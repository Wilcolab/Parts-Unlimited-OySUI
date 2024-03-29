# Parts Unlimited Frontend

The Parts Unlimited Frontend is an SPA written with [React](https://reactjs.org/) and [Redux](https://redux.js.org/)

## Getting started

- Make sure you have yarn https://classic.yarnpkg.com/en/docs/install/#mac-stable
- In the main folder cd to frontend folder and run `yarn install`

Make sure your server is up and running to serve requests.

###  15-06-21

- Bug fix [Update in package json file on the start script for backend. It is now "rails s" insted of "yarn start"]
- A documentation update [Added more information about what is needed and the project setup]

# How Has This Been Tested?

- Test A [After run `yarn start` you should go to your browser and tap `http://localhost:3000/`. You should see the app running]

## Pages overview

- Home page (URL: /#/ )
  - List of tags
  - List of items pulled from either Feed, Global, or by Tag
  - Pagination for list of items
- Sign in/Sign up pages (URL: /#/login, /#/register )
  - Use JWT (store the token in localStorage)
- Settings page (URL: /#/settings )
- Editor page to create/edit articles (URL: /#/editor, /#/editor/slug )
- Item page (URL: /#/item/slug )
  - Delete item button (only shown to item's author)
  - Render markdown from server client side
  - Comments section at bottom of page
  - Delete comment button (only shown to comment's author)
- Profile page (URL: /#/@username, /#/@username/favorites )
  - Show basic user info
  - List of items populated from seller's items or user favorite items

# Welcome to the Parts Unlimited repo

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

After setup each section you should start the app use: `yarn start` in the main directory, it'll start both the backend and the frontend.

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@janesmithwilco` as reviewer.

Changelog:

###  14-07-21

- Center profile follow information for mobile devices
- Update gem acts_as_follower dependency in Gemfile file. This was causing problems with following other issues.

###  13-07-21

- Bug fix displaying broken image on the items when the item.image was empty.
- Bug fix when click on favorite an item.

###  21-06-21

- Bug Fix when loading the application without data in the DB.
- Adding Data to the seeds.rb file

###  15-06-21

- Bug fix [Update in package json file on the start script for backend. It is now "rails s" insted of "yarn start"]
- A documentation update [Added more information about what is needed and the project setup]
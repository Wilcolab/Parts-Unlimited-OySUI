# Parts Unlimited Backend

The Parts Unlimited backend is Ruby web app written with [Ruby On Rails](https://rubyonrails.org/)

## Getting started

- Make sure you have rails https://gorails.com/setup/osx/11.0-big-sur
- In the main folder cd to backend folder and run `bundle install`
- To start the app use: `rails s` from the backend directory.

Note: The current version of Ruby on the Gemfile is 2.7.0
Make sure your DB is up and running.

## Dependencies

- [acts_as_follower](https://github.com/tcocca/acts_as_follower) - For implementing followers/following
- [acts_as_taggable](https://github.com/mbleigh/acts-as-taggable-on) - For implementing tagging functionality
- [Devise](https://github.com/plataformatec/devise) - For implementing authentication
- [Jbuilder](https://github.com/rails/jbuilder) - Default JSON rendering gem that ships with Rails, used for making reusable templates for JSON output.
- [JWT](https://github.com/jwt/ruby-jwt) - For generating and validating JWTs for authentication

## Folders

- `app/models` - Contains the database models for the application where we can define methods, validations, queries, and relations to other models.
- `app/views` - Contains templates for generating the JSON output for the API
- `app/controllers` - Contains the controllers where requests are routed to their actions, where we find and manipulate our models and return them for the views to render.
- `config` - Contains configuration files for our Rails application and for our database, along with an `initializers` folder for scripts that get run on boot.
- `db` - Contains the migrations needed to create our database schema.

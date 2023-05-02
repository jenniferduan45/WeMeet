# WeMeet

This is an event-organization app for college students to post, search, join, comment, and rate events. It is developed in Ruby on Rails.

## Group Demo Video
https://youtu.be/30avNv94V8k

## Dependency
1. install `postgreSql` on your local computer. [Reference here](https://www.postgresql.org/download/)
2. install `reek` using command `gem install reek` in your terminal. [Reference here](https://github.com/troessner/reek)
 
## How to build and run locally
1. Run `bundle install --without production` to install dependencies and related gems
2. Run `rake db:migrate:reset` to load up all migrations
3. Run `rake db:seed` to load initial values
4. RUn `rails s` to start the server

## How to run tests
1. `rake cucumber` for BDD tests.
2. `rake spec` for TDD Rspec tests.
3. coverage reports are generated seperated for both `Spec` and `Cucumber` and both are under the `coverage` folder.

Railscast sm-rc71 and 275 and 257
================================
RSpec
```
It is a testing framework.
```

git clone
```

```
database setup
```
rake db:create
rake db:migrate
rails g bootstrap:install
rails g simple_form:install
```
scaffold
```
#todo
rake db:migrate
rails g bootstrap:themed orders -f
````
Gemfile
```
gem 'rspec-rails', '~> 3.0.0.beta'
bundle install
rails generate rspec:install
rake db:migrate RAILS_ENV=test
bundle exec rspec spec/controllers/posts_controller_spec.rb
```
new gem intro
```
Guard -- to automatically running the rspec when i save it and run 'guard init rspec' to create guard file
capybara -- acceptence test framework with selenium support built in.
factory_girls_rails - replacement of fixtures. a library for setting object as test data.
run 'bundle exec guard' -- so that guard can detect changes
```
To generate new rspec file
```
rails g integration_test any_name
```
Rails Server
```
rails s
```
Rails Console
```
rails c
```
sm-rc257
```
is for views and javascript
```

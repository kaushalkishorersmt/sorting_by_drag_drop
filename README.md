# README

- rails new sorting_by_drag_drop -d --database=postgresql
- rails g scaffold Questions question answer
- rake db:setup
- rake db:migrate

- https://github.com/jquery-ui-rails/jquery-ui-rails
- https://github.com/swanandp/acts_as_list
- https://github.com/twbs/bootstrap-rubygem

gem 'bootstrap', '~> 4.0.0.beta'

gem 'jquery-rails'

gem 'jquery-ui-rails'

gem 'acts_as_list'


- bundle

- rails g migration AddPositionToQuestions position:integer
- rake db:migrate

- mv app/assets/stylesheets/application.css app/assets/stylesheets/application.scss
- mv app/assets/javascripts/questions.coffee app/assets/javascripts/questions.js

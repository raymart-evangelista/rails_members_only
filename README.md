# README

This is part of the Ruby on Rails Members Only Project in The Odin Project's Ruby on Rails Curriculum. Find it at https://www.theodinproject.com/lessons/ruby-on-rails-members-only.

What confused me the most was how devise and Turbo Drive don't play nicely together. I kept thinking that most of the errors I encountered was because of that, but that wasn't always the case. An 'aha!' moment was fixing the Routes file with `resources :posts, only: [:new, :create, :index]` instead of what it was before. This made it so submitting Post forms worked.

## Resources

### Helped...
- set up Devise with Turbo conflict: https://www.youtube.com/watch?v=XJ27X06GVrI

- add foreign key to PostController#create: https://stackoverflow.com/questions/31480645/how-to-add-foreign-key-value-on-controller-create

- remove tables that interfered with db:migrate: https://stackoverflow.com/questions/17715903/rake-dbmigrate-table-already-exist

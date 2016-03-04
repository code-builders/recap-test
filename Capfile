require 'recap/recipes/rails'

set :application, 'demo'
set :repository, 'https://github.com/code-builders/recap-test.git'

server 'demo@159.203.228.5', :app

after "deploy:update_code", "rails:db:migrate"

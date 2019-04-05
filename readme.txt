From this tutorial:
https://www.youtube.com/watch?v=a-jcTib9ZPA

Repo:
https://github.com/devteds/e1-rails-on-docker


mkdir noteapp
cd noteapp
# Create Gemfile using scaffold file
# touch Gemfile.lock
# Create Dockerfile using scaffold file
# Create docker-compose.yml using scaffold file

docker-compose run app rails new . --force
docker-compose build
docker-compose up -d

# View new Rails app at http://localhost:3001

# Edited the Dockerfile and Gemfile slightly from what was presented to get it to work successfully.

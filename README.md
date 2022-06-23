# Ruby on Rails 7 with Docker setup
Create new Rails 7 project with Docker setup

To create new Ruby on Rails project with Docker setup.

Instructions:

1. Insert files to the new Rails project
	- Dockerfile
	- docker-compose.yml
	- entrypoint.sh
	- .dockerignore
	- .env.example
	- config/database.yml

2. database.yml is using DATABASE_URL variable for 1 line database connection. Don't copy the files if you don't prefer the said setup.

3. Update docker-compose.yml variable db > environment, if values does not met your needs.

4. Update Rails project .env with .env.example values
	- command: cp .env.example .env
	- update environment (.env) values based on your preferred setup, in this case DATABSE_URL 

5. Run docker
	- command: docker compose up


-----
This Rails 7 with Docker project is created to prevent version incompatibility with other server setup.

-- jasonmag

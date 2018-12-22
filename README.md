# Simple App with Docker and Redis

1. Create package.json
2. Create app file (index.js)
3. Create Dockerfile
4. Create docker-compose.yml
5. docker compose commands
- ```docker-compose up``` - the same as  ```docker run <image>```
- ```docker-compose up -d``` to launch all the containers in the project in the background.
- ```docker-compose up --build``` (re)build from the current directory, and run the image.
- ```docker-compose ps``` to see all the containers in the project running. (This will not list other containers running outside the project not listed in docker-compose.yml in the same directory)
- ```docker-compose down``` to stop all the containers in the project.

# Docker Yarn Example

## Building and running

Quick start:

`docker-compose run --build`

This will build and run the application.

To build:

`docker-compose build`

This builds an image which creates a layer with the application dependencies.

To run:

`docker-compose up`

This mounts the app code into a running container and should be available at <http://localhost:3000/>

Note: If you're on Windows using docker toolbox it might be <http://192.168.99.100:3000/>

Try changing your code (text in App.js for example) and see the browser auto refresh.

Stopping the app:

Hit `Ctrl+C`

Then `docker-compose down`

To clean up:

`docker-compose rm`

## Credits

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Express Docker
This is a simple example of how to run an Express app inside a Docker container.
It has several bash scripts to help doing different stuff.

## Preconditions
You have docker installed in your computer. Go to [docker.io](http://docker.io) for instructions.

## Scripts
- `start-dev.sh`: Runs a container with a console for development purposes. It is like your own computer's console but inside a Docker container with all the tools you need already there and without polluting your own computer with those tools.
- `build-image.sh`: Once you're happy with your app run this script to create an image with the current state of your app. Take into account that once you create that image, no matter what you change in your code, the image will still run the app like it was when you created the image.
- `run-image.sh`: This runs your previously created image inside a container.
- `remove-image.sh`: Remove your image. Useful if you want to create a new one with a newer version of your app.

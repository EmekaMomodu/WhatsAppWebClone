# Whatsapp Web Clone

Clone of Whatsapp Web UI. Check out its [backend service here](https://github.com/EmekaMomodu/WhatsAppWebClone-Backend) which implements WebSocket communication.

Built with React and Socket.IO .

## Run this project locally

1. Open terminal in project's root directory i.e where the file named Dockerfile is located.
2. Run command `docker build . -t whatsapp-web-clone-ui` to build the docker image.
3. Run command `docker run -p 3000:3000 -d whatsapp-web-clone-ui` to spin up a container for the created image.
4. This web application should start running on `http://localhost:3000/`.

_N.B: You will need to run the backend service to simulate getting responses when you send in a message._

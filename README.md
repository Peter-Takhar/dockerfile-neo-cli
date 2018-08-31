# dockerfile-neo-cli

Very simple docker image to set up neo-cli in the Ubuntu environment\
To run this image, enter:
```
docker run -it -d -p 10332:10332 ubuntu-neo-cli
```
You are then able to communicate with the node through the JSON-RPC API.

Neo-cli Installation: <http://docs.neo.org/en-us/node/cli/setup.html> \
Neo-cli Api Reference: <http://docs.neo.org/en-us/node/cli/2.7.4/api.html>

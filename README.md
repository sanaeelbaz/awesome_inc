## Awesome Inc.
## Prerequisites
this section describes the requirements for this website (GoHugo..).
The production website is hosyed in an Ubuntu 18.04 Docker container.
The applications "GoHugo" and "Make" are installed with apt-get update && apt-get install -y hugo make.
GNU Make 4.3.
Hugo Static Site Generator v0.80.0.
## Lifecycle
When running the command hugo server -D the website is in the developement mode.
When running the command hugo -d dist the website is built into the folder "dist/", and it is in the production mode.

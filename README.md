# Actions Runner

This actions runner is built on the standard github actions runner and adds the following tools to help speed up our deployments:

* Docker Runtime including Docker Compose v2
* Python3 PIP
* NodeJS 20
* CURL

This allows a number of common use cases for us to run without needing to download additional content during the build process.

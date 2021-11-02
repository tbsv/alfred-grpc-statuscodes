# alfred-grpc-statuscodes

Use Alfred search to get quick info about gRPC status codes and hit enter to get more information about each code on the [gRPC Status Codes](https://grpc.github.io/grpc/core/md_doc_statuscodes.html/) website. 

## Installation
1. [Download latest version](https://github.com/tbsv/alfred-grpc-statuscodes/releases)
2. Double click the `GRPC-Status-Codes.alfredworkflow` file for installation

## How to use
To invoke **gRPC status codes**, simply type `grpc` followed by the status code you would like more information about. The workflow will display the status code, along with the name and a brief description. You can also search for status codes by name, so entering `grpc internal` will return `13: INTERNAL`. If you would like more information about a status code, simply hit `enter` to be taken to the [gRPC Status Codes](https://grpc.github.io/grpc/core/md_doc_statuscodes.html/) website.

## Credits
* [Alfred](https://www.alfredapp.com/) | Without the incredible launcher, this easy-to-use workflow wouldn't be possible.
* [gRPC Status Codes](https://grpc.github.io/grpc/core/md_doc_statuscodes.html/) | The grpc-related info content is provided by this website.
* [ma3574](https://github.com/ma3574) | Thanks for providing [alfred-http-status-codes](https://github.com/UpSync-Dev/alfred-http-status-codes) worklflow. This workflow is based upon the http version. Because of my own requirement, I created the grpc version out of it.
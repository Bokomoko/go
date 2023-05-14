# Go bare bones dev container

This is a skeleton dev container for developing Go language applications using VS Code and dev containers. The idea is to start from this skeleton and add the things you want.

## How to install

Make sure that you have Docker installed and running on your system. After starting the Docker daemon, clone/fork this repo to your dev machine and open the directory/folder with the sample "hello world". VS Code will ask you to open the project in a dev container. Reply YES and you're good to go.

## Advantages of using dev containers with VS Code

The main advantage is that you don't need to install/configure anything on your dev machine. The dev container can be quickly deployed to any other computer, virtual computer or web dev space like Github's CodeSpace. By using dev containers you will make sure your development environment is the very same as the production environment so no more "It works on my machine!" arguments.

Whenever you use VS Code for Go lang development you may add the extensions that make sense for Go. This is particularly useful if you code in multiple languages like JavaScript/React for front end. You keep VS Code light with the extensions pertaining to the language you're coding. Debuging tools, database clients, testing and debuging extensions that are specific to a project or language will be loaded only on those projects where it makes sense.

The same applies for environment variables, credentials, version of libraries, and things like that.

Another advantage is that any configuration change needed for using Go language on the dev container won't cause any issues in your local machine. And vice-versa, that is, nothing you would do on your computer will jeopardize the development of the go environment in your project.

For more information on dev containers, [please follow this link] (https://learn.microsoft.com/pt-br/training/modules/use-docker-container-dev-env-vs-code/)


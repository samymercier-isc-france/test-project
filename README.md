# What is the project ?

It is a personnal project to train with some development and deployment tools in order to learn and improve, it has some features and will probably will have more, here a list of all features actually available :
    - A lottery wheel 


## Project requiremenents 

 - Docker installed on your machine if you want a fast deployement
 - VS Code and Node.js installed on your machine for development and slower desployement

## Deploying the app with Docker

Run `docker-compose up` in the project's root (test-project folder)
Navigate to `http://localhost:4201/` to access the project.

Make sure Docker is installed on your machine and running !
Only the Angular part is Dockerised !

## Running web version of the app for development

Get to the angular project root by typing `cd./testing-angular/` in the terminal.
Run `npm i` to install/update all project's dependencies
Run `ng serve -o` for a dev server. Navigate to `http://localhost:4200/` to access the web project.

## Running mobile version of the app for development

Get to the ionic project root by typing `cd./testing-ionic/` in the terminal.
Run `npm i` to install/update all project's dependencies
Run `ionic lab -o` for a dev server. Navigate to `http://localhost:8200/` to access the mobile project

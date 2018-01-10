# Welcome to "Project Tracking" using EmberJS

## Installation

You can install EmberJS in your Linux distribution using:

`npm install -g ember-cli`

Maybe you should update npm using:

`npm update -g`

## Creating a new project

Amber-cli help us making all the basic setup:

`ember new project-tracking`

Changing directory:

`cd project-tracking`

Remember, angular-cli is a fork from amber-cli. So, you can run ember serve:

ember serve

## First run

Isn't important, but you migth open the initial page on `http://localhost:4200/`

 :eyes:

## The main page

Open the file `app/templates/application.hbs` in your favorite editor (like Atom) and comment the line `{{welcome-page}}` like this:

`{{!welcome-page}}`

Now, you can put your code inside that. On this case, I wrote the name of project:

`<h1>Project Tracking</h1>`

Creating a Project's menu:

`ember generate route projects`
`ember generate route appointments`

## Also...

clone this project to see more details.

Participation Community Dashboard
=====

This project is a Mozilla Community Dashboard to gather the most important statistics about certain countries from [mozillians.org](https://mozillians.org).

You can find the initial spec here: [participation-org/issues/133](https://github.com/mozilla/participation-org/issues/133).

# Contributing

We will use this repo's issues to track the work. Feel free to jump in.

## Getting set up

It's as easy as forking this repository, change the necessary files and create a Pull Request.

To get started, you will need a mozillians.org API key though. You can get it easily on your mozillians.org profile page:

* Log in to mozillians.org
* Go to your "Edit your profile"
* At the bottom you see "Developer"
* Click on "Manage API keys"
* Register a new app
* Add the resulting API key to the `config.js` file in the root directory of this project.

### Setting up the project on your local environment

1. Install [Node](http://nodejs.org)

2. Inside the project folder run the following command to install the Grunt and Bower CLIs

        sudo npm install -g grunt-cli bower

3. Finally, install the project dependencies and libraries with the following commands:

        npm install
        bower install

### Running the project locally in development mode

To run the server in development mode, simply type:

    grunt serve

# Smple dev container app #

This repo showcases how a .devcontainer.json would look like for a laravel project.

The idea is that you open this folder on VSCode, and the editor takes care of pulling the containers for you. 
So as a developer the only thing you have to do is to open the editor and start coding.

## Setup ##

To make this work add the following to your `.env` file:

```ini
WWWGROUP=1000
WWWUSER=1000
```

VSCode will use those values to connect & start services on the container that's going to run your laravel app.

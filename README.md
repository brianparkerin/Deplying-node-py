# Deploying-node-py
### Deploying any app on Node &amp; Python on Heroku Linux/Win


### Basic Commands:

Install the Heroku CLI
Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login
Clone the repository
Use Git to clone MYAPP's source code to your local machine.

$ heroku git:clone -a "MYAPP"
$ cd brimimar
Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master


### Source Docs:

https://devcenter.heroku.com/articles/python-runtimes

https://devcenter.heroku.com/articles/python-support#specifying-a-python-version

https://devcenter.heroku.com/categories/deployment

https://devcenter.heroku.com/articles/heroku-cli-commands

https://www.youtube.com/watch?v=t5G5YPEZWZ0

https://www.youtube.com/watch?v=fxavwHPJ36o


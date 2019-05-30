# Sparta-Chef-Dev-Prod

## How to use

Clone down this repo on to your local machine.

Then enter the directory and run the command `berks vendor cookbooks` to create the cookbooks.

Then run `vagrant up` to start the virtual machine.

`vagrant ssh app` to enter the app instance and then start the app with `pm2 start /home/ubuntu/app/app.js`

Then go to [this site](http://development.local/) to use the app.

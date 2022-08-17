# README
How can you test the A2HS feature in development?
* Install ngrok
* # mac OSX > brew cask install ngrok

# linux > sudo snap install --edge ngrok


Allow requests by adding the following to your environment configuration
# config/environments/development.rb
config.hosts << /[a-z0-9\-]+\.ngrok\.io/

Once your app has loaded, click on the add to homescreen shortcut Firefox a2hs button (Firefox) or click on menu Chrome menu then Add to homescreen (Chrome)

Now you can access your app from your homescreen and experience the fullscreen navigation

Launch a ngrok tunnel alongside your rails server
ngrok http 3000

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

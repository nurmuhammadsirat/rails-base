# Base Rails

This is a basic Rails setup that I always use before starting development.

## What's Included?

Current Rails version: 5.2.1

Additional gems included:

* devise
* omniauth (with omniauth-google-oauth2)
* pry-byebug
* rspec-rails
* dotenv-rails

## Additional Setup After Cloning

* Follow instructions at https://github.com/zquestz/omniauth-google-oauth2 to enable Google login.
* Create a .env file and add the following environment variables: GOOGLE_CLIENT_ID & GOOGLE_CLIENT_SECRET

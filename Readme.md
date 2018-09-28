# Unite Tenant Administration Postman Collection

## How to use the application

* Install Postman `https://www.getpostman.com/`
* Edit `Unite Integration.postman_environment` in order to use the integration environment by entering the value of your
    * `unite_id`
    * `unite_secret`
    * `tenant_refresh_token`
    * and optionally a `company_refresh_token`
* Using these values the collection will automatically retrieve new access tokens for you as needed.
* Import the `Unite Production.postman_environment.json` file
* Import the `Unite Tenant Administration.postman_collection.json` file
* Select an the Integration environment in the top right corner and try out the different endpoints that are available.

## Important

This application is to be used by companies that are integrating with the Unite Platform. 
Additional documentation describing this authorization process can be found at 
https://portal.unite.eu/developers/api-access-for-3rd-party-client

## Requirements

Unite Credentials are required to use this example application.

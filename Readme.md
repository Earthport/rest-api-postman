# Earthport REST API Postman Collection

## Getting Started
This repo contains a Postman collection of sample requests to the Earthport REST API. 
It also contains environment configurations for sandbox and customer-integration.

You will need to do the following :-
 1. Install Postman
 2. Import the Postman collection from this repo
 3. Configure an environment in Postman and define a number of environment specific variables or import the environment configuration supplied within this repo and override the values with your client_id and client_secret.

### Environment Variables
To learn how to create environments see the [Postman documentation](https://www.getpostman.com/docs/v6/variables_and_environments/test_multi_environments)
You will need to define 3 variables:-
1. host (this has already been defined for you)
2. client_id
3. client_secret

You can download Postman from https://www.getpostman.com
Installation instructions can be found [here](https://www.getpostman.com/docs/v6/postman/launching_postman/installation_and_updates)
Earthport will have supplied you with your client_id and secret. The host will depend on which test environment you are testing against.

#### Sandbox Environment
host = api-sandbox.earthport.com

#### Customer Integration Environment
host = api-integration.earthport.com
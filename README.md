# light-go-rest-api

Demo project to display the setup for a REST api in golang without dependencies

## Endpoints

- `/coasters` allows you to GET all coasters and POST new ones.
- `/coaster/id` allows you to GET a specific coaster.
- `/coasters/random` redirects to a random coaster.
- `/admin` allows access to the secret admin portal with basic auth.

## Requirements

Requires `ADMIN_PASSWORD` as an environment variable. This is used to authenticate for the admin portal.

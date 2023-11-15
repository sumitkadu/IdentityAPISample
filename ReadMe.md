Installation Pre-requisities

1. Need SQL server database named Identity setup on localhost to execute this project.

Execute Locally

1. Execute project with or without Docker image.
2. Use the URL to access swagger
3. Use Register Admin API to create user for you
4. Use Login API to generate bearer token with user created in step 3.
5. Use the token to make a call to weatherforecast API.

The project uses ASP.NET Core Identity for Authentication and Authorization. User Admin role for claims to weatherforecast API.

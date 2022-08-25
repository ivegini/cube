# cube
A React application and .NET server for managing product transactions.

## Running the app
To run the app, you will need to have Docker installed. From the root of the project, execute
```
docker compose -f docker/docker-compose.yml up
```

You can then go to `http://localhost:8080/` to view it in the browser.

You can also go to `http://localhost:8080/swagger` to read the documentation on the server API.

## Unit tests
To test the application, from the root of the project, run
```
cd server && dotnet test
```
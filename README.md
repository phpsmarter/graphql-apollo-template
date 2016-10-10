#graphql-apollo-template
This is a simple GraphQL Backend template based on the [apollo](http://dev.apollodata.com/tools/)
GraphQL Server.

The Project includes:
* a example data schema and mock data
* lint tests setup for react
* a travis file to run tests on travis and continuous integration to Azure Web App

## Installation

Clone the repository and run `npm install`

```
git clone https://github.com/lukasreichart/graphql-apollo-template <Application Name>
cd <Application Name>
npm install
```

### Updating the application name
Update the Application name in ```package.json```, ```config/config.js``` and in the ```.travis.yml``` file.


## Starting the server


### In Debug mode
```
npm run debug
```
### In Production mode
```
npm run build-and-start
```
Which will generate the code into the /build directory.

The server will run on port 8080 or on port 80 in production mode. You can change this by editing `server.js`.

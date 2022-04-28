# Cosmos Bookstore

Cosmos Bookstore is a sample books catalog application that demonstrates the capabilities of Azure Cosmos DB API for MongoDB.

Some of the functionalities being demonstrated are:

- Using template for resource creation
- App services
- Connecting to the database & the client configuration
- Reads & Queries
- Sorting & Indexing
- Updates
- Using different operators
- Using the pipeline of azure to get the deployment code from github

## Deploy the app quickly

Clone this repository and navigate to the root of the directory.

Follow the steps below to deploy the app with minimal effort and begin experimenting with the application and the codebase.

### Deploy the resources to Azure

The template below deploys the application into an Azure App Service instance and creates an Azure Cosmos DB account.
Simply enter the Resource Group name in this template to deploy the resources.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnayakshweta%2FCosmosBookstore%2Fmaster%2Fdeployment%2Fazuredeploy.json)

### Connect to the application

Now you can try out the application by browsing to the app service URL.
You can find the URL in the overview section of the App Service resource created by the deployment template.
![Cosmos Bookstore Main page](deployment/docs/images/cosmosbookstoremainpage.png)

## Dataset

 ["GoodReads 100k books"](https://www.kaggle.com/mdhamani/goodreads-books-100k) 

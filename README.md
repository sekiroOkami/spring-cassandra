<!--- STARTEXCLUDE --->
# Spring Data Cassandra REST API
*10 minutes, Beginner, [Start Building](https://github.com/DataStax-Examples/spring-data-starter#prerequisites)*

This application uses Spring Data Cassandra and DataStax Astra DB to build a REST API for a backend service that interacts with products and orders.
<!--- ENDEXCLUDE --->

![image](https://user-images.githubusercontent.com/3254549/90944387-439a1f00-e3d3-11ea-9df4-e8a5580c62cd.png)

## Objectives
* Run a REST API that connects to DataStax Astra DB

## How this works
We're using Spring Data Cassandra and Datastax Astra DB to build a REST API that stores Products and Orders.

## Get Started
To build and play with this app, follow the build instructions that are located here: [https://github.com/DataStax-Examples/spring-data-starter](https://github.com/DataStax-Examples/spring-data-starter#prerequisites)

<!--- STARTEXCLUDE --->
# Running Spring Data Cassandra REST API
Follow the instructions below to get started.

## Prerequisites
Let's do some initial setup by creating a serverless(!) database.

### DataStax Astra
1. Create a [DataStax Astra account](https://dtsx.io/38HWu73) if you don't already have one:
![image](img/01.png)

2. On the home page. Locate the button **`Create Database`** both vector and non-vector support the Cassandra CQL
![image](img/02.png)

3. Populate the fields and click create database 
![image](img/03.png)

4. After your database is provisioned, we need to generate an Application Token for our App. Go to the `Settings` tab in the database home screen.
![image](img/04.png)

5. Generate a token by clicking `Generate Token` and give it a name.
![image](img/05.png)

6. After you have your Application Token, head to the database connect screen and select the driver connection that we need. Go ahead and download the `Secure Bundle` for the driver.
![image](img/06.png)

### Github
1. Click `Use this template` at the top of the [GitHub Repository](https://github.com/DataStax-Examples/spring-data-starter):
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-use-template.png)

2. Enter a repository name and click 'Create repository from template':
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-create-repository.png)

3. Clone the repository:
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-clone.png)

## 🚀 Getting Started Paths:
*Make sure you've completed the [prerequisites](#prerequisites) before starting this step*
  - [Running on Gitpod](#running-on-gitpod)

### Running on Gitpod
1. Click the 'Open in Gitpod' link:
[![Open in IDE](https://gitpod.io/button/open-in-gitpod.svg)](https://dtsx.io/2QjoULs)

2. Once your Gitpod workspace has loaded, you'll be asked to paste your service account credentials in the Gitpod terminal at the bottom of the screen:
![image](https://user-images.githubusercontent.com/3254549/90944321-e900c300-e3d2-11ea-9624-dae5f81b6a0a.png)

3. When the app is finished building, click the 'Open Browser' button on the bottom right of the screen:
![image](https://user-images.githubusercontent.com/3254549/90944371-249b8d00-e3d3-11ea-8305-b7d4fad9742c.png)

4. You've successfully build a Spring Data Cassandra application!
![image](https://user-images.githubusercontent.com/3254549/90944387-439a1f00-e3d3-11ea-9df4-e8a5580c62cd.png)
<!--- ENDEXCLUDE --->

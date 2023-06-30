# Ecommerce Back End

## Description
The Ecommerce Back End App is built on Express.js API and offers comprehensive functionality. By adding the database name, MySQL username, and password to an environment variable file, users can establish a connection to the database using Sequelize. Running schema and seed commands creates a development database and populates it with test data. Invoking the application starts the server and syncs Sequelize models with the MySQL database. Insomnia Core can be used to access API GET routes for categories, products, and tags, displaying data in JSON format. Additionally, API POST, PUT, and DELETE routes can be tested successfully to create, update, and delete data within the database.

## How to Use
Start by entering your username and password for myslq in the terminal. Log in to your terminal and source the schema file. Then seed your files by initiaing the command node seeds/index.js in your terminal. After put node server.js into your terminal. Then in your insomnia app insert the endpoints to see results with GET. You may POST, PUT, and DELETE by utilizing the various endpoints in the routes/api folders.

## Screenshot of application
<img title="Ecommerce Back End" alt="Screenshot of Ecommerce Back End App in Insomnia" src="assets\Screenshot Ecommerce Back End.png">

## Walkthrough Video
<iframe src="https://drive.google.com/file/d/1K8xvlnVpkH1IT6kxd9CXDW3Rzc2fa3Q3/preview" width="700" height="480"></iframe>
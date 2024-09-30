# Readme

This is a simple project to demonstrate how to use standalone static swagger ui.

## How to run

1. Clone the project
2. Replace the `swagger.json` file or change the url referencing to it on `swagger-initializer.js`
3. Serve the project using a web server. You can use `http-server` or `live-server` for example.

## How to use the latest version of Swagger UI

1. Go to [Swagger UI Installation Page](https://swagger.io/docs/open-source-tools/swagger-ui/usage/installation/)
2. Navigate to the `Plain old HTML/CSS/JS (Standalone)` section
3. Follow the instructions
  3.1. Download the latest version of Swagger UI
  3.2. Extract the files
  3.3. Copy the `dist` folder to your server
  3.4  Open the `swagger-initializer.js` file and change the `url` property to the path of your `swagger.json` file
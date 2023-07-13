# Serverless Web Application development using AWS and ArcGIS

A serverless web application was developed that allowed users to request rides on unicorns from the Wild Rydes fleet. The application offers an easy-to-use interface where users can specify their pickup location and interacts with a backend RESTful web service to submit and process ride requests. Additionally, the application allows users to register and log in before making ride requests. The architecture of the application utilizes various AWS services such as Lambda, API Gateway, DynamoDB, Cognito, and Amplify Console. Amplify Console is responsible for hosting and deploying the static web resources, while JavaScript in the user's browser handles data communication with the backend API built using Lambda and API Gateway. Amazon Cognito ensures user authentication and management, and DynamoDB serves as the storage layer for the API's Lambda function, enabling data persistence.


<img width="427" alt="image" src="https://github.com/gaurivp/Serverless-Web-Application-development-using-AWS/assets/92565931/dc8f5137-0215-453b-8387-c079c1de5a38">

















Image: https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/ 

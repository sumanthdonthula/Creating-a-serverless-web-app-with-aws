# Creating-a-serverless-web-app-with-aws


I would thank hervvenevon for his wildrydes-site app on repository Ive cloned it and used for my project
git link-https://github.com/hervenivon/wildrydes-site

Process:
Basically for dynamically hosting our website on cloud we have to create a repository and added on aws amplify.Then we can configure user pools using cognito on aws for registration purpose for a new user.Then for maintaining backend of our site we should use aws lambda and aws dynamodb in order to give response to clients the backend runs on cloud.To make our application dynamic we should add an api on aws and configure.

I posted the upgraded wildrydes-site in this repo.

You can see the working of my web application here: 
https://drive.google.com/file/d/1ZsJMm-3Y7yJkLoVBlREEDIif9edIbVbv/view?usp=sharing

In user pools we can see number of people who have signed up with our app.

![image](https://user-images.githubusercontent.com/46747610/119274684-cbe17500-bc2e-11eb-8ede-988b13a28323.png)

In dynamodb we can see the dynamic tables created by our user while they are accessing our app

![image](https://user-images.githubusercontent.com/46747610/119274719-eca9ca80-bc2e-11eb-8727-f449b7c3017a.png)

To deploy your serverless web application on aws follow this link:
https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/

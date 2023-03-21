# Workflow of maven application  for sonarqube 

### I have created this template for the maven application coverage on the sonarqube. With the help of this template, Whenever you will push your code or pull your code with the changes into the particular folder which I mentioned in the template. Checks will trigger and you will be able to see the coverage on the sonar qube.

### You just need to follow the below step to run this template:-

```
Step 1: 
You need to set up a sonarqube server and create a project. Make sure you have a copy of the project key or name and also a copy of the token of that project.



Step2: 
Now you need to store that project key, token, and your host in the GitHub secrets. Make sure you have the same key of your secrets mentioned in the workflow or you can update the workflow environment variable as per your need.

Step 3: 
you just push your code to the repo and the workflow will trigger. You will be able to see the coverage on the sonarqube server.
````
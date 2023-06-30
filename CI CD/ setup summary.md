# CI/CD setup summary

### 1. Code Repository:
The source code is managed using a Git repository hosted on GitHub. We work with branches and ensure that the code is merged with the main branch.

### 2. Automated Testing:
We have implemented Java Espresso tests for our app, allowing us to continuously test the frontend of the application. Additionally, we utilize Apptim to regularly assess the app's performance.

### 3. Continuous Integration (CI):
Whenever there is a code update in the GitHub repository, the CI process automatically starts. GitHub Actions runs tests and the build process to ensure the code is error-free and can be compiled successfully.

### 4. Continuous Deployment (CD):
After each successful build and passing CI processes, the app is deployed to a testing environment. Here, we can review, test, and provide feedback on the app.

### 5. Release to Production
Once the app has been successfully tested in the CD prozess and all requirements are met, We deployed it to the production environment.

With this CI/CD setup, we can work on our app safely and efficiently.











# Mobile App Project Documentation

## Project Overview
This repository contains the Android mobile application code for the project.

## Setup Instructions
1. **Clone the Repository**: Use the command `git clone https://github.com/nikk-devops/mobileapp.git` to clone the repository.
2. **Install Dependencies**: Navigate into the project directory and run `./gradlew build` to install the necessary dependencies.
3. **Configuration**: Update the configuration files in the `app/src/main/res` directory as per your environment settings.

## How to Use the Harness CI/CD Pipeline
1. **Connect Your Repo**: Go to the Harness platform and connect your GitHub repository.
2. **Create a New Pipeline**: Select the repository and create a new pipeline for your Android application.
3. **Configure Build and Test Steps**: Set up the build and test steps using the Harness UI. You can run `./gradlew test` to execute tests.
4. **Deployment**: Define deployment steps to push the app to the Google Play Store or any other environment as needed.
5. **Triggering the Pipeline**: You can manually trigger the pipeline or set it up to trigger automatically on pushes to the main branch.

## Conclusion
This README provides a quick start guide to set up and use the Harness CI/CD pipeline for the Android mobile application. For further customization, refer to the official Harness documentation and Android development guides.
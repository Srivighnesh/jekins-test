# Project Overview

This Jenkins test project is designed to demonstrate the capabilities of Jenkins in Continuous Integration and Continuous Delivery. It contains examples of Jenkins pipelines, job configurations, and integration tests.

## Features
- Jenkinsfile for defining the CI/CD pipeline
- Example scripts for automated testing
- Configuration for building and deploying applications

# Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Srivighnesh/jekins-test.git
   cd jekins-test
   ```

2. **Install Jenkins**:
   - Follow the [official Jenkins installation guide](https://www.jenkins.io/doc/book/installing/).

3. **Import the Job**:
   - Open Jenkins dashboard.
   - Click on `New Item` and select `Pipeline`.
   - Use the `Jenkinsfile` from this repository to configure the pipeline.

4. **Run the Pipeline**:
   - Trigger the pipeline manually or configure it to run on specific events (e.g., GitHub webhook).

# Important Commands

- **Start Jenkins**:
  ```bash
  java -jar jenkins.war
  ```

- **Access Jenkins**:
  - Open your web browser and navigate to `http://localhost:8080` (default Jenkins port).

- **Build a Job**:
  - Click on the job in the Jenkins dashboard and click `Build Now`.

- **View Console Output**:
  - Click on the build number to view the logs of the build execution.

# Conclusion

This repository serves as a template for using Jenkins in your projects. Feel free to modify and tweak the configurations as per your project needs.
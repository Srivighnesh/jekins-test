# Jenkins Setup Instructions

## Windows Service Startup
1. Install Jenkins using the installer.
2. Open the command prompt as an administrator. 
3. Run the following command to start Jenkins as a service:
   ```bash
   jenkins.exe install
   ```
4. Start the Jenkins service with:
   ```bash
   jenkins.exe start
   ```

## Login Credentials
- **Default Username:** admin
- **Default Password:** You can find the initial admin password in the `Jenkins_home/secrets/initialAdminPassword` file after the installation.

## SCM Configuration Notes
1. For Git: 
   - Ensure Git is installed on your system and available in PATH.
   - In Jenkins, navigate to **Manage Jenkins** -> **Global Tool Configuration** -> **Git** and configure the path to Git executable.
2. For SVN: 
   - Similarly, configure the path to the SVN executable under **Global Tool Configuration**.
3. Setup Webhook: 
   - For GitHub, add a Webhook to your repository pointing to `http://<your-jenkins-url>/github-webhook/`. This triggers builds on code push.

Make sure to adjust any paths as per your installation specifics!
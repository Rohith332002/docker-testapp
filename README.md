# docker-testapp
Testing Jenkins webhook integration 
Auto trigger test from GitHub
CI test: GitHub webhook → Jenkins auto build 
## CI/CD Pipeline

This project uses Jenkins for continuous integration.
Whenever code is pushed to the main branch, Jenkins automatically:
- Pulls the latest code from GitHub
- Runs the build steps
- Verifies the project structure

Webhook integration is configured using ngrok for local Jenkins testing.

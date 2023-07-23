# event-manager
Event management solution for communities

## Project structure
Use AWS for infrastructure - that is, everything related hosting.

- Amazon API Gateway to handle endpoints
- Amazon DynamoDB as the database
- Amazon S3 for static resources?

Use Terraform to define the AWS infrastructure - that is, everything related to setting AWS up

Use Python or JavaScript for the AWS Lambda functions

Use Vue or a template framework for the frontend

Use GitHub for version control
- GitHub Actions to publish code changes to AWS


## Setup for development
*A setup script will probably be made that installs and sets up the following things as well*

- [ ] install WSL
- [ ] install VSCode
- [ ] install GH CLI
- [ ] install AWS CLI
- [ ] install Terraform CLI
- [ ] install Node/NPM and/or Python/Poetry tools

### Unanswered questions
*These things still need to be answered*

- [ ] How do we run the AWS changes and DynamoDB in local or testing environments?
- [ ] Does it make sense to use AWS RDS with a postgres DB instead of DynamoDB?
- [ ] What's the best way to handle user authentication? AWS Cognito?
- [ ] Is it possible to use Battle.net as an authentication provider?
- [ ] How to setup reviews on PRs, so that people are tagged in a Discord embed/message if they receive a PR for them to review?

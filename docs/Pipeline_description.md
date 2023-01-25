# Pipeline Description

1. Push Commits to GitHub
2. Trigger CircleCI Workflow
3. Install node and checkout code
4. Install dependencies for the frontend app
5. Install dependencies for the backend app
6. Build Front-End app
7. Build API app
8. Wait For Manual Approval on CircleCI
9. Deploy API to Elastic Beanstalk
10. Deploy UI to S3

![Pipleline](./pipeline.png)

# ebs_lab

# ebs_lab

## Overview

This project demonstrates a simple Node.js application deployed on AWS Elastic Beanstalk. The application uses Express.js to create a basic web server that responds with a greeting message.

## Prerequisites

To run this project, ensure you have the following installed:

- Node.js
- AWS CLI
- Elastic Beanstalk CLI

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ebs_lab.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ebs_lab
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

## Running Locally

To run the application locally, use the following command:

```bash
npm start
```

The server will be running at `http://localhost:3000`.

## Deploying to Elastic Beanstalk

1. Initialize your Elastic Beanstalk application:

   ```bash
   eb init
   ```

2. Create an environment and deploy the application:

   ```bash
   eb create
   eb deploy
   ```

3. Open the application in your browser:
   ```bash
   eb open
   ```

## Project Structure

- `index.js`: Entry point of the application, sets up the Express server.
- `package.json`: Contains project metadata and dependencies.

## License

This project is licensed under the ISC License.

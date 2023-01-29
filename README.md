# Serverless NestJS with Serverless PostgreSQL

## Installation

```bash
$ yarn
```

## Running the app

```bash
# watch mode
$ yarn start:dev
```

Note: Before starting the server ,ensure the database connection details is updated in the `.env`

## Deploy to Cloud

1. Configure your AWS credentials using `aws configure` command.
2. `sls deploy`

Note: Ensure you have Serverless Framework installed. If not , you can install it globally using `npm install -g serverless`


## Test Serverless Locally

`sls offline`

# Project
### Team Members

Emmanuel Oh Eu-gene

Liew Xi Wei

Tan Qi En

Tay Rui Xian

Yap Bing Yu

### Description

This is the main repo for CS301-g1-team5 project submission. It contains folders for proposal and final submission, as well as CloudFormation templates for setting up basic AWS networking infrastructure. For further information on deploying each service, refer to the README in the respective repos:

[Batch](https://github.com/cs301-itsa/project-2021-22t1-g1-team5-batch) - Containerized service that runs on a periodic schedule, pulling transaction data from Exavault FTP server and reading individual transactions into SQS (Simple Queue Service)

[Backend](https://github.com/cs301-itsa/project-2021-22t1-g1-team5-backend) - Containerized service that consumes transactions from AWS SQS (Simple Queue Service), processes rules, and saves all records to a database

[Frontend](https://github.com/cs301-itsa/project-2021-22t1-g1-team5-frontend) - UI for for card owners to log in and view their accumulated rewards and campaign benefits

[Lambda](https://github.com/cs301-itsa/project-2021-22t1-g1-team5-lambda) - Lambda functions that retrieve user specific-data from the database for the frontend, and also expose a REST endpoint for transactions to be uploaded as JSON


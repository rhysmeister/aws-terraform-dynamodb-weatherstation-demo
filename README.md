# aws-terraform-dynamodb-weatherstation-demo
A demo for an imaginary Global Weather Station system based on DynamoDB

# Features

* Simple 1 Table System to collect Weather Data from a huge number of stations scattered through-out the Globe.
    * Global Secondary Index
    * Global Local Index
    * Performance can be calculated
        * N stations writing 1 record per X time period
        * Daily Reporting Jobs
* Backup Plan
* Restore Plan
* IAM Access Policy
* Cognito?
# Expert Opinion 
AWS Lambda used to stream events from AWS CloudWatch Logs to Splunk using Splunk's HTTP event collector API.

# Development Stack / Techy
Built using Node.JS 6.10 and AWS Lambda.

# Build
Define the following Environment Variables

 1. **SPLUNK_HEC_URL**: URL address for your Splunk HTTP event collector endpoint. Example: https://host.com:8088/services/collector
 
 2. **SPLUNK_HEC_TOKEN**: Token for your Splunk HTTP event collector.

 Configure Lambda function to be triggered by CloudWatch logs. 
 
# Tests
To be continued.

# Contacts 
andrew.evans@landmark.co.uk (developer), isabel.north@landmark.co.uk (devops)
# Lambda Twilio SMS Sender

## Description

This AWS Lambda function is designed to send SMS messages using Twilio. It's built using [Node.js/Python/etc.] and is deployed via the Serverless Framework. The function sends messages to specified numbers with a predefined message body.

## Setup

### Prerequisites

- AWS CLI installed and configured
- Node.js 18.X
- Serverless Framework installed
- Twilio account with Account SID, Auth Token, and a Twilio Phone Number

## Configure
1. Open serverless.yml.
2. Locate the environment section under the functions block.
3. Fill in your Twilio credentials and phone number:

```bash
   environment:
   TWILIO_ACCOUNT_SID: 'your-twilio-account-sid'
   TWILIO_AUTH_TOKEN: 'your-twilio-auth-token'
   TWILIO_PHONE_NUMBER: 'your-twilio-phone-number'
```
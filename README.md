# AWS-DynamoDB-Create
Script to generate a DynamoDB table

https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html

# Commands to running this NodeJS file after connecting to your AWS EC2 Instance.
# First SSH into instance and elevate privileges to root.

1.) Connect to your Linux instance as ec2-user using SSH.

2.) Install node version manager (nvm) by typing the following at the command line.

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

3.) Activate nvm by typing the following at the command line.

. ~/.nvm/nvm.sh

4.) Use nvm to install the latest version of Node.js by typing the following at the command line.

nvm install node

5.) Test that Node.js is installed and running correctly by typing the following at the command line.

node -e "console.log('Running Node.js ' + process.version)"

6.) You need to install the aws-sdk

npm install aws-sdk

node FILE_NAME

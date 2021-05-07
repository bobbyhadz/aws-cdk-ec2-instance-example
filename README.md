# EC2 Instance Example in AWS CDK - Complete Guide

A repository for an article on
[bobbyhadz.com](https://bobbyhadz.com/blog/aws-cdk-ec2-instance-example)

## How to Use

1. Clone the repository

2. Install the dependencies

```bash
npm install
```

3. create a Key pair with the name of `ec2-key-pair` in your default region

4. Create the CDK stack

```bash
npx cdk deploy
```

5. Open the AWS CloudFormation Console and the stack should be created in your
   default region

6. Copy and paste the public IPv4 url of the EC2 instance in your browser and
   you should see the response from the nginx server

7. Cleanup

```bash
npx cdk destroy
```

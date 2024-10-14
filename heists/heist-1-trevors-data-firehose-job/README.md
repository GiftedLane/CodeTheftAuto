# Heist 1: Trevor's Data Firehose Job

## Mission Name: "Burning Data and Dumping Payloads" 🔥💾

### Mission Briefing

Trevor has cooked up another one of his wild ideas, and this time, it involves "burning" data and dumping payloads into an S3 bucket. In this heist, you’ll help Trevor by setting up an AWS infrastructure that automates the flow of data triggered by events.

Your mission is to create an **EventBridge rule** that triggers a **Kinesis Data Firehose**, which in turn invokes a **Lambda function**. The Lambda will process a simple "Hello World" event, and the Firehose will dump the resulting payload into an **S3 bucket** with a structured prefix.

### Objectives:

- [ ] **EventBridge Rule**: Create a rule that triggers based on a specific event pattern.
- [ ] **Kinesis Data Firehose**: Set up a delivery stream that invokes the Lambda function.
- [ ] **Lambda Function**: Write a "Hello World" Lambda function that processes the event payload.
- [ ] **S3 Bucket**: Store the payload in an S3 bucket using a date-based prefix like `heist-data/YYYY/MM/DD/`.

### Required AWS Services:
- EventBridge
- Kinesis Data Firehose
- Lambda
- S3

### Getting Started:

The configuration files for **Heist 1: Trevor's Data Firehose Job** will be created live during the upcoming stream! 🎮 Join us for the session, where we’ll walk through building the Terraform infrastructure step-by-step.

1. **Tune in to the live stream**: Catch the live stream on [Twitch](https://www.twitch.tv/giftedlane) every Sunday at 9:30 AM EST. We’ll be building and explaining each part of the infrastructure together, live!
   
2. **Follow along**: During the stream, you can code along with us or simply watch and take notes. After the stream, the completed Terraform configuration files will be pushed to this directory for your use.

3. **After the stream**: Once the stream is complete, you’ll be able to clone the updated repository and navigate to the `heist-1-trevors-data-firehose-job/` directory. At that point, you can:

   ```bash
   terraform init
   terraform plan
   terraform apply
   ```
   to deploy the infrastructure that we built together.

4. **Join the discussion**: If you have questions, suggestions, or run into any issues during the stream, feel free to participate in the live chat, or reach out afterward on our [Patreon community](https://www.patreon.com/GIFTEDLANE).

5. **Stay tuned!** 🎉 After the stream, the fully completed configuration files will be available here, so you can revisit the heist at your own pace.

### Important Note:

This README and the configuration files will be updated immediately following the stream to reflect the completed infrastructure for **Heist 1**. Be sure to check back for the final files!

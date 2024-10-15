# Heist 2: Michael's Budget Banditry

## Mission Name: "Keeping the Bank in Check" 💰🔔

### Mission Briefing

In this heist, you’re stepping up your game and tackling a critical part of any AWS operation: **cost management**. It’s time to ensure you're not blindsided by unexpected charges. By setting up **billing alarms**, **budgets**, and **notifications**, you’ll be able to keep your AWS spending in check and avoid any unwanted surprises.

Your mission is to create a fully automated **billing alert system** using Terraform. You’ll set up **CloudWatch billing alarms** to notify you when your charges approach **$10**, and configure **AWS Budgets** to alert you when you're nearing your monthly budget.

### Objectives:

- [ ] **SNS Topic**: Set up an SNS Topic that will send email notifications for billing alerts.
- [ ] **CloudWatch Billing Alarm**: Create a CloudWatch Billing Alarm that triggers when your account’s charges exceed $10.
- [ ] **AWS Budgets**: Configure a budget with alerts when you hit 80% of your monthly spending limit.
- [ ] **Notifications**: Verify that all alerts are sent to your email via SNS.

### Required AWS Services:
- Simple Notification Service (SNS)
- CloudWatch (Billing Alarms)
- AWS Budgets

### Getting Started:

The configuration files for **Heist 2: Michael's Budget Banditry** will be created live during the upcoming stream! 🎮 Join us for the session, where we’ll walk through building the Terraform infrastructure step-by-step to monitor and manage your AWS costs.

1. **Tune in to the live stream**: Catch the live stream on [Twitch](https://www.twitch.tv/giftedlane) every Sunday at 9:30 AM EST. We’ll be building and explaining each part of the infrastructure together, live! (October 27, 2024)

2. **Follow along**: During the stream, you can code along with us or simply watch and take notes. After the stream, the completed Terraform configuration files will be pushed to this directory for your use.

3. **After the stream**: Once the stream is complete, you’ll be able to clone the updated repository and navigate to the `heist-2-michaels-budget-banditry/` directory. At that point, you can:

   ```bash
   terraform init
   terraform plan
   terraform apply
   ```

4. **Join the discussion**: If you have questions, suggestions, or run into any issues during the stream, feel free to participate in the live chat, or reach out afterward on our [Patreon community](https://www.patreon.com/GIFTEDLANE).

5. **Stay tuned!** 🎉 After the stream, the fully completed configuration files will be available here, so you can revisit the heist at your own pace.

---

### Important Note:

This README and the configuration files will be updated immediately following the stream (October 27, 2024) to reflect the completed infrastructure for **Heist 2**. Be sure to check back for the final files!

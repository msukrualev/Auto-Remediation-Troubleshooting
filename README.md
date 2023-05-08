# Auto-Remediation-Troubleshooting

* Introduction
During this lab, we will learn how to implement a simple remediation solution for correcting changes to a production auto scaling group (ASG) within AWS.

* Here is our scenario:

Your company uses a 'multiple environment to a single AWS account' approach for their EC2 deployments. Your DevOps engineering manager has noticed that there have been several outages due to junior engineers accidentally setting the desired capacity of the production ASG to zero (0). She wants to avoid having to manipulate IAM permissions for now and has asked you to put an auto remediation solution in place to auto recover from these mistakes.

![Auto-Remediation Page 01 Snapshot 02](https://user-images.githubusercontent.com/121056799/236736556-9957c590-19a3-4158-8b60-a67e1d3fdee9.png)

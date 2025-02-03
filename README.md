# N8N Free AWS Launcher

<div align="center" style="display: flex; align-items: center;">
  <a href="https://github.com/stefanopochet/n8n_aws_launcher" target="_blank">
    <img alt="N8N AWS Launcher Logo" src="https://github.com/stefanopochet/n8n_aws_launcher/raw/main/logo.webp" width="280" style="height: auto;">
  </a>
</div>

<p align="center">
  <a href="https://github.com/stefanopochet/n8n_aws_launcher/releases">
    <img src="https://img.shields.io/github/v/release/stefanopochet/n8n_aws_launcher" alt="Release Version">
  </a>
  <a href="https://github.com/stefanopochet/n8n_aws_launcher/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/stefanopochet/n8n_aws_launcher" alt="MIT License">
  </a>
  <a href="https://github.com/stefanopochet/n8n_aws_launcher/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="Send PR">
  </a>
</p>

<h1 align="center">
  Launch n8n for Free on AWS
</h1>

<p align="center">
  <br />
  <a href="https://github.com/stefanopochet/n8n_aws_launcher" rel="dofollow">Explore the project on GitHub</a>
<br />

---

## N8N AWS Launcher

The N8N AWS Launcher provides a unique and effortless way to deploy n8n on AWS with just one click, completely free using the AWS Free Tier. This project leverages AWS CloudFormation to automate the setup of an EC2 instance running n8n in a Docker container.

### Features

- **One-Click Deployment**: Launch n8n on AWS with minimal setup.
- **Cost-Effective**: Utilize AWS Free Tier to run n8n at no cost.
- **Automated Setup**: Uses CloudFormation to handle the infrastructure setup.
- **Secure Access**: Configurable security group for HTTP and SSH access.

### Setup Guide

1. **Download the CloudFormation Template**: Save the template file on your computer from [this link](https://raw.githubusercontent.com/stefanopochet/n8n_aws_launcher/refs/heads/main/n8n-cloud-formation-template.yaml).

2. **Access AWS CloudFormation**: Go to [AWS CloudFormation](https://console.aws.amazon.com/cloudformation/home).

3. **Create a New Stack**:
   - Click on "Create stack" and select "With new resources (standard)".
   - Choose "Upload a template file" and select the previously downloaded template file.

4. **Configure Stack Details**:
   - Enter a stack name, e.g., `n8nawslauncher` (or any name you prefer).
   - For **EC2 Instance Type**, select your preferred instance type. `t3.micro` is recommended for AWS Free Tier and should suffice for minimal workflows.

5. **Review and Create**:
   - Leave all options on the next screen empty.
   - Confirm by clicking "Submit".

6. **Deployment**:
   - Wait a few minutes for the server to be instantiated. The events will be automatically updated.
   - After completion, wait an additional 2 minutes for the server to complete its setup.

7. **Access n8n**:
   - Check the "Outputs" tab in the CloudFormation stack.
   - Look for the key `InstancePublicURL`. It will contain a URL like `http://ec2-xx-xx-xx-xx.compute-1.amazonaws.com/`.
   - Click on it, ensuring you use `http`.
   - You should see the n8n welcome page. Hooray!

### Contributing

We welcome contributions! Please feel free to submit a pull request or open an issue on [GitHub](https://github.com/stefanopochet/n8n_aws_launcher).

### License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/stefanopochet/n8n_aws_launcher/blob/main/LICENSE) file for details.

---

For more information, visit the [n8n documentation](https://docs.n8n.io/).

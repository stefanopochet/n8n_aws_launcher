# N8N Free AWS Launcher

<div align="center" style="display: flex; align-items: center;">
  <a href="https://github.com/stefanopochet/n8n_aws_launcher" target="_blank">
    <img alt="N8N AWS Launcher Logo" src="https://github.com/stefanopochet/n8n_aws_launcher/raw/main/logo.png" width="280" style="height: auto;">
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

## N8N AWS Launcher (Free in 1 Click)

The N8N AWS Launcher provides a unique and effortless way to deploy n8n on AWS with just one click, completely free using the AWS Free Tier. This project leverages AWS CloudFormation to automate the setup of an EC2 instance running n8n in a Docker container.

### Features

- **One-Click Deployment**: Launch n8n on AWS with minimal setup.
- **Cost-Effective**: Utilize AWS Free Tier to run n8n at no cost.
- **Automated Setup**: Uses CloudFormation to handle the infrastructure setup.
- **Secure Access**: Configurable security group for HTTP and SSH access.

### Getting Started

1. **Prerequisites**: Ensure you have an AWS account and access to the AWS Management Console.
2. **Deployment**: Use the provided CloudFormation template to create a stack in your AWS account.
3. **Access**: Once deployed, access your n8n instance via the public DNS provided in the CloudFormation outputs.

### Usage

- **Configuration**: Customize the instance type and key pair name in the CloudFormation template as needed.
- **Security**: Modify the security group settings to restrict access to specific IPs for enhanced security.

### Contributing

We welcome contributions! Please feel free to submit a pull request or open an issue on [GitHub](https://github.com/stefanopochet/n8n_aws_launcher).

### License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/stefanopochet/n8n_aws_launcher/blob/main/LICENSE) file for details.

---

For more information, visit the [n8n documentation](https://docs.n8n.io/).

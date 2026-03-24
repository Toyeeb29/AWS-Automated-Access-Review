# AWS-Automated-Access-Review
## A comprehensive tool for automating AWS IAM security reviews. This project provides security professionals and GRC teams with automated access auditing capabilities to enhance cloud security posture and support compliance requirements
## About
AWS Access Review is a comprehensive, zero-configuration security assessment tool that automatically evaluates your AWS environment for potential security risks and compliance gaps. Built for security professionals and GRC teams, it combines findings from multiple AWS security services into a clear, actionable report with AI-powered analysis.

Unlike complex security dashboards that require constant monitoring, AWS Access Review delivers insights directly to stakeholders' inboxes on a scheduled basis. The tool focuses on identifying IAM misconfigurations, overly permissive permissions, missing security controls, and external access risks—the most common sources of cloud security incidents.

With single-click deployment and integration with native AWS services, you can start receiving detailed security reports in minutes without extensive setup or third-party dependencies.

## Prerequisites
AWS CLI installed and configured with appropriate permissions
Python 3.11 or higher
An AWS account with the following services enabled:
AWS Security Hub
IAM Access Analyzer
Amazon SES (with verified email for receiving reports)
Amazon Bedrock (with access to Claude model)

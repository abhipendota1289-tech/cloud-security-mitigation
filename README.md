# cloud-security-mitigation


## Overview
This project demonstrates how to identify and mitigate a cloud security misconfiguration in AWS by securing a publicly accessible EC2 instance.

## Problem Statement
The EC2 instance was exposed to the public internet via open inbound rules, increasing the attack surface and risk of unauthorized access.

## Security Risks Identified
- Public HTTP access from anywhere
- No monitoring or role-based access control initially

## Mitigation Steps
- Restricted inbound traffic using Security Groups
- Applied least-privilege IAM role to EC2
- Enabled basic monitoring using CloudWatch

## Tools & Services Used
- AWS EC2
- AWS Security Groups
- AWS IAM
- AWS CloudWatch

## Outcome
The attack surface was reduced, access was controlled, and the EC2 instance followed cloud security best practices.


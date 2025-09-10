# AWS IAM User & Group Management Guide

A comprehensive, step-by-step guide for creating, managing, and organizing AWS IAM users and groups to ensure secure and efficient access management in AWS environments.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Step-by-Step Guide](#step-by-step-guide)
- [Connect with Me](#connect-with-me)

---

## Overview

This repository enables cloud administrators to efficiently set up AWS IAM configurations by guiding you through:

- Creating multiple IAM users with custom console credentials
- Organizing users into groups (e.g., Developers, ReadOnly, FullAccess)
- Attaching AWS managed policies for role-based access control
- Merging group policies and managing permissions for scalable security

---

## Features

- **User Creation:** Onboard users with custom passwords and enabled console access.
- **Group Management:** Create user groups based on roles and job functions.
- **Policy Attachment:** Assign AWS managed policies to groups for streamlined permission management.
- **Credential Management:** Download user credentials and configure sign-in URLs for ease of access.

---

## Step-by-Step Guide

### 1. Sign in to AWS Management Console

- Go to https://aws.amazon.com and sign in using your root or admin account.

### 2. Create IAM Users

- Navigate to **IAM** service.
- Click **Users** on the left navigation panel.
- Click **Add users**.
- Enter the user name (e.g., `User_1`).
- Select **Provide user access to the AWS Management Console**.
- Choose **Custom password** and set the password.
- **Uncheck** “User must create a new password at next sign-in” to avoid forced resets.
- Click **Next**.

### 3. Set User Permissions

- Add the user to an existing group (recommended) or attach policies directly.
- Use groups to manage permissions by job function.
- Review permissions and create the user.
- Download the `.csv` file containing sign-in information or save sign-in URL and password.

### 4. Create IAM User Groups

- In IAM, click **User groups**.
- Click **Create group**.
- Enter group name, for example:
  - **Developers**: Attach `AdministratorAccess` policy.
  - **ReadOnly**: Attach `AmazonEC2ReadOnlyAccess` policy.
  - **FullAccess**: Attach `AmazonS3FullAccess` policy.
- Add respective users to each group.
- Review and create the group.

### 5. Manage Group Policies

- To add or update policies on groups:
  - Open the group in IAM.
  - Click **Permissions > Attach policies**.
  - Search and attach relevant AWS managed policies.
  - Add or remove users as needed under the **Users** tab.

### 6. Repeat as Needed

- Repeat steps 2-5 to create additional users and groups depending on your organizational needs.



---


## Connect with Me

<p align="center">
  <a href="https://github.com/ShaikhAteeb02">
    <img src="https://img.shields.io/badge/GitHub-ShaikhAteeb02-informational?style=flat-square&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/ateeb-ahmed-shaikh-932234192">
    <img src="https://img.shields.io/badge/LinkedIn-ShaikhAteeb-blue?style=flat-square&logo=linkedin" alt="LinkedIn"/>
  </a>
</p>

---

*Empower your AWS organization with secure, scalable IAM management!*


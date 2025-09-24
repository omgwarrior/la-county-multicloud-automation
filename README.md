# LA County - Multi-Cloud Automation Framework

This repository contains a standardized Ansible framework for provisioning and managing resources across a hybrid-cloud environment, including VMWare, AWS, Azure, and GCP.

## 🚀 Purpose

The goal of this framework is to provide a single source of truth for infrastructure deployment, ensuring consistency, reducing manual errors, and enabling rapid provisioning through Infrastructure as Code (IaC).

## ✅ Prerequisites

1.  **Ansible:** Ensure Ansible is installed (`pip install ansible`).
2.  **Cloud SDKs/Libraries:**
    * AWS: `boto3` and `botocore` (`pip install boto3 botocore`)
    * VMWare: `PyVmomi` (`pip install PyVmomi`)
3.  **Cloud Credentials:** Ensure your AWS (`~/.aws/credentials`) and other cloud provider credentials are configured correctly.

## ⚙️ Setup

Clone the repository and install the required Ansible collections:

```bash
git clone [https://github.com/omgwarrior/la-county-multicloud-automation.git](https://github.com/omgwarrior/la-county-multicloud-automation.git)
cd la-county-multicloud-automation
ansible-galaxy collection install -r requirements.yml

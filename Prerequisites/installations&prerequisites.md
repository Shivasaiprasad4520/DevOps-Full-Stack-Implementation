# **AWS Account Creation Guide for Beginners**

## **Introduction**
Creating an AWS account is the first step toward learning cloud computing. This guide will walk you through the process and highlight common challenges beginners may face.

---

## **Step-by-Step AWS Account Creation**

### **Step 1: Visit the AWS Sign-Up Page**
- Go to [AWS Sign-Up](https://aws.amazon.com/)
- Click on **Create an AWS Account**

### **Step 2: Enter Your Email & Account Details**
- Provide a valid email address
- Choose a **Root user** name (preferably your full name or business name)
- Set a strong password
- Click **Continue**

### **Step 3: Contact Information**
- Choose **Personal** or **Business** account type
- Fill in your **full name, phone number, and address**
- Click **Continue**

### **Step 4: Payment Information**
- Enter a valid credit or debit card (AWS requires this for identity verification)
- AWS may place a small temporary charge for verification
- Click **Continue**

### **Step 5: Identity Verification**
- Enter the **OTP** received via SMS or a phone call
- Complete the CAPTCHA verification
- Click **Verify**

### **Step 6: Choose a Support Plan**
- Select **Basic (Free)** unless you need premium support
- Click **Continue**

### **Step 7: Access Your AWS Console**
- Once verified, go to the [AWS Console](https://aws.amazon.com/console/)
- Log in using your email and password
- Explore AWS services!

---
# **AWS IAM User Creation Guide for Beginners**

## **Step-by-Step IAM User Creation**

### **Step 1: Log in to AWS Console**
- Go to [AWS Management Console](https://aws.amazon.com/console/)
- Sign in with your **Root Account**
- Navigate to **IAM Dashboard**

### **Step 2: Open IAM Users Section**
- Click on **Users** in the left navigation pane
- Click **Add User**

### **Step 3: Enter User Details**
- Provide a **User Name** (e.g., `devops-user`)
- Select **AWS Credential Type**:
  - **Access Key – Programmatic Access** (for CLI, SDKs, API access)
  - **Password – AWS Management Console Access** (for GUI access)
- Click **Next**

### **Step 4: Assign Permissions**
- Choose how to set permissions:
  - **Attach Existing Policies Directly** (e.g., `AdministratorAccess`, `PowerUserAccess`, `ReadOnlyAccess`)
  - **Add to a Group** (recommended for better management)
  - **Copy from Another User**
- Click **Next**

### **Step 5: Add Tags (Optional)**
- Assign metadata like `Department: DevOps`, `Project: E-Commerce`
- Click **Next**

### **Step 6: Review and Create User**
- Review all details carefully
- Click **Create User**

### **Step 7: Download Credentials**
- Download the **Access Key ID & Secret Access Key** (if programmatic access is enabled)
- Save these credentials securely (they won’t be shown again)
- Click **Close**
---


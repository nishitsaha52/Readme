# Jenkins Script Execution Guide

## Overview
This document provides step-by-step instructions for running scripts (such as cloning or deleting) in Jenkins using the **Script Console**.

---

## Steps to Run the Scripts

### Step 1: Access the Jenkins Script Console
1. Log in to your Jenkins dashboard.  
2. Click on the **Notification Button**.  
3. Navigate to **Manage Jenkins**.  
4. Select **Script Console** from the options.  
   - Alternatively, access the Script Console directly via the URL below:  
     👉 https://qapipeline.tcgdigital.com/jenkins/manage/script

---

### Step 2: Paste and Modify the Script
1. Copy the required script — either **cloning** or **deleting**.  
2. Paste it into the Script Console text area.  
3. Update the required **data points or parameters** (e.g., job name, repository name, branch, etc.) as per your requirements.

---

### Step 3: Run the Script
1. Review the script to ensure all details are correct.  
2. Click on the **Run** button.  
3. Monitor the output in the console to verify successful execution.  
4. If any errors occur, check the logs and correct the data points or syntax before rerunning.

---

## Important Notes
- Ensure you have **administrator privileges** before running scripts in the Jenkins Script Console.  
- Exercise caution while running **deletion scripts** — deleted Jenkins jobs or configurations cannot be recovered.  
- Always **review and validate** scripts prior to execution to avoid unintended changes.  
- Prefer running scripts first in a **staging or QA Jenkins environment** before applying to production.

---

## Example Use Cases
- **Cloning Script:** Duplicate an existing Jenkins job or pipeline configuration.  
- **Deleting Script:** Remove outdated or unused Jenkins jobs or pipelines.  

---

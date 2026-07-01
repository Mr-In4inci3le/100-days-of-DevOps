## Task

To accommodate the backup agent tool's specifications, the system admin team at xFusionCorp Industries requires the creation of a user with a non-interactive shell. Here's your task:



Create a user named jim with a non-interactive shell on App Server 3.

Note: You can find the infrastructure details by clicking on the Details of all Users and Servers button on the top-right section of the page.

<img width="1920" height="3095" alt="image" src="https://github.com/user-attachments/assets/4c576a66-db95-4ab5-9c72-ad035ed599b0" />

## Solution:

Step 1: Log in to app server 3 via SSH
Step 2: add the command `sudo useradd -s /sbin/nologin jim`
Step 3: Use the password for the banner when it prompts
Step 4: verify it `grep '^jim:' /etc/passwd` or simply you can check `/etc/passwd`

<img width="957" height="567" alt="image" src="https://github.com/user-attachments/assets/d4d2cfde-c090-4870-ad5a-010b0d9c0ba9" />

<img width="890" height="640" alt="image" src="https://github.com/user-attachments/assets/09b64554-916e-4550-9f36-de3d02ba8881" />


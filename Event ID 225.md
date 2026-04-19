# SOC257 - VPN Connection Detected from Unauthorized Country

Step 1: Review given info from the alert.
<img width="1605" height="536" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/98c5bce5-61fa-47ab-8889-283ac51fa4d8" />

Step 2: investigate Monicas email traffic. 

<img width="1910" height="764" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/ae8f7c41-59cd-4363-9e3c-99506edac0ea" />
Here we can see 3 emails for one time passwords requests initiated my Multi-Factor Authentication from a Vpn URL located in Hanoi, Ha Noi.

Step 3: After investigating in log managment using the given source address to filter the logs we can see that there are three incorrect OTP notifications.


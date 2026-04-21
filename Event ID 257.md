# Event ID 257 SOC282 - Phishing Alert - Deceptive Mail Detected

Step 1: View given information about the alert 
<img width="1131" height="299" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/d4c0da32-9b02-4aa3-9de6-a61e5a243dc0" />
Here we can see that the source address "free@coffeeshooop.com" is suspicious because of the odd spelling.

Step 2: Use virustotal to see if the source address is a known malicous address
<img width="1884" height="825" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/6592be59-496e-4895-b61e-887ac58c16d4" />
Here we can see that it is listed as malicous by 10 different vendors

Step 3: Look through Email Security to see if the email included a link or package
<img width="1890" height="868" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/ea76db7a-0873-4110-b572-6fe4641672b4" />
The email does include a click. When hovering over the link it shows a very long url that is suspicous


Step 4: We need to check Log Management to see if the link was clicked and allowed
<img width="1575" height="684" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/66d9b67d-095c-4017-a8ba-5ea0c573b62e" />
We see a long that shows the same URL from the link in the email being run and allowed.

Step 5: We need to contain Felix's device from the network and create a case for the alert




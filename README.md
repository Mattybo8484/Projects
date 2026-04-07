
# Alert Investigations 


## EventID 304 	SOC326 - Impersonating Domain MX Record Change Detected

Step 1: View trigger reason and given information.
<img width="1632" height="512" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/557e3e2b-eef1-429e-9762-b5a1f4ce706d" />

Step 2: Investigate the emails for potential security issues and check for any related phishing activity after the alert creation date.

<img width="1748" height="712" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/cfee12fd-c9aa-4070-a20b-eb3a8889b9ad" />
Found an email from a source that appears to be trusted giving a link for Mateo@letdefend.io to click in order to recieve a voucher. Link is supicious as it is slightly misspelled.

Step 3: Run the link through virus total to see if it is marked as malicious by any vendors.

<img width="1900" height="963" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/b65ab8eb-09d2-4b77-9eb9-b946faec7da5" />
Here we can see that the link is not listed as a known malicious source but sense this is an alert for impersonating a Domain MX Record change we have to assure that the sender is who they say they are. So next 
we run the IP address of the sender through Virustotal.
<img width="1903" height="934" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/85e6a970-5a5a-4982-9518-47b38de89740" />
Here we can see that the IP address is marked as malicious.

Step 4: Delete the email

Step 5: Check EndPoint Security to see if Mateo clicked the link.

<img width="1174" height="623" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/33f79638-8eba-4943-995a-99e96679446d" />

Here we can see that the link was run and it was the last event in his browser history.

Step 6: Contain Mateos device from the network.
<img width="1550" height="811" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/e473df08-dcbd-4c14-b082-fa03bbc4cc00" />





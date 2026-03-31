
# Alert Investigations 


## EventID 304 	SOC326 - Impersonating Domain MX Record Change Detected

Step 1: View trigger reason and given information.
<img width="1632" height="512" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/557e3e2b-eef1-429e-9762-b5a1f4ce706d" />

Step 2: Investigate the emails for potential security issues and check for any related phishing activity after the alert creation date.

<img width="1748" height="712" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/cfee12fd-c9aa-4070-a20b-eb3a8889b9ad" />
Found an email from a source that appears to be trusted giving a  link for Mateo@letdefend.io to click in order to recieve a voucher. Link is supicious as it is slightly misspelled.

Step 3: Check EndPoint Security to see if Mateo clicked the link.

<img width="1174" height="623" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/33f79638-8eba-4943-995a-99e96679446d" />

Here we can see that the link was run and it was the last event in his browser history.

Step 4: Check to see if there is any suspicous activity after mateo clicked the link.

<img width="1216" height="689" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/41661195-a3cd-4bc8-a6ca-90503f72d4c4" />

Found many suspicous events running system32 commands with long strings.


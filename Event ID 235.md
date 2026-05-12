
## 		SOC127 - SQL Injection Detected

## View given information
<img width="1542" height="467" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/0c159b17-05db-4b8d-923f-6413ab402791" />

## Check validadity of alert
We need to check logs to see if this alert is a true positive and if there is really an attack attempt
<img width="1396" height="364" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/c857928a-a19d-4346-aa9d-7a26a88582c5" />
Here we see that the raw data show an input with "--" which is a commonly used in SQL injection attacks because SQL systems will ignore everything after "--". This increases the threat

<img width="884" height="959" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/ad882d59-4a8b-4e5b-90c5-355c785f3916" />
After using Whois we found that the source address is external and from Beijing CNISP Technology Co., Ltd.

<img width="1893" height="845" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/d372950e-9635-4585-8d8f-b9430d0fea3b" />
After putting the source IP address through VirusTotal it is listed as malicious by 10 different vendors

## Escalate alert
With the information found we should escalate the alert as this is a true positive.

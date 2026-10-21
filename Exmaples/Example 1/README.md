# Phishing Investigation
## Information
Email: 🔔 Action Required_ Storage 100% Full  

User Affected: dessyboi23@gmail.com  

From: dessyboi23<alert-5779@jlgcd.ukl> sent via sb035.securebackendbase.my.id  

Received: from efianalytics.com(132.148.22.170, 216.244.76.116)  

Reply to: me@aol.com  

Link: https://storage.googleapis[.]com/obsidianly/obsidianly.html?act=un&pid=14829_md&uid=2&vid=578858&ofid=335&lid=433&cid=1125061  


# Report
The user dessy with the email dessyboi23@gmail received an email with an from address sent via sb035.securebackendbase.my.id API. 
The email states the user's cloud storage has reached 100% capacity and the payment for the renewal of the the storage has expired and the email is asking for the user to update their payment information to avoid service disruption.  

Looking over the original message for the email to see the original source of the email and see the specific email authentication methods the email went through and see the result.
Firstly the From info of the email copies the email of the user and adds an alert to act like the email is a high priority email and make the user trust the email.
Looking at the domain the email was received from the two IP's associated with it 132.148.22.170 and 216.244.76.116 was reported to abuseIPDB for being used for email spam, spoofing and hacking.  

### SPF
The SPF for the email passed as the domain for the API 433-1125061@sb035.securebackendbase.my.id ( which is a low level domain based of indonesia) designated that the IP 5.135.245.28 was authorized to send for that domain.  

### DKIM
Looking at the DKIM for the email from the domain jn2r.sb035.securebackendbase.my.id it looks the DKIM is valid but there was an error and the dkim had a permerror
which caused it to fail.  

### DMARC
The DMARC record is not present in this email.  


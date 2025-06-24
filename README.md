# elevate-labs-task-2
Most of the phishing attacks are done through E-MAILS only 
The attacker will trick the  end user by sending an e-mail so that he will gain unauthorized access or sensitive data
Phishing e-mail attacks can be made in any way whether it’s a malware virus or worm attack.

MAIN MOTIVE OF THE ATTACKER 
The main motive of the attacker behind phishing is to gain confidential information like:
Password
Credit card details
Social security numbers
Date of birth
The attacker uses this information to further target the user impersonate the user and cause data theft.

VISUAL ANALYSIS: If we can clearly observe we can find the easy mistakes like 
Spellings 
Lottery e-mails
Gift cards
Vouchers
Job opportunities
Fake birthday wishes
Low-resolution images
Fake logos 

TOOLS USED: MxToolbox, mha.azurewebsites

To determine whether an email is a phishing attempt or a legitimate message, we can use tools like MxToolbox and mha.azurewebsites to analyze the email header. 
When you receive an email, you can copy the email header and paste it into MxToolbox. This tool provides information such as the IP address and other details, helping to identify if it is a phishing email and outlining the destination path.
Once we obtain the IP address using MxToolbox, we can check whether the associated domain is whitelisted or blacklisted by pasting the IP address into the same tool.
If we examine the email closely (refer to FIG-1), we may find a URL that contains misspellings of the domain name. This is a clear indication that the email is a phishing attempt.

# Alert Types 

1. ***Unusual Login Failure :***
  - Mostly occured due to  NTLM Services and Microsoft Authentication or user entering wrong password
  - Event type : Host Login Failure 
  - Failure Reason : Unknown user name or password
  - Mostly detected by Host
  - Output : Mostly Treated as False Positive
  - Mostly found in all the clients due to NTLM Services

2. ***Suspious Login :***
  - Event type : Host Login Failure
  - Failure Reason: Account currently disabled 
  - mostly detected by Host

3. ***Potential Zero Day Malware :***
  - occured due to Wifi network or port scanning
  - Event type: New Connection To An Application On A Host
  - Failure Reason : New Connection Establishment
  - Mostly detected by Network and ML

4. ***Potential Malware Infected Host :*** 
  - Event type : Unusual Connection Duration To An Application On A Host
  - Failure Reason : Unusual connection duration detected from ... to ... on port ..
  - Mostly detected by Network and ML


5. ***Policy Violation :***
  - occured mostly due to connectivity to other countries which are mostly blacklisted
  - Event  type : Prohibited Country Access
  - Failure Reason : Prohibited country access by host .....
  - Mostly deteced by Network
  - Output : Mostly whitelisted such alerts

6. ***UDA - Protocol Recon :***
  - occured mostly because of firewall denied all the traffic or Test Policy port 3128
  - Mostly False Positive Alert 
  - Event type : Protocol Recon
  - Mostly detected by Network
  - Output : Mostly Treated as False Positive

7. ***Potential Data Exfiltration :***
  - Occured mostly because of suspicious data upload  
  - Event Type : Data Upload
  - Failure Reason : Suspicious data upload from .... to ....


8. ***Brute Force Attack :***
  - 
  - Event Type: Database Admin Login Failure or Network Login Failure
  - Failure Reason : failed in authentication or User login denied due to bad credentials

9. ***Potential Ransomware :***
  -
  - Event Type : Suspicious Process
  - Failure Reason : New process has been created for .exe which can be suspicious as a ransomware malware

10. ***Potential Vulnerability Exploit :***


 

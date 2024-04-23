# Phishing Analysis - Manual Artifact Extraction

## Objective
The Blue Team Level 1 Certification Course work provides practical cybersecurity skills. This guided project utilizes a virtual machine environment and simulated emails to familiarize cybersecurity professionals with manually extracting artifacts for phishing analysis.

### Skills Learned
-Email signature analysis
<p>--Sender and recipient addresses</p>
<p>--Sender Server IP address</p>
<p>--Attachment Hashes</p>
<p>-Examine email coding via Sublime 3 Text Editor</p>
<p>-PowerShell reserves DNS lookup on IP addresses</p>
<p>-PowerShell commands</p>
<p>--Reserve DNS lookup (nslookup...)</p>
<p>--display file hashes (get-filehash .\...)</p>



### Tools Used
-Laptop
<p>-Blue Team Level 1 Certification Course</p>
<p>-Thunderbird Mailing Service</p>
<p>-Sublime 3 Text Editor</p>
<p>-PowerShell</p>

### Steps
<img src="https://i.imgur.com/O7pjwk3.jpg" style="width: 85%;" alt="1">
<p><i>Ref 1: Sender server IP address found</i></p>

<img src="https://i.imgur.com/r0gPtjO.jpg" style="width: 85%;" alt="1">
<p><i>Ref 2: Reserve DNS lookup using PowerShell. Domain is highlight in red</i></p>

<img src="https://i.imgur.com/xdIPzVz.jpg" style="width: 85%;" alt="1">
<p><i>Ref 3: Sample email attachment hashes displayed using PowerShell. Note nested commands. Default "get-filehash" command displays SHA256 hash values</i></p>

# Phishing Analysis

## Objective
The Blue Team Level 1 Certification Course work provides practical cybersecurity skills. This guided project utilizes a virtual machine environment, sample emails, and a sample credential harvester to familiarize cybersecurity professionals with phishing analysis.

### Skills Learned
-Conduct email manual artifact extraction
<p>--Sender and recipient addresses</p>
<p>--Sender Server IP address</p>
<p>-Examine email attachment hashes</p>
<p>-Examine email coding using Sublime 3 Text Editor</p>
<p>-PowerShell reverse DNS lookup on IP addresses</p>
<p>-PowerShell commands</p>
<p>--Reserve DNS lookup (nslookup...)</p>
<p>--display file hashes (get-filehash .\...)</p>
<p>-Examine credential harvester using Chrome Developer Tool</p>
  
### Tools Used
-Laptop
<p>-Blue Team Level 1 Certification Course</p>
<p>-Thunderbird Mailing Service</p>
<p>-Sublime 3 Text Editor</p>
<p>-PowerShell CLI</p>
<p>-Chrome Developer Tool</p>

### Steps
<img src="https://i.imgur.com/O7pjwk3.jpg" style="width: 85%;" alt="1">
<p><i>Ref 1: Sender server IP address found</i></p>

<img src="https://i.imgur.com/r0gPtjO.jpg" style="width: 85%;" alt="1">
<p><i>Ref 2: Reverse DNS lookup using PowerShell. Domain is highlight in red</i></p>

<img src="https://i.imgur.com/xdIPzVz.jpg" style="width: 85%;" alt="1">
<p><i>Ref 3: Sample email attachment hashes displayed using PowerShell. Note nested commands. Default "get-filehash" command displays SHA256 hash values, "-algorithm..." will display specific hashes</i></p>
File hashes may reveal potential malware 'out in the wild'. Once discovered during forensics work, a cross reference made on malware repositories (virustotal.com) may return a malware profile.

<img src="https://i.imgur.com/nwqx8A0.jpg" style="width: 85%;" alt="1">
<p><i>Ref 4: Sample credential harvester supposedly hyperlinked from a phishing email, test input, and Chrome Developer Tool displaying hyperlink to collecting web server </i></p>

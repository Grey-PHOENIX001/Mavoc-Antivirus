<div align="center">
  <img width="160px" src="images/mavoc_antivirus_logo.png" />
  <h1>Mavoc Antivirus</h1>

  <br>

  <p><i> An opensource antivirus tool that scans system files and removes malware , Torjans , payloads, botnets, Ransomeweres ..etc 
  <br>Created in QT and python by<a href="https://twitter.com/Smukx07"> @Smukx</a> .</i></p>
  <br />
  <img src="images/mavoc_quickscan.png" width=70%/>
  <img src="images/quick-scan-result.png" width=70%/>
</div>

> ":warning: The tool is in its early developmental stage. The Heuristic method is still under development. It will come with a new feature in the next update.


## Working Methodology

<div align="center">
  
  <img src="images/Core.png" width=70% /><br/>
  Flowchart for working methodology
  <br>
  </div>
 
**Scans files using Hashing algorithm such as sha256 and md5 hashes .**

**Uses Heuristic Method to Scan 1st Set of Lines .**
  
**Scans files using malicious extensions over 900+ popular malicious extensions .**

**Network Protection Restricts Malicious websites over 42 Thousand websites .**

Note : FOR SCHEDULE SCAN . RUN mavoc.py to Start the Antivirus with Schedule Scan . 

## Types of Scans

**There are 6 Types of Scans** 

- Quick Scan
- Schedule Scan 
- Full Scan
- Network Blocker
- Cloud Firm Scan
- Clean System


<details>
  <summary><b>Quick Scan</b></summary>
  <p><b>There are 2 types of Scans, Quick Recursive and Non-Recursive Scan.</b></p>
  <p>Quick Non-Recursive scan will simply look for common places where malware, payloads, etc., may be stored.</p>
  <p>Quick Recursive Scan will scan all files recursively in the common path, even inside temporary files and folders within the common directory path.</p>
</details>

<details>
  <summary><b>Schedule Scan</b></summary>
  <p>To initiate a Schedule Scan with Mavoc Antivirus, you need to start the Mavoc Antivirus application mavoc.ps1 instead of staring the mavoc.py .</p>
  <p>Schedule Scan will scan and completely removes malicious files on common path every 1 minute by default, but you can adjust the timing in the mavoc.ps1 script.</p>
</details>

<details>
  <summary><b>Full Scan</b></summary>
  <p><b>There are Two Types of Scans: Full Scan and Partition Scan.</b></p>
  <p>Full Scan will comprehensively scan your entire system, which may take hours, so please be patient when using this option.</p>
  <p>Partition Scan allows you to select a particular partition or folder to scan files recursively, making it the fastest scanning method.</p>
</details>

<details>
  <summary><b>Network Blocker</b></summary>
  <p>Network Blocker contains a list of more than 42,000 malicious sites. When enabled, it blocks access to these sites. You can reset it to the default settings by choosing to disable network blocker.</p>
</details>

<details>
  <summary><b>Cloud Firm Scan</b></summary>
  <p>This scan utilizes the VIRUS TOTAL API to scan a specific file.</p>
  <p>Important Note: If you are using the free VIRUS TOTAL API, limit your scans to a minimum of 3 files per minute.</p>
</details>

<details>
  <summary><b>Clean System</b></summary>
  <p>Clean System is used to remove unwanted files from common directory paths, such as temporary and registry paths. It automatically deletes these files to optimize system performance and enhance security.</p>
</details>


#### Customization

<details>
  <summary><b>Setting up HASH for Scanning</b></summary>
  <br>
  <p>I have Collected Popular Databases from various popular sources in Dark Web, VX-Undergrond Group etc .. </p>
  <p>At this date over 700 K Popular SHA256 and MD5 Hashes of virus database has been added. </p>
  <p>I Have an Two Files , the fast_md5 and fast_sha256 hashes has been added in the hashes folder. By Default 350K Popular hashes has been added </p>
</details>

<details>
  <br>
  <summary><b>Setting Path for Quick Scanning</b></summary> 
  <p>On Line 1828 or Search `DIRECTORY PATH FOR QUICK SCAN` on the mavoc.py. you can add your own directory for scanning .</p>
</details>

<details>
  <summary><b>Custom BlackList Configuration</b></summary>
  <p>You can custom your own black list program to block sites 
By default it has over 42000 Malicious and scamming sites.</p>
</details>

Uploading ... 

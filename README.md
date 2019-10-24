# Project 7 - WordPress Pentesting

Time spent: **8** hours spent in total

> Objective: Find, analyze, recreate, and document different vulnurabilities affecting an older versions of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID: User Enumeration
  - [ ] Summary: Created a new user and checked while logging in
    - Vulnerability types:User enumeration
    - Tested in version: 4.2
     
  - [ ] GIF Walkthrough: yes 
  - [ ] Steps to recreate: Created a new user and checked while logging in
  <img src="https://github.com/mrsuman2002/Software-Secure-Engineering/blob/master/WP%204.2%20%20Username%20emumeration.gif">



2. (Required) Vulnerability Name or ID: Cross site scripting by Image upload
  - [ ] Summary: checked by uploading image with malicious filename
    - Vulnerability types:Cross site scripting
    - Tested in version: 4.2
    
  - [ ] GIF Walkthrough:yes
  - [ ] Steps to recreate: XSS on wordpress website
<img src="https://github.com/mrsuman2002/Software-Secure-Engineering/blob/master/WP%204.2%20%20XSS%20on%20a%20WordPress%20site.gif">

3. (Required) Vulnerability Name or ID XSS to upload larger media than 2 mb
  - [ ] Summary: Uploaded music file with malicious description.
    - Vulnerability types: cross- site scripting
    - Tested in version:4.7.4
     
  - [ ] GIF Walkthrough: yes
  - [ ] Steps to recreate: Uploaded music file on wordpress site with malicious music file.
   
   <img src='WP 4.7.4 Large File Upload Error XSS.gif' title='WordPress XSS2' width='' alt='' />
   

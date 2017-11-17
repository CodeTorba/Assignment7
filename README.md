# Assignment7  WordPress Pentesting

Time spent: **6** hours spent in total

> Objective: Find, analyze, recreate, and document **three vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. Unauthenticated Stored Cross-Site Scripting 7945
    - [ ] Summary: An unauthenticated attacker can inject javascipt in WordPress comments.
    - Vulnerability types: XSS
    - Tested in version:4.2
    - Fixed in version: 4.2.1
  - [ ] Affected source code:The MYSQL TEXT type size limit is 64 KB so if the commemt is larger it will be  truncated
    - [Link 1](https://klikki.fi/adv/wordpress2.html)
1.  Authenticated Stored Cross-Site Scripting
  - [ ] Summary: A stored XSS vulnerability in WordPress allows an user with the psoting capability to compromise the website 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.2
  - [ ] Affected source code: The malicious script is executed when an administratir views the page.
    - [Link 1](https://klikki.fi/adv/wordpress3.html)
1. (Required) Nav Menu Title Cross-Site Scripting  8132
  - [ ] Summary: The nav menu title is subjected to being compromised and crashing the site.
    - Vulnerability types:XSS
    - Tested in version:4.2
    - Fixed in version: 4.2.4
  - [ ] Affected source code: nav menu title
    - [Link 1](https://core.trac.wordpress.org/changeset/33541)

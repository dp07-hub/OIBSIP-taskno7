# Nikto Vulnerability Scan Report

## Target:
http://testphp.vulnweb.com

## Description:
A Nikto scan was performed on a vulnerable web application hosted by Acunetix for testing purposes.

## Findings:
- Outdated Apache version detected.
- Directory indexing enabled on /admin/.
- HTTP TRACE method allowed.
- Found default login page.
- Potential XSS vulnerability in search parameter.

## Recommendations:
- Disable TRACE method and directory listing.
- Sanitize user input to prevent XSS.
- Hide sensitive directories and admin panels.
- Regularly update web server software.

## Tool Used:
Nikto v2.1.5 (Kali Linux)
# OIBSIP-taskno7

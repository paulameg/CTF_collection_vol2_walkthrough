# CTF_collection_vol2_walkthrough
Technical write-up and solutions for the TryHackMe "CTF Collection Vol. 2". This repository documents the exploitation of various vulnerabilities, including XOR cryptography, Base64 data URI decoding, HTTP header manipulation with Burp Suite, and POST method exploitation. Features Python and Bash automation scripts for efficient flag capture.


# TryHackMe: CTF Collection Vol. 2 - Write-up & Solutions

This repository contains technical documentation and step-by-step solutions for the "CTF Collection Vol. 2" room on TryHackMe. The project demonstrates the application of offensive security techniques, cryptography, and web application analysis in a controlled environment.

## 🛠️ Tools & Technologies

* **OS:** Kali Linux
* **Web Analysis:** Burp Suite (Intercept, Repeater), Browser DevTools
* **Automation:** Python, Bash, Curl
* **Cryptography:** CyberChef, XOR Analysis, Base64, Hex/Binary decoding
* **Reconnaissance:** Gobuster, Robots.txt analysis

## 🎯 Key Learning Outcomes

This CTF covered a wide range of vulnerability categories and exploitation techniques:

* **HTTP Manipulation:** Utilized Burp Suite to inject custom request headers (`egg:Yes`) and manipulated HTTP methods (switching from `GET` to `POST` to submit credentials).
* **Applied Cryptography:** Deciphered XOR-encoded strings through frequency analysis and character mapping (Custom Alphabet Mapping).
* **Web Steganography:** Extracted hidden data from images via the Data URI Scheme (Base64) and identified hidden visual elements via CSS inspection.
* **Chain Decoding:** Performed complex multi-step conversions following the Binary -> Decimal -> Hexadecimal -> ASCII pipeline.
* **Information Disclosure:** Identified sensitive credentials and hidden directories within HTML comments and non-standard files like `robots.txt`.


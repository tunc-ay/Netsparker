# What is Netsparker?

Netsparker is an automated, yet fully configurable, [web application security scanner](https://www.netsparker.com/online-web-application-security-scanner/) that enables you to scan websites, web applications and web services, and identify security flaws. Netsparker can scan all types of web applications, regardless of the platform or the language with which they are built.

Netsparker is the only online web application security scanner that automatically exploits identified vulnerabilities in a read-only and safe way, in order to confirm identified issues. It also presents proof of the vulnerability so that you do not need to waste time manually verifying it. For example, in the case of a detected SQL injection vulnerability, it will show the database name as the proof of exploit.

Our scanning technology is designed to help you secure web applications easily without any fuss, so you can focus on fixing the reported vulnerabilities. If Netsparker cannot automatically confirm a vulnerability, it will inform you about it by prefixing it with *Possible* and assigning a Certainty value, so you know what should be fixed immediately.

## Key Concepts

This is a list of key concepts in Netsparker.

| **Concept** | **Description** |
| --- | --- |
| Highly accurate | Netsparker produces highly accurate web application security scans, whose vulnerabilities are verified, proving that they are not false positives. |
| Proof-Based ScanningTM | Our Proof-Based Scanning technology actively and automatically verifies detected vulnerabilities, confirming that they are real and not false positives, by exploiting them in a read-only and safe manner. Depending on the type of vulnerability, Netsparker will generate proof. Some vulnerabilities also allow you to exploit them manually or generate a Proof of Concept. It is completely safe. For example, when [exploiting a SQL injection vulnerability](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/) and generating a proof of exploit for it, the scanners will only try to read data from the database, not write or delete data from the database. |
| Proof of Concept | Netsparker identifies vulnerabilities, then it safely exploits them _during_ the web vulnerability scan. This Proof of Concept is the actual exploit that proves that the vulnerability exists. And, it&#39;s useful if you need to reproduce the vulnerability for a developer.This is what an XSS vulnerability report looks like, where the Proof URL is what Netsparker uses to exploit the vulnerability. |
| Proof of Exploit | A proof of exploit is used to report the data that can be extracted from the vulnerable target once the vulnerability is exploited, demonstrating the impact an exploited vulnerability can have and proving that it is not a false positive. This is what it looks like in the case of an SQL Injection vulnerability, as reported in Netsparker Enterprise. 
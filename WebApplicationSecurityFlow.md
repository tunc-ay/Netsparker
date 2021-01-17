# Web Application Security Scanning Flow

Launching an automated web application security scan is not enough on its own. Maintaining a secure web application is a broader and more challenging process. Thanks to Netsparker’s advanced technologies, discovering issues in a web application and fixing them is easier than ever. </br>

Netsparker will help you with default options and explanations. But you also need to gather some detailed information about your web applications. This topic will help you prepare, so that you can set the correct options for your Netsparker scan. </br>

![Web Application Security Flow](https://dpsvdv74uwwos.cloudfront.net/statics/img/drive/wvvhlsy15-4ko41hzhs9wtqhqneuhvb0zqt.png "Web Application Security Flow")

## Knowing Your Web Application

Before launching a scan, it's best to conduct a mental inventory. The answers will help you to optimize your [Scan Policies](https://www.netsparker.com/support/scan-policies-netsparker/).

Do you know the following about your website [Technologies](https://www.netsparker.com/support/technologies-netsparker/)?

* Which programming (or scripting) languages were used to develop the website?
* Is the web application based on a framework or a CMS?
* On which operating system does the application run?
* Are there any databases connected to the application?
* Are you aware of all your online collateral, web applications and services?
* The most vulnerable components of a web application could be the login forms and the input fields (which are reported in the [Knowledge Base Tab](https://www.netsparker.com/support/technical-report/#knowledge-base-tab) once a scan has been completed). Have you checked your websites to determine if there are any web forms or input areas? You will need them for setting form authentication or excluding them from the Scan Scope. Excluding components will be very useful in such cases. Netsparker carries out a large number of attacks which may negatively affect your web application if the parameters are not set properly. For instance, if there is a mail form on your web application, Netsparker will send requests on that form and you may receive many unwanted emails.

For further information, see [Before Using Netsparker](https://www.netsparker.com/support/before-using-netsparker/), [Application & Service Discovery Service](https://www.netsparker.com/support/application-and-service-discovery/), and [Do Netsparker Scans Damage Web Applications?](https://www.netsparker.com/support/negative-impact-netsparker-scans/).

## Preparing and Configuring Scans

After learning which technologies and other elements exist on the web application, next you will start configuring the scan. 

Netsparker is a very user-friendly, automated web application security scanner. In most cases, it is enough to enter the target URL and start scanning. The scanner will automatically fine-tune itself. However, even though Netsparker will discover the issues successfully, it may make extra and unnecessary security checks, keeping the target host needlessly busy, because the scan is not configured precisely. So, you can choose to configure the [Scan Settings](https://www.netsparker.com/support/creating-new-scan-netsparker/#netsparker-enterprise-scan-options-fields) yourself. Alternatively, you can make use of [Netsparker Assistant](https://www.netsparker.com/support/netsparker-assistant/).

The duration of a web application security scan depends on various factors. To keep the duration short, you can optimize a scan by configuring some of the settings. For even more accurate scan results, you should configure the scan further. You can configure the following options:

* Crawling Options
* Scan Scope
* URL Rewrite Rules
* Website Authentication
* Scan Policy

Before scanning your website, the target host must be ready for the test. Ensure that the target host stays online during the scanning process. In addition, you can use the Pause and Stop features. To avoid any service breakdowns, you can use the [Scan Time Window](https://www.netsparker.com/support/scan-time-window/) to set the time for Netsparker to scan the target URL.

For further information, see [Overview of Scan Policies](https://www.netsparker.com/support/scan-policies-netsparker/) and [Scan Policy Optimizer](https://www.netsparker.com/support/scan-policy-optimizer-netsparker/).

## Scanning Your Web Applications

Think of your web applications as an unsecured back door into your business. Modern web applications let users interact with the host’s network or server. Poor coding and defective hardening policies may negatively affect the web application security. If the web application is not developed with the relevant security standards, it can be manipulated by exploiting vulnerabilities and misconfigurations. </br>

Netsparker’s advanced Proof-Based ScanningTM technology makes it easy to identify SQL Injection, Cross-site Scripting (XSS) and thousands of other vulnerabilities in web applications. Netsparker also can detect out-of-date web application technologies to help you keep your web application up-to-date. </br>

    The VDB (Vulnerability database) is updated every week.

In the Netsparker Standard edition, there are also built-in security testing tools such as HTTP Request Builder, ViewState Viewer, and Encoding and Decoding Tools. It also has a report generator that allows the user to export the details of the scan results. Netsparker can be easily integrated into your SDLC, DevOps and other environments to help keep your web applications secure. </br>

For further information, see [What is Netsparker?](https://www.netsparker.com/support/what-is-netsparker/) and [Integrating Netsparker Enterprise into Your Existing SDLC](https://www.netsparker.com/support/integrating-netsparker-enterprise-SDLC/).

## Reviewing and Comparing Scan Results with Previous Scans
If you have a Netsparker edition, you probably have already performed a scan of your web application. Previous scans make you aware of the security development process. Please compare the old and new scan results, and review the newly discovered issues. </br>

* Netsparker allows you to retest the issues found in a previous scan.
* You can also choose the security test type for specific vulnerabilities.
* Incremental scans help you save time. Instead of scanning the web application, you can just scan the new pages added since the last scan.

You can integrate an issue tracker with Netsparker to help you manage and maintain a list of all the issues at each stage of the SDLC (Software Development Life Cycle). </br>

For further information, see [Creating a New Scan](https://www.netsparker.com/support/creating-new-scan-netsparker/) and [Reviewing Scan Results and Imported Vulnerabilities](https://www.netsparker.com/support/reviewing-scan-results-imported-vulnerabilities/). </br>

## Fixing Issues
Attackers use different methods to hack web applications. Every day brings the potential for a new attack. Scheduling and performing periodic security scans are vital. Each scan may discover new vulnerabilities in your web application. If vulnerabilities are detected, you need to fix them as quickly as possible and then re-test them with Netsparker. At this point, Netsparker checks whether the issues are properly fixed. If so, they are marked as resolved.  This process needs to be conducted continuously so that the security of your web applications is maintained. </br>

For further information, see [Updating the Status of an Issue in Netsparker Enterprise](https://www.netsparker.com/support/fixing-vulnerability-updating-status-issue-netsparker-enterprise/).

## Retesting Fixed Issues

The main objective of a security scan is to detect issues and fix them. Netsparker lets you retest the issues to check if they are fixed or not. Instead of starting a full scan, you can retest only the fixed issues. </br>

In Netsparker Standard, you can retest a single issue or multiple issues at once. In Netsparker Enterprise, you can retest all issues. Netsparker Enterprise automatically checks the issue. If it is fixed as intended, the issue will be marked as Fixed. If not, the issue will be assigned back to the Assignee. If you are sure that the issue is a false positive, you can mark it as a False Positive. You can also mark the issue as Accepted Risk if you are aware of its impact. And, finally, you can manually mark an issue as Fixed (Unconfirmed). </br>

For further information, see [How to Run a Retest in Netsparker Enterprise](https://www.netsparker.com/support/creating-new-scan-netsparker/#how-to-run-a-retest-in-netsparker-enterprise), and [How to Run a Retest in Netsparker Standard](https://www.netsparker.com/support/creating-new-scan-netsparker/#how-to-run-a-retest-in-netsparker-standard).

## Generating Reports
Reporting is the most important step in the web application security scanning process. Netsparker can generate reports based on relevant regulations. If you want your web application to be compliant with ISO 27001, generate an ISO 27001 Compliance Report to check for specific vulnerabilities and apply the correct remedies. </br>

Netsparker Enterprise On-Demand also has a PCI compliance feature that enables you to automate most of the process and generate approved PCI compliance reports. When a PCI scan is completed, websites that meet the standard will receive an approved compliance report. If the website fails, you can fix the listed vulnerabilities and retest them.</br>

Netsparker also enables you to create custom reports (see [Custom Report Policies](https://www.netsparker.com/support/custom-report-policies-netsparker/)). This means you can change the vulnerability details, classification numbers, actions to take or add the logo of your organization. </br>

For further information, see [Built-in Reports](https://www.netsparker.com/support/built-in-reports-netsparker/) and [Report Templates](https://www.netsparker.com/support/report-templates-netsparker).


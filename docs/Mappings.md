# OWASP IoT Top 10 2014

|  **OWASP IoT Top 10 2014** | **OWASP IoT Top 10 2018** |
| --- | --- |
|  **I1 Insecure Web Interface** | **I3 Insecure Ecosystem Interfaces** |
|  **I2 Insufficient Authentication/Authorization** | **I1 Weak, Guessable, or Hardcoded Passwords<br/><br/>I9 Insecure Default Settings** |
|  **I3 Insecure Network Services** | **I2 Insecure Network Services** |
|  **I4 Lack of Transport Encryption/Integrity Verification** | **I7 Insecure Data Transfer and Storage** |
|  **I5 Privacy Concerns** | **I6 Insufficient Privacy Protection** |
|  **I6 Insecure Cloud Interface** | **I3 Insecure Ecosystem Interfaces** |
|  **I7 Insecure Mobile Interface** | **I3 Insecure Ecosystem Interfaces** |
|  **I8 Insufficient Security Configurability** | **I9 Insecure Default Settings** |
|  **I9 Insecure Software/Firmware** | **I4 Lack of Secure Update Mechanism<br/><br/>I5 Use of Insecure or Outdated Components** |
|  **I10 Poor Physical Security** | **I10 Lack of Physical Hardening** |
***
# Code of Practice

|  **[Code of Practice (UK Government)](https://www.gov.uk/government/publications/secure-by-design/code-of-practice-for-consumer-iot-security	 "Code of Practice (UK Government)")** | **Description** | **OWASP IoT Top 10 Mappping** |
| --- | --- | --- |
|  **1. No default passwords** | All IoT device passwords shall be unique and not resettable to any universal factory default value | **I1 Weak, Guessable, or Hardcoded Passwords** |
|  **2. Implement a vulnerability disclosure policy** | All companies that provide internet-connected devices and services shall provide a public point of contact as part of a vulnerability disclosure policy in order that security researchers and others are able to report issues. Disclosed vulnerabilities should be acted on in a timely manner. | **N/A** |
|  **3. Keep software updated** | Software components in internet-connected devices should be securely updateable. Updates shall be timely and should not impact on the functioning of the device. An end-of-life policy shall be published for end-point devices which explicitly states the minimum length of time for which a device will receive software updates and the reasons for the length of the support period. The need for each update should be made clear to consumers and an update should be easy to implement. For constrained devices that cannot physically be updated, the product should be isolatable and replaceable. | **I4 Lack of Secure Update Mechanism<br/><br/>I8 Lack of Device Management** |
|  **4. Securely store credentials and security-sensitive data** | Any credentials shall be stored securely within services and on devices. Hard-coded credentials in device software are not acceptable. | **I7 Insecure Data Transfer and Storage** |
|  **5. Communicate securely** | Security-sensitive data, including any remote management and control, should be encrypted in transit, appropriate to the properties of the technology and usage. All keys should be managed securely. | **I3 Insecure Ecosystem Interfaces<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **6. Minimise exposed attack surfaces** | All devices and services should operate on the ‘principle of least privilege’; unused ports should be closed, hardware should not unnecessarily expose access, services should not be available if they are not used and code should be minimised to the functionality necessary for the service to operate. Software should run with appropriate privileges, taking account of both security and functionality. | **I2 Insecure Network Services<br/><br/>I5 Use of Insecure or Outdated Components** |
|  **7. Ensure software integrity** | Software on IoT devices should be verified using secure boot mechanisms. If an unauthorised change is detected, the device should alert the consumer/administrator to an issue and should not connect to wider networks than those necessary to perform the alerting function. | **I9 Insecure Default Settings<br/><br/>I10 Lack of Physical Hardening** |
|  **8. Ensure that personal data is protected** | Where devices and/or services process personal data, they shall do so in accordance with applicable data protection law, such as the General Data Protection Regulation (GDPR) and the Data Protection Act 2018. Device manufacturers and IoT service providers shall provide consumers with clear and transparent information about how their data is being used, by whom, and for what purposes, for each device and service. This also applies to any third parties that may be involved (including advertisers). Where personal data is processed on the basis of consumers’ consent, this shall be validly and lawfully obtained, with those consumers being given the opportunity to withdraw it at any time. | **I6 Insufficient Privacy Protection** |
|  **9. Make systems resilient to outages** | Resilience should be built in to IoT devices and services where required by their usage or by other relying systems, taking into account the possibility of outages of data networks and power. As far as reasonably possible, IoT services should remain operating and locally functional in the case of a loss of network and should recover cleanly in the case of restoration of a loss of power. Devices should be able to return to a network in a sensible state and in an orderly fashion, rather than in a massive scale reconnect. | **I8 Lack of Device Management<br/><br/>I9 Insecure Default Settings** |
|  **10. Monitor system telemetry data** | If telemetry data is collected from IoT devices and services, such as usage and measurement data, it should be monitored for security anomalies. | **N/A** |
|  **11. Make it easy for consumers to delete personal data** | Devices and services should be configured such that personal data can easily be removed from them when there is a transfer of ownership, when the consumer wishes to delete it and/or when the consumer wishes to dispose of the device. Consumers should be given clear instructions on how to delete their personal data. | **I6 Insufficient Privacy Protection** |
|  **12. Make installation and maintenance of devices easy** | Installation and maintenance of IoT devices should employ minimal steps and should follow security best practice on usability. Consumers should also be provided with guidance on how to securely set up their device. | **I8 Lack of Device Management<br/><br/>I9 Insecure Default Settings** |
|  **13. Validate input data** | Data input via user interfaces and transferred via application programming interfaces (APIs) or between networks in services and devices shall be validated. | **I3 Insecure Ecosystem Interfaces** |
***
# GSMA IoT Security Assessment Checklist

|  **[GSMA IoT Security Assessment Checklist](https://www.gsma.com/iot/iot-security-assessment/ "GSMA IoT Security Assessment Checklist")** | **Description** | **OWASP IoT Top 10 Mappping** |
| --- | --- | --- |
|  **CLP11_5** | 11.5 Risk Assessments | **N/A** |
|  **CLP11_6** | 11.6 Privacy Considerations | **I6 Insufficient Privacy Protection** |
|  **CLP11_7** | 11.7 Secure Development | **I5 Use of Insecure or Outdated Components** |
|  **CLP11_7.2** | 11.7.2 Review the current product or service’s Security Model | **N/A** |
|  **CLP12_5.1** | 5.1 Implement a Service Trusted Computing Base | **I5 Use of Insecure or Outdated Components** |
|  **CLP12_5.2** | 5.2 Define an Organizational Root of Trust | **I7 Insecure Data Transfer and Storage** |
|  **CLP12_5.3** | 5.3 Define a Bootstrap Method | **I9 Insecure Default Settings** |
|  **CLP12_5.4** | 5.4 Define a Security Infrastructure for Systems Exposed to the Public Internet | **I2 Insecure Network Services<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **CLP12_5.5** | 5.5 Define a Persistent Storage Model | **I7 Insecure Data Transfer and Storage** |
|  **CLP12_5.6** | 5.6 Define an Administration Model | **I3 Insecure Ecosystem Interfaces<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **CLP12_5.7** | 5.7 Define a Systems Logging and Monitoring Approach | **I8 Lack of Device Management** |
|  **CLP12_5.8** | 5.8 Define an Incident Response Model | **I8 Lack of Device Management** |
|  **CLP12_5.9** | 5.9 Define a Recovery Model | **I8 Lack of Device Management** |
|  **CLP12_5.10** | 5.10 Define a Sunsetting Model | **I8 Lack of Device Management** |
|  **CLP12_5.11** | 5.11 Define a Set of Security Classifications | **I8 Lack of Device Management** |
|  **CLP12_5.12** | 5.12 Define Classifications for Sets of Data Types | **I6 Insufficient Privacy Protection** |
|  **CLP12_6.1** | 6.1 Define a Clear Authorization Model | **I1 Weak, Guessable, or Hardcoded Passwords<br/><br/>I3 Insecure Ecosystem Interfaces** |
|  **CLP12_6.2** | 6.2 Manage the Cryptographic Architecture | **I3 Insecure Ecosystem Interfaces<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **CLP12_6.3** | 6.3 Define a Communications Model | **I2 Insecure Network Services<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **CLP12_6.4** | 6.4 Use Network Authentication Services | **I2 Insecure Network Services<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **CLP12_6.5** | 6.5 Provision Servers Where Possible | **I8 Lack of Device Management** |
|  **CLP12_6.6** | 6.6 Define an Update Model | **I4 Lack of Secure Update Mechanism** |
|  **CLP12_6.7** | 6.7 Define a Breach Policy for Exposed Data | **I6 Insufficient Privacy Protection** |
|  **CLP12_6.8** | 6.8 Force Authentication Through the Service Ecosystem | **I3 Insecure Ecosystem Interfaces** |
|  **CLP12_6.9** | 6.9 Implement Input Validation | **I3 Insecure Ecosystem Interfaces** |
|  **CLP12_6.10** | 6.10 Implement Output Filtering | **I3 Insecure Ecosystem Interfaces** |
|  **CLP12_6.11** | 6.11 Enforce Strong Password Policy | **I1 Weak, Guessable, or Hardcoded Passwords** |
|  **CLP12_6.12** | 6.12 Define Application Layer Authentication and Authorization | **I3 Insecure Ecosystem Interfaces** |
|  **CLP12_6.13** | 6.13 Default-Open or Fail-Open Firewall Rules and System Hardening | **I2 Insecure Network Services<br/><br/>I3 Insecure Ecosystem Interfaces<br/><br/>I8 Lack of Device Management** |
|  **CLP12_6.14** | 6.14 Evaluate the Communications Privacy Model | **I6 Insufficient Privacy Protection** |
|  **CLP12_7.1** | 7.1 Define an Application Execution Environment | **N/A** |
|  **CLP12_7.2** | 7.2 Use Partner-Enhanced Monitoring Services | **I8 Lack of Device Management** |
|  **CLP12_7.3** | 7.3 Use a Private APN for Cellular Connectivity | **N/A** |
|  **CLP12_7.4** | 7.4 Define a Third-Party Data Distribution Policy | **I6 Insufficient Privacy Protection<br/><br/>I8 Lack of Device Management** |
|  **CLP12_7.5** | 7.5 Build a Third-Party Data Filter | **N/A** |
|  **CLP12_8.1** | 8.1 Protect Against Rowhammer and Similar Attacks | **N/A** |
|  **CLP12_8.2** | 8.2 Protect Against Virtual Machine Compromises | **N/A** |
|  **CLP12_8.3** | 8.3 Build an API for Users to Control Privacy Attributes | **I6 Insufficient Privacy Protection** |
|  **CLP12_8.4** | 8.4 Define a False Negative/Positive Assessment Model | **I9 Insecure Default Settings** |
|  **CLP13_6.1** | 6.1 Implement an Endpoint Trusted Computing Base | **I9 Insecure Default Settings** |
|  **CLP13_6.2** | 6.2 Utilize a Trust Anchor | **I9 Insecure Default Settings** |
|  **CLP13_6.3** | 6.3 Use a Tamper Resistant Trust Anchor | **I9 Insecure Default Settings** |
|  **CLP13_6.4** | 6.4 Utilise an API for the TCB | **I2 Insecure Network Services<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_6.5** | 6.5 Defining an Organizational Root of Trust | **I3 Insecure Ecosystem Interfaces<br/><br/>I10 Lack of Physical Hardening** |
|  **CLP13_6.6** | 6.6 Personalize Each Endpoint Device Prior to Fulfilment | **I1 Weak, Guessable, or Hardcoded Passwords<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_6.7** | 6.7 Minimum Viable execution Platform | **I3 Insecure Ecosystem Interfaces** |
|  **CLP13_6.8** | 6.8 Uniquely Provision Each Endpoint | **I1 Weak, Guessable, or Hardcoded Passwords<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_6.9** | 6.9 Endpoint Password Management | **I1 Weak, Guessable, or Hardcoded Passwords** |
|  **CLP13_6.10** | 6.10 Use a Proven Random Number Generator | **I9 Insecure Default Settings** |
|  **CLP13_6.11** | 6.11 Cryptographically Sign Application Images | **I9 Insecure Default Settings** |
|  **CLP13_6.12** | 6.12 Remote Endpoint Administration | **I8 Lack of Device Management** |
|  **CLP13_6.13** | 6.13 Logging and Diagnostics | **I8 Lack of Device Management** |
|  **CLP13_6.14** | 6.14 Enforce Memory Protection | **N/A** |
|  **CLP13_6.15** | 6.15 Secure Bootloaders | **I9 Insecure Default Settings** |
|  **CLP13_6.16** | 6.16 Locking Critical Sections of Memory | **I7 Insecure Data Transfer and Storage<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_6.18** | 6.18 Perfect Forward Secrecy | **I7 Insecure Data Transfer and Storage** |
|  **CLP13_6.19** | 6.19 Endpoint Communications Security | **I2 Insecure Network Services<br/><br/>I3 Insecure Ecosystem Interfaces<br/><br/>I7 Insecure Data Transfer and Storage** |
|  **CLP13_6.20** | 6.20 Authenticating an Endpoint Identity | **I1 Weak, Guessable, or Hardcoded Passwords** |
|  **CLP13_7.1** | 7.1 Use Internal Memory for Secrets | **I7 Insecure Data Transfer and Storage** |
|  **CLP13_7.2** | 7.2 Anomaly Detection | **I8 Lack of Device Management** |
|  **CLP13_7.3** | 7.3 Use Tamper Resistant Product Casing | **I10 Lack of Physical Hardening** |
|  **CLP13_7.4** | 7.4 Enforce Confidentiality and Integrity to/from the Trust Anchor | **I9 Insecure Default Settings** |
|  **CLP13_7.5** | 7.5 Over the Air Application Updates | **I4 Lack of Secure Update Mechanism** |
|  **CLP13_7.6** | 7.6 Improperly Engineered or Unimplemented Mutual Authentication | **I1 Weak, Guessable, or Hardcoded Passwords<br/><br/>I3 Insecure Ecosystem Interfaces** |
|  **CLP13_7.8** | 7.8 Privacy and Unique Endpoint Identities | **I3 Insecure Ecosystem Interfaces<br/><br/>I6 Insufficient Privacy Protection** |
|  **CLP13_7.9** | 7.9 Run Applications with Appropriate Privilege Levels | **I3 Insecure Ecosystem Interfaces** |
|  **CLP13_7.10** | 7.10 Enforce a Separation of Duties in the Application Architecture | **I3 Insecure Ecosystem Interfaces** |
|  **CLP13_7.11** | 7.11 Enforce Language Security | **I5 Use of Insecure or Outdated Components** |
|  **CLP13_7.12** | 7.12 Implement Persistent Pentesting | **N/A** |
|  **CLP13_8.1** | 8.1 Enforce Operating System Level Security Enhancements | **I5 Use of Insecure or Outdated Components<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_8.2** | 8.2 Disable Debugging and Testing Technologies | **I9 Insecure Default Settings<br/><br/>I10 Lack of Physical Hardening** |
|  **CLP13_8.3** | 8.3 Tainted Memory via Peripheral-Based Attacks | **I7 Insecure Data Transfer and Storage <br/><br/>I9 Insecure Default Settings<br/><br/>I10 I10 Lack of Physical Hardening** |
|  **CLP13_8.4** | 8.4 User Interface Security | **I3 Insecure Ecosystem Interfaces** |
|  **CLP13_8.6** | 8.6 Utilize a Private APN | **I9 Insecure Default Settings** |
|  **CLP13_8.7** | 8.7 Implement Environmental Lock-Out Thresholds | **I3 Insecure Ecosystem Interfaces** |
|  **CLP13_8.8** | 8.8 Enforce Power Warning Thresholds | **I10 Lack of Physical Hardening** |
|  **CLP13_8.9** | 8.9 Environments Without Back-End Connectivity | **I3 Insecure Ecosystem Interfaces<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_8.10** | 8.10 Device Decommissioning and Sunsetting | **I8 Lack of Device Management** |
|  **CLP13_8.11** | 8.11 Unauthorized Metadata Harvesting | **I6 Insufficient Privacy Protection** |
|  **CLP13_9.1** | 9.1 Intentional and Unintentional Denial of Service | **I2 Insecure Network Services<br/><br/>I3 Insecure Ecosystem Interfaces<br/><br/>I9 Insecure Default Settings** |
|  **CLP13_9.2** | 9.2 Safety Critical Analysis | **I8 Lack of Device Management** |
|  **CLP13_9.3** | 9.3 Defeating Shadowed Components and Untrusted Bridges | **I10 Lack of Physical Hardening** |
|  **CLP13_9.4** | 9.4 Defeating a Cold Boot Attack | **I10 Lack of Physical Hardening** |
|  **CLP13_9.5** | 9.5 Non-Obvious Security Risks (Seeing Through Walls) | **N/A** |
|  **CLP13_9.6** | 9.6 Combating Focused Ion Beams and X-Rays | **N/A** |
|  **CLP13_9.7** | 9.7 Consider Supply Chain Security | **I5 Use of Insecure or Outdated Components<br/><br/>I10 Lack of Physical Hardening** |
***

# CTIA Cybersecurity Certification Test Plan for IoT Devices

| [**CTIA Cybersecurity Certification Test Plan** **for IoT Devices** ](https://api.ctia.org/wp-content/uploads/2018/10/CTIA-IoT-Cybersecurity-Certification-Test-Plan-V1_0_1.pdf) | **Description \(Purpose\)** | [**OWASP IoT Top 10 Mappping**](https://www.owasp.org/images/1/1c/OWASP-IoT-Top-10-2018-final.pdf) |
| :--- | :--- | :--- |
| **1 Terms of Service and Privacy Policies Test** | Device Terms of Service and privacy policy are readily available. The Terms of Service cover “end of life” for the device. | **I6 Insufficient Privacy Protection** |
| **2 Password Management Test** | Device supports local password management. | **I1 Weak, Guessable, or Hardcoded Passwords**  **I3 Insecure Ecosystem Interfaces**  **I9 Insecure Default Settings** |
| **3 Authentication Tests.** | Device supports user authentication. | **I3 Insecure Ecosystem Interfaces** |
| **4 Access Controls** | Device enforces role-based access control. | **I1 Weak, Guessable, or Hardcoded Passwords** |
| **5 Patch Management** | Device supports automatic and manual installation of patches from an authorized source. | **I4 Lack of Secure Update Mechanism**  **I5 Use of Insecure or Outdated Components** |
| **6 Software Upgrades** | Device supports manual installation software upgrades from an authorized source. | **I4 Lack of Secure Update Mechanism**  **I5 Use of Insecure or Outdated Components** |
| **7 Audit Log** | Device supports the gathering audit log events and reporting them to an EMS using IPsec, SSH, TLS, or DTLS for encryption and integrity protection. | **I8 Lack of Device Management** |
| **8 Encryption of Data in Transit** | Device supports encrypted communications using IPsec, SSH, TLS or DTLS. | **I7 Insecure Data Transfer and Storage** |
| **9 Multi-Factor Authentication** | Device supports multiple authentication factors. | **N/A** |
| **10 Remote Deactivation** | Device can be remotely deactivated by the EMS. | **N/A** |
| **11 Secure Boot** | Device supports a secure boot process to protect its hardware \(e.g., UEFI\). | **I9 Insecure Default Settings** |
| **12 Threat Monitoring** | Device supports logging of anomalous or malicious activity based on configured polices and rules. | **I8 Lack of Device Management** |
| **13 IoT Device Identity** | Device provides an IoT Device Type and a globally unique IoT Device Identity. | **I8 Lack of Device Management** |
| **14 Digital Signature Generation and Validation** | Device supports generation and validation of digital signatures | **I7 Insecure Data Transfer and Storage** |
| **15 Encryption of Data at Rest** | Device supports an effective mechanism for encrypting data stored on the device. | **I7 Insecure Data Transfer and Storage** |
| **16 Tamper Evidence** | Device has the ability to alert a monitoring system when it is physically opened. | **I10 Lack of Physical Hardening** |
| **17 Design-In Features** | Device includes features to fail secure, provide boundary security, and ensure function isolation. | **I2 Insecure Network Services**  **I3 Insecure Ecosystem Interfaces**  **I9 Insecure Default Settings** |


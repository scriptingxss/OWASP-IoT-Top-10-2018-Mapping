# OWASP IoT Top 10 2018 Mapping Project

The OWASP IoT Mapping Project is intended to provide a mapping of the OWASP IoT Top 10 2018 to industry publications and sister projects. The goal is to assist with making the OWASP IoT Top 10 practical. As with all Top 10 lists, they should be used as a first step and expanded upon according to the applicable IoT ecosystem. Typically, lists have shortcomings that are unable to cover each aspect of an IoT environment. Each mapping may not have a 1 to 1 relation but will have similar recommendations and/or controls.

### OWASP IoT Top 10 2018

|  |  |  |
| :--- | :--- | :--- |
| OWASP IoT Top 10 | Description |  |
| I1 Weak, Guessable, or Hardcoded Passwords | Use of easily bruteforced, harcoded, publicly available, and/or unchangable password in client-side software/firmware that can grant unauthorized access to deployed systems. |  |
| I2 Insecure Network Services | Unneeded or insecure network services running on the device itself, especially those exposed to the internet, that compromise the confidentiality, integrity/authenticity, or availability of information or allow unauthorized remote control |  |
| I3 Insecure Ecosystem Interfaces | Insecure web, backend API, cloud or mobile interfaces that allow compromise of the product and/or its ecosystem. Common issues include a lack of authentication/authorization, lacking or weak encryption, and a lack of input and output filtering. |  |
| I4 Lack of Secure Update Mechanism | Lack of ability to securely update the device/ecosystem, lack of firmware validation on device, lack of secure delivery \(un-encrypted in transit\), lack of anti-rollback mechanisms, lack of notifications of security changes due to updates. |  |
| I5 Use of Insecure or Outdated Components | Use of deprecated or insecure software components/libraries that could allow the device to be compromised. This includes insecure customization of operating system platforms, and use of third-party software or hardware components from a compromised suppply chain. |  |
| I6 Insufficient Privacy Protection | User’s personal information stored on the device or in the ecosystem that is used insecurely, improperly, or without permission. |  |
| I7 Insecure Data Transfer and Storage | Lack of encryption or access control of sensitive data anywhere within the ecosystem, including at rest, in transit, or during processing. |  |
| I8 Lack of Device Management | Lack of security support on devices deployed in production, including asset management, update management, secure decommissioning, systems monitoring, and response capabilities. |  |
| I9 Insecure Default Settings | Devices or systems shipped with insecure default settings or lack the ability to make the system more secure by restricting operators from modifying configurations. |  |
| I10 Lack of Physical Hardening | Lack of physical hardening measures, allowing potential attackers to gain sensitive information that can help in a future remote attack or take local control of the device. |  |

## Contributing

If you feel a crucial mapping is missing, feel free to contribute by submitting a pull request, contact the project leaders, or join the [OWASP Slack Team](https://owasp.slack.com/) and look for us in the \#iot-security channel


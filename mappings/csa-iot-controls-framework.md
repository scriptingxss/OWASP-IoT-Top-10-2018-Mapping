# CSA IoT Controls Framework



<table>
  <thead>
    <tr>
      <th style="text-align:left"><a href="https://cloudsecurityalliance.org/download/artifacts/iot-security-controls-framework/"><b>CSA IoT Controls Framework</b></a>
      </th>
      <th style="text-align:left"><b>Description (Control Specification)</b>
      </th>
      <th style="text-align:left"><a href="https://www.owasp.org/images/1/1c/OWASP-IoT-Top-10-2018-final.pdf"><b>OWASP IoT Top 10 Mapping</b></a>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>RSM-01</b>
        <br /><b>RSM-02</b>
      </td>
      <td style="text-align:left">Adopt a standardized industry recognized risk management approach. Baseline
        security requirements should be established for developed or acquired IoT
        components to comply with applicable legal, statutory, and regulatory compliance
        obligations. Deviations from standard baseline configurations should be
        authorized following change management policies and procedures prior to
        deployment, provisioning, or use. Compliance with security baseline requirements
        should be reassessed based on business needs.
        <br />
        <br />&quot;Perform a risk assessment. Analyze sources, storage and transmissions
        of sensitive data across devices, gateways, applications, data stores,
        mobile applications, cloud services, fog computing services and network
        infrastructure. Analyze data classification mechanisms and data security
        capabilities to protect sensitive data from unauthorized use, access, loss,
        destruction, and falsification. Analyze the potential for trusted insiders
        to misuse their privileged access to data. Analyze data retention periods
        and end-of-life disposal requirements. Identify safety risks. Prioritize
        risks based on impact and likelihood. Decide on risk migitations for each
        risk - mitigate, defer or accept the risk.
        <br />Perform a risk assessment as follows:
        <br />&#x2022;Analyze potential risk if the security of each of the following
        components would be compromised: sources, storage and transmissions of
        sensitive data across devices, gateways, applications, data stores, mobile
        applications, cloud services, fog computing services and network infrastructure.
        <br
        />&#x2022;Analyze data classification mechanisms and data security capabilities
        in order to protect sensitive data from unauthorized use, access, loss,
        destruction or falsification.
        <br />&#x2022;Analyze the potential for trusted insiders to misuse their privileged
        access to data.
        <br />&#x2022;Analyze data retention periods and end-of-life disposal requirements.
        <br
        />&#x2022;Based on these analyses, identify your organization&#x2019;s safety
        risks. Prioritize these risks based on potential impact and likelihood
        of occurrence.
        <br />&#x2022;Choose and implement risk mitigations for each potential security
        threat: actively mitigate, defer or accept the risk.&quot;</td>
      <td style="text-align:left"><b>N/AI1 Weak, Guessable, or Hardcoded Passwords</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>TSP-01</b>
        <br /><b>TSP-02</b>
        <br /><b>TSP-03</b>
        <br /><b>TSP-04</b>
        <br /><b>TSP-05</b>
        <br /><b>TSP-06</b>
        <br /><b>TSP-07</b>
        <br /><b>TSP-08</b>
      </td>
      <td style="text-align:left">Document an enterprise IoT cyber security policy. Require all IoT implementations
        to comply with this policy or apply for an exception. Your enterprise IoT
        cyber security policy should include, at minimum, encryption, monitoring,
        auditing, authentication and access control, as well as physical security
        controls that must be applied to each component of your IoT system. Monitor
        frequently to identify out-of-compliance implementations.
        <br />
        <br />Monitor and validate the update (patch/version) status of each IoT device
        in your inventory. Flag devices that are out of policy or are unreachable
        due to disconnection. If the issue cannot be resolved (connection and update)
        through the IoT system, then an email, call or personal visit may be required,
        depending on the criticality of update and device use.
        <br />
        <br />Monitor for duplicate or compromised IoT devices. Establish rules to identify
        devices authenticating with the same identity credentials, which may indicate
        a security compromise. Investigate and remediate issues upon detection.
        <br
        />
        <br />Document a minimum cryptographic policy for TLS, DTLS and other cryptographic
        protocols. The policy should define acceptable algorithms, key lengths
        and modes of operation. Align the policy with guidance from the latest
        revision of NIST SP 800-131A.
        <br />
        <br />Document password policies that define minimum complexity requirements
        for IoT system users, administrators and service accounts. Define aging
        requirements for passwords. Define lock-out policies for all components
        of the IoT system.
        <br />
        <br />Document a data security policy for the IoT system. Define the organizational
        data classification levels and map minimum data security requirements to
        those classification levels.
        <br />
        <br />Document an identity management policy for the IoT system. Define appropriate
        uses for symmetric keys, passwords and certificates. Restrict the provision
        of duplicate identity credentials (keys, certificates, passwords) to no
        more than one device, user or service.
        <br />
        <br />Document a device security management policy for the IoT system. Define
        the minimum frequency for performing updates to firmware and software.
        Define minimum safeguards against malicious code that could compromise
        IoT devices. Define minimum frequency for applying patches to third party
        libraries.</td>
      <td style="text-align:left">
        <p><b>I1 Weak, Guessable, or Hardcoded Passwords<br /></b>
        </p>
        <p><b>I8 Lack of Device Management</b>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>GVN-01</b>
        <br /><b>GVN-02</b>
        <br /><b>GVN-03</b>
        <br /><b>GVN-04</b>
        <br /><b>GVN-05</b>
      </td>
      <td style="text-align:left">Create a governance framework for the IoT system. Define who is accountable
        for the security of distributed systems and their interconnection to cloud
        and other data services. Identify executive leaders responsible for each
        individual system, and define the specific responsibilities for securing
        those systems. Identify and document the roles and responsibilities of
        employees and third party users for protecting data and assets within your
        IoT systems.
        <br />
        <br />Document all standards, as well as regulatory, legal and statutory requirements
        relevant to your IoT system. Communicate the impact of these requirements
        to individual IoT system owners.
        <br />
        <br />Perform independent security assessments of IoT inventory at least annually
        to ensure the organization addresses nonconformities of established policies,
        standards, procedures, and compliance obligations.
        <br />
        <br />Audit user, administrator, service and device accounts within the IoT
        system at least annually. Take action to disable any accounts that are
        determined to be unnecessary, unauthorized and expired.
        <br />
        <br />Establish procedures to cleanse data as it moves from the Production environment
        to the DEV/QA environment in order to reduce the risk of replicating sensitive
        operational information to the DEV/QA environment when debugging is required.</td>
      <td
      style="text-align:left"><b>N/A</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>PRV-01</b>
        <br /><b>PRV-02</b>
        <br /><b>PRV-03</b>
        <br /><b>PRV-04</b>
        <br /><b>PRV-05</b>
      </td>
      <td style="text-align:left">Implement and enforce technical and policy mechanisms to restrict administrator
        ability to track location or other sensitive attributes of system users.
        Implement access controls and logging procedures to prevent insiders from
        disabling these controls without the system logging the event.
        <br />
        <br />Perform a privacy assessment of the Public Key Infrastructure (PKI) that
        issues credentials to IoT devices and services. Analyze the potential for
        tracking of user locations and activities based on correlation to the issued
        PKI certificates. If determined that a privacy concern exists, implement
        anonymity mechanisms within the PKI such as Location
        <br />Obscurer Proxies and Pseudonym Certificate Authorities.
        <br />
        <br />Perform an analysis to document metadata generated by the IoT system.
        Classify metadata based on sensitivity level. Monitor for leaked metadata
        classified as sensitive, and define actions for remediating leaks when
        discovered.
        <br />
        <br />Perform a privacy impact assessment (PIA) at the onset of new device development.
        Subjects covered during the PIA will include at a minimum: deletion of
        data from a device; mechanism used to inform users of the data collected;
        obtaining and storing consent from users authorizing the use of data; the
        means for providing users access to review and edit personal data before
        it is transferred; and notice concerning the timing and frequency of data
        collection; as well as the ability for users to opt-in to data sharing.
        <br
        />
        <br />Update privacy impact assessment (PIA) annually. Communicate key findings
        of the PIA to all system administrators. Track compliance with PIA results
        on a continuous basis.</td>
      <td style="text-align:left"><b>I6 Insufficient Privacy Protection</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>SCN-01</b>
        <br /><b>SCN-02</b>
        <br /><b>SCN-03</b>
        <br /><b>SCN-04</b>
        <br /><b>SCN-05</b>
        <br /><b>SCN-06</b>
        <br /><b>SCN-07</b>
        <br /><b>SCN-08</b>
        <br /><b>SCN-09</b>
        <br /><b>SCN-10</b>
        <br /><b>SCN-11</b>
      </td>
      <td style="text-align:left">Whenever passwords are used within an IoT system, evaluate whether certificates
        can be used instead. When possible, update systems to require certificates
        for authentication instead of passwords.
        <br />
        <br />Authentication credentials can be bound to the specific application authorized
        to make use of those credentials when using IEEE 1609.2 certificates for
        IoT devices. If using IEEE 1609.2 certificates, designate an application-unique
        identifier and use within the IEEE 1609.2 SSP/PSID bits. Validate the SSP/PSID
        fields when making authorization decisions.
        <br />
        <br />Document all IoT device configuration files. Digitally sign those files
        and store them in a secure repository. Use these digitally signed files
        to restore devices. Validate the digital signature of the file after provisioning
        to the device.
        <br />
        <br />Restrict access to IoT device configuration files. Require pseudo access
        to modify configuration files on IoT devices.
        <br />
        <br />Log all changes to configuration files. Log all access attempts to modify
        configuration files. Monitor continuously and audit on a regular basis.
        <br
        />
        <br />Minimize privileged operations that run as root and do not run network
        services (e.g., web servers) as root.
        <br />Implement IoT system role-based access control (RBAC). Include standard
        roles for users, services and devices (e.g. device, local user, system
        operator, auditor, application, gateway).
        <br />
        <br />Identify privileged operations within the IoT system. Establish elevated
        roles mapped to those privileged operations. Roles may include trusted
        device, privileged local user, system administrator, trusted application,
        and trusted gateway.
        <br />
        <br />Implement an audit user group responsible for managing audit log data,
        including reviewing and rotating data off of devices. Restrict read access
        of security logs to this audit group. Provision audit group members with
        read access, but do not provide write privileges to any audit logs.
        <br
        />
        <br />Implement additional authorization procedures when warranted, such as
        geofencing systems and time-of-day restrictions.
        <br />
        <br />Implement authenticated discovery services. Authenticate all service discovery
        queries and drop requests that fail authentication.</td>
      <td style="text-align:left"><b>I1 Weak, Guessable, or Hardcoded Passwords</b>
        <br />
        <br /><b>I3 Insecure Ecosystem Interfaces</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>SDV-01</b>
        <br /><b>SDV-02</b>
        <br /><b>SDV-03</b>
        <br /><b>SDV-04</b>
        <br /><b>SDV-05</b>
        <br /><b>SDV-06</b>
        <br /><b>SDV-07</b>
        <br /><b>SDV-08</b>
        <br /><b>SDV-09</b>
        <br /><b>SDV-10</b>
        <br /><b>SDV-11</b>
        <br /><b>SDV-12</b>
        <br /><b>SDV-13</b>
        <br /><b>SDV-14</b>
        <br /><b>SDV-15</b>
        <br /><b>SDV-16</b>
        <br /><b>SDV-17</b>
        <br /><b>SDV-18</b>
      </td>
      <td style="text-align:left">Adopt a software assurance maturity model (SAMM) to establish a secure
        development lifecycle for all developed IoT devices and components (e.g.
        OpenSAMM).
        <br />
        <br />Select an IoT integration framework to standardize secure on-boarding,
        configuration management, asset management, discovery and secure connectivity
        across newly developed IoT devices.
        <br />
        <br />Enforce the concept of least privilege. Limit applications and services
        that run as root and require authentication for all access. Do not run
        network services (e.g. web servers) as root.
        <br />
        <br />Establish good password processes. Do not hardcode passwords into the
        device and do not provision duplicate identities or passwords across multiple
        devices. Require password changes on a regular basis.
        <br />
        <br />Establish responsible disclosure policies and procedures and implement
        feedback loops to update product backlogs when a security vulnerability
        is identified or reported. Work with independent testers that report vulnerabilities
        to ensure the vulnerability is closed.
        <br />Integrate chip-to-cloud capabilities that leverage microcontrollers (MCUs)
        with pre-provisioned cloud trust anchors to support more secure bootstrap
        and zero-touch provisioning of IoT devices. Use secure MCU hardware features
        to protect sensitive material and cryptographic primitives and to perform
        trusted bootloading by validating software prior to booting.
        <br />
        <br />Use cryptographic coprocessors to offload CPU-intensive cryptographic
        operations. Design IoT products with cryptographic agility to support updates
        to algorithms and key sizes as existing approaches become obsolete. Make
        use of well-tested cryptographic modules (ideally FIPS (140-2 <a href="https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.140-2.pdf">https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.140-2.pdf</a>)
        validated). Use good sources of entropy for random number generation associated
        with key material. Ensure cryptographic modules perform power-up tests
        to include cryptographic algorithm tests, software/firmware integrity tests,
        and critical function tests.
        <br />
        <br />Eliminate or lock-down unnecessary hardware features of IoT devices (e.g.
        un-needed radios or USB interfaces). Disable or password-restrict any test
        interfaces (JTAG, UART, GPIO).
        <br />
        <br />Apply tamper protection for security-critical components of the IoT device
        ranging from simple seals and/or locked covers to piezo-electric circuits
        depending on the threat environment.
        <br />
        <br />Select a device real-time operating system (RTOS) that provides enhanced
        security features, such as application sandboxing, secure boot, access
        controls, trusted execution environment, kernel separation, and a (minimized)
        microkernel.
        <br />
        <br />Do not store API keys and other credentials in public-facing source control
        systems (e.g. gitlab/github). Publish procedures for the secure handling
        of API keys. Do not hardcode API keys into firmware, mobile applications,
        or any client-based application. Monitor at least quarterly to verify that
        API keys and other credentials are not stored in public-facing source control
        systems.
        <br />
        <br />Integrate MCUs with hardware-based separation architectures for higher
        assurance requirements. Label and operate security sensitive applications
        to run in the trusted side of the hardware only. Implement limited command
        interfaces between the trusted and untrusted components of the MCU. Configure
        the device to perform attestation of software (measure the security state
        of the software) prior to entering into trusted modes and use controlled
        execution to prevent timing delays from revealing sensitive information.
        <br
        />
        <br />Implement tamper-response mechanisms such as zeroization of key material
        and other sensitive data when warranted by the threat landscape.
        <br />
        <br />Select a device RTOS that is certified for use in specific industries,
        such as air travel and other transportation systems, industrial control
        systems, medical devices.
        <br />Establish supply chain practices. For example, subscribe to security alerts
        from all third party components and frameworks. Review updates immediately
        for proposed deployment.
        <br />
        <br />Use static and dynamic analysis tools to validate the security of all
        third party libraries.
        <br />
        <br />Validate the authenticity and integrity of all third party libraries and
        software components within an IoT system.
        <br />
        <br />Develop web services in accordance with OWASP (<a href="https://www.owasp.org/index.php/Main_Page">https://www.owasp.org/index.php/Main_Page</a>)
        security guidance.</td>
      <td style="text-align:left"><b>I1 Weak, Guessable, or Hardcoded Passwords</b>
        <br />
        <br /><b>I3 Insecure Ecosystem Interfaces</b>
        <br />
        <br /><b>I10 Lack of Physical Hardening</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>SNT-01</b>
        <br /><b>SNT-02</b>
        <br /><b>SNT-03</b>
        <br /><b>SNT-04</b>
        <br /><b>SNT-05</b>
        <br /><b>SNT-06</b>
        <br /><b>SNT-07</b>
        <br /><b>SNT-08</b>
        <br /><b>SNT-09</b>
        <br /><b>SNT-10</b>
        <br /><b>SNT-11</b>
        <br /><b>SNT-12</b>
        <br /><b>SNT-13</b>
        <br /><b>SNT-14</b>
        <br /><b>SNT-15</b>
        <br /><b>SNT-16</b>
        <br /><b>SNT-17</b>
        <br /><b>SNT-18</b>
      </td>
      <td style="text-align:left">Disable non-authenticated Bluetooth pairing procedures (e.g., JustWorks).
        <br
        />
        <br />Audit the security of bluetooth implementations using the bluetooth security
        checklist found in Section 4.4 of the NIST SP.800-121r2 (<a href="https://www.nist.gov/publications/guide-bluetooth-security-1">https://www.nist.gov/publications/guide-bluetooth-security-1</a>)
        document. Remediate any deficiencies.
        <br />
        <br />Task network security tools to search for new botnet activity, and immediately
        remove infected IoT devices upon detection. Keep up to date on botnet characteristics
        using the CSA IoTWG botnet tracker (<a href="https://gitlab.com/brianr/CloudSA_IoT_WG/wikis/iot_botnets">https://gitlab.com/brianr/CloudSA_IoT_WG/wikis/iot_botnets</a>).
        <br
        />
        <br />Securely configure all supporting software and infrastructure (e.g., web
        servers, mobile applications, cloud services) supporting the IoT system.
        Refer to specific secure configuration guidance for your system implementation.
        <br
        />
        <br />Configure whitelists between IoT devices, gateways and servers. Provision
        certificates to enable TLS or DTLS-based authentication for all MQTT and
        HTTP interactions with backend computing devices.
        <br />
        <br />Establish procedures for monitoring misbehavior and revoking credentials
        when a server/gateway is suspected of being compromised.
        <br />
        <br />Establish a security plan for mobile applications. Ensure mobile devices
        receive updates from approved/trusted repositories. Require the use of
        only approved mobile devices for managing IoT devices. Ensure that mobile
        devices store identity/key material in hardware-backed secure storage locations
        (e.g. Android KeyChain/KeyStore and iOS KeyChain).
        <br />
        <br />Install Near Field Communication (NFC) technology devices in locations
        that do not lend themselves to installation of sniffers in close proximity.
        Establish physical security protection measures (e.g. cameras/guards) to
        monitor access to these devices.
        <br />
        <br />Configure a Software-Defined Perimeter (SDP) that authenticates IoT devices
        prior to connection to a network, and restricts activities based on pre-approved
        roles and privileges.
        <br />
        <br />Use a network visualization tool to monitor the operating state and health
        status of IoT devices, gateways and services. Use simple heartbeat monitoring
        to monitor device connectivity or SNMPv3 traps for monitoring CPU utilization,
        memory, and other abnormal behaviors.
        <br />
        <br />Define physical boundaries for WSNs and limit the power rating of ZigBee
        and ZWave devices to minimize signal leakage.
        <br />
        <br />Set up Wireless Sensor Networks (WSN), such as ZigBee, ZWave and Bluetooth,
        to be disconnected from the Internet with only authorized gateways exposing
        internet connectivity.
        <br />
        <br />At least quarterly, scan the physical environment to look for anomalies,
        such as radiofrequency (RF) attacks and rogue device insertion.
        <br />
        <br />Require all communications with an IoT device to be initiated by the device.
        Log and alert about unauthorized connection requests
        <br />
        <br />Disable the default ZigBee Trust Center (TC) key and generate/use a non-default
        key for protecting the confidentiality of keys in transport.
        <br />
        <br />Distribute ZigBee Master Keys out of band. Never pass master keys over
        the network. Master keys are used to establish additional key material.
        <br
        />
        <br />Rotate ZigBee Network Keys at least annually, and disable prior keys upon
        distribution/establishment of the new network key.
        <br />
        <br />Supplement Z-Wave networks with AES 128 cryptographic keys for authentication.
        Use these keys in addition to the standard 4-byte Home ID to access a Z-Wave
        network.</td>
      <td style="text-align:left"><b>I7 Insecure Data Transfer and Storage</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>OPA-01</b>
        <br /><b>OPA-02</b>
        <br /><b>OPA-03</b>
        <br /><b>OPA-04</b>
        <br /><b>OPA-05</b>
        <br /><b>OPA-06</b>
        <br /><b>OPA-07</b>
        <br /><b>OPA-08</b>
        <br /><b>OPA-09</b>
        <br /><b>OPA-10</b>
        <br /><b>OPA-11</b>
        <br /><b>OPA-12</b>
      </td>
      <td style="text-align:left">Create maintenance plans to routinely inspect and maintain IoT hardware.
        Keep parts in inventory for repairing and replacing IoT devices immediately
        upon detection of a problem.
        <br />
        <br />Use predictive maintenance analysis to calculate expected performance
        issues or breakdowns in IoT systems. Implement preventive solutions based
        on this analysis.
        <br />
        <br />Set up cloud services to support regional failover of nodes and gateways.
        Test annually to ensure that failover is automatic in the event that a
        single region goes offline.
        <br />
        <br />Set up monitoring procedures to identify and alert on abnormally heavy
        traffic transmitted from IoT devices, which may indicate a security compromise.
        Configure cloud services to automatically rate limit connections from clients
        upon detection to guard against potential DDoS attacks.
        <br />
        <br />Work with Cloud Service Providers (CSPs) to define Service Level Agreements
        (SLAs) for uptime percentages and response timing (for incidents/patches).
        Hold CSPs accountable for any breaches of a SLA.
        <br />
        <br />Store configurations of IoT devices in the cloud. Configure digital twins,
        device shadows, etc. in order to support interfacing to device logic even
        when the physical device is disconnected. At least annually, test that
        you can update device configurations while IoT hardware is offline by taking
        the device offline, transmitting a configuration change command, and then
        bringing the device back online.
        <br />
        <br />Set up Wireless Sensor Network (WSN) gateways in a cluster formation to
        better handle heavy load and support failover in the event a single gateway
        goes offline. Configure IoT nodes to contact backup gateways when a primary
        gateway fails. At least annually, test failover capabilities and load shedding/distribution
        capabilities.
        <br />
        <br />Set up metropolitan-scale Wireless Sensor Network deployments using clusters
        of nodes deployed to geographic regions in order to minimize points of
        interconnection and reduce long-haul traffic.
        <br />
        <br />Deploy network monitoring tools and monitor IoT networks for congestion.
        Establish prioritized traffic flows (e.g. differentiated services) and
        execute dynamic rerouting (e.g. WSN/SDN) upon detection of congested communications.
        <br
        />
        <br />Cache messaging at gateways for at least 1 day (or more, depending on
        your environment) to ensure availability of messaging should IoT nodes
        be offline.
        <br />
        <br />Scan geographic areas for jammers attempting to suppress Radio Frequency
        (RF) communications. Execute incident response plans when detecting such
        an event.
        <br />
        <br />Monitor IoT node power levels by configuring nodes to alert on battery
        drainage. This may help combat attacks aimed at draining the energy from
        critical routing nodes in
        <br />WSN architectures. Investigate any discovered incidents associated with
        excess battery drainage.</td>
      <td style="text-align:left"><b>I3 Insecure Ecosystem Interfaces</b>
        <br />
        <br /><b>I8 Lack of Device Management</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>ACT-01</b>
        <br /><b>ACT-02</b>
        <br /><b>ACT-03</b>
        <br /><b>ACT-04</b>
        <br /><b>ACT-05</b>
      </td>
      <td style="text-align:left">Deploy an inventory management system and record details about each IoT
        device in inventory. Use this inventory management system to track the
        version of each IoT device, including firmware and patch status; RTOS version/image
        version; application/library versions; lost or decommissioned status; to
        whom devices are assigned; and location of devices.
        <br />
        <br />Monitor devices to identify those out of compliance with organizational
        policy and require updates or patches.
        <br />
        <br />If possible, implement an online database to automatically update changes
        to your IoT asset/inventory database. If automation of this process is
        not possible, schedule the task at a minimum quarterly.
        <br />
        <br />Establish naming conventions for your IoT devices, and configure unique
        identifiers to each device. Identifiers should be unique across the enterprise
        and designed in a manner that will allow further incorporation of large
        quantities of additional devices at a later time without naming conflicts
        (e.g. during mergers/acquisitions).
        <br />
        <br />Use unique identifiers to track devices across their lifecycles and as
        the basis for provisioning cryptographic identities/certificates.</td>
      <td
      style="text-align:left"><b>I8 Lack of Device Management</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>CMP-01</b>
        <br /><b>CMP-02</b>
        <br /><b>CMP-03</b>
        <br /><b>CMP-04</b>
        <br /><b>CMP-05</b>
      </td>
      <td style="text-align:left">Acquire IoT devices that integrate hardware security mechanisms and use
        hardware roots of trust for storage of cryptographic material and to secure
        operation of cryptographic functions, including secure boot and firmware
        signature validation.
        <br />
        <br />For devices not capable of implementing hardware-based security, use software
        security mechanisms to protect key material and cryptographic functions.
        <br
        />
        <br />Evaluate legacy IoT devices annually for technology upgrades. Legacy devices
        that do not support hardware security roots-of-trust should be replaced
        as soon as possible. In the interim, use gateway security mechanisms to
        extend the security boundary and to mitigate risks exposed by these legacy
        devices.
        <br />
        <br />Require that all gateways use a FIPS 140-2-validated (<a href="https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.140-2.pdf">https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.140-2.pdf</a>)
        hardware root of trust.
        <br />
        <br />Acquire IoT products that have undergone testing and received a device
        security certification that is applicable to your legal, statutory, and
        regulatory compliance obligations. Device certification can vary by industry,
        environment, usage, and other critical applications.</td>
      <td style="text-align:left"><b>N/A</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>LBT-01</b>
      </td>
      <td style="text-align:left">Evaluate liability potential of an IoT system where the system interfaces
        physically with the public or workers. Define safety restrictions and post
        warning notices.</td>
      <td style="text-align:left"><b>N/A</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>BCN-01</b>
      </td>
      <td style="text-align:left">Create a continuity plan that details the contact information of system
        owners. Create a system for alerting these contacts, and when an IoT system
        is compromised or made unavailable, alert these contacts.</td>
      <td style="text-align:left"><b>N/A</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>TMM-01</b>
        <br /><b>TMM-02</b>
        <br /><b>TMM-03</b>
        <br /><b>TMM-04</b>
        <br /><b>TMM-05</b>
      </td>
      <td style="text-align:left">Conduct threat modeling at the onset of any device or system development.
        Use a standardized approach to threat modeling that includes identifying
        components, data flows, and high-value code. Define the threats, prioritize
        (e.g. rate) the threats, and identify mitigations. Communicate the outputs
        of your threat model into the system requirements backlog, and track these
        requirements to completion across the lifecycle of the product or system.
        <br
        />
        <br />Validate security requirements by creating security tests and performing
        those tests on each product or system release.
        <br />
        <br />Identify threat intelligence feeds applicable to your specific industry.
        Maintain an understanding of the types of attackers that typically target
        your systems, and their motivations.
        <br />
        <br />Monitor for newly identified vulnerabilities in your products, including
        in product dependencies. Monitor for newly released patches from your suppliers.
        <br
        />
        <br />Monitor for new botnets targeting IoT devices, and communicate relevant
        characteristics (ports/services) to network security teams immediately
        so they may take action.
        <br />
      </td>
      <td style="text-align:left"><b>I3 Insecure Ecosystem Interfaces</b>
        <br />
        <br /><b>I5 Use of Insecure or Outdated Components</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>VLN-01</b>
      </td>
      <td style="text-align:left">Establish a vulnerability management program for IoT systems. Perform
        periodic or continuous vulnerability assessments (annually, at a minimum)
        on IoT devices. Track updates to IoT protocol specifications in order to
        identify upcoming security/privacy updates in libraries. Maintain a risk
        register that is updated based on vulnerability information associated
        with deployed IoT devices/systems.</td>
      <td style="text-align:left"><b>N/A</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>IMT-01</b>
        <br /><b>IMT-02</b>
      </td>
      <td style="text-align:left">Document all audit mechanisms. Verify that only assigned audit group members
        are able to read audit logs and that no user is able to write to these
        logs. Ensure offloading of audit log data (e.g. from device to cloud or
        gateway) is integrity-protected (e.g. HMAC or digital signature) and that
        the integrity protection is maintained with the log during long-term storage.
        In all cases, validate the integrity of log files prior to review.
        <br />
        <br />Establish an IoT Incident Management Plan. Identify business and technical
        Points of Contact (PoCs) for each IoT system and inform them of what their
        roles and responsibilities are in the event of a security incident. Define
        the roles of third party organizations in incident responses (e.g. vendors
        and service providers). Define a chain-of-custody for log/audit data captured
        from devices. Define and establish escalation procedures and forensics
        activities that must be performed on devices. Consider acquiring automated
        forensics capabilities in real-time from networked devices.</td>
      <td style="text-align:left"><b>N/A</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>PHY-01</b>
      </td>
      <td style="text-align:left">Establish physical security processes that restrict physical access to
        IoT edge devices and alert on physical access attempts.</td>
      <td style="text-align:left"><b>I8 Lack of Device Management</b>
        <br />
        <br /><b>I10 Lack of Physical Hardening</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>MSU-01</b>
        <br /><b>MSU-02</b>
        <br /><b>MSU-03</b>
        <br /><b>MSU-04</b>
        <br /><b>MSU-05</b>
        <br /><b>MSU-06</b>
      </td>
      <td style="text-align:left">Define misuse patterns and establish policies for revoking credentials.
        Implement procedures for reporting and adjudicating misbehavior. Establish
        and implement procedures for revoking credentials within one day of de-authorization.
        <br
        />
        <br />Employ analytics tools that in near-real-time gather and analyze device
        use and data streams about device misuse.
        <br />
        <br />Define all security-relevant events, including elevation of privilege
        attempts; successful/unsuccessful firmware update events; configuration
        changes to IoT devices and service software; account modifications; and
        tamper events. Monitor for these and other relevant security events across
        your entire IoT system, including any devices; cloud services; mobile or
        network services; and storage systems. Define thresholds for each type
        of security event and trigger investigations when thresholds are exceeded.
        <br
        />
        <br />Log every failed remote access attempt (SSH, Web, etc.). Create a process
        that automatically alerts a security administrator upon detection of five
        sequential invalid attempts in a 30-minute period.
        <br />
        <br />Automatically transmit security event data to the cloud for storage and
        analysis. Record at minimum the initiator, receiver, timestamp, data and
        event type.
        <br />
        <br />Establish an enterprise IoT wireless detection capability. Actively search
        for rogue wireless devices operating within your locations. Actively search
        for network communications to well-known botnet C2C addresses/ports. Actively
        search for unauthorized communications to vendor IP addresses. Immediately
        disable any identified devices/communications and investigate the cause
        of the infraction. Implement a system that will alert users when unintended
        violations occur.</td>
      <td style="text-align:left"><b>I8 Lack of Device Management</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>SOP-01</b>
        <br /><b>SOP-02</b>
        <br /><b>SOP-03</b>
      </td>
      <td style="text-align:left">Evaluate the safety impacts of an IoT system, log all safety risks, prioritize
        these risks, and implement mitigations for each risk. Incorporate device
        and environmental controls to enforce safety requirements.
        <br />
        <br />Conduct fault tree analysis (FTA) to identify and prioritize safety risks
        associated with your IoT system.
        <br />
        <br />Design and implement an enterprise logging capability. Protect the integrity
        of all logs from generation to storage in order to enable a chain of custody.</td>
      <td
      style="text-align:left"><b>I8 Lack of Device Management</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>CLS-01</b>
        <br /><b>CLS-02</b>
        <br /><b>CLS-03</b>
        <br /><b>CLS-04</b>
        <br /><b>CLS-05</b>
        <br /><b>CLS-06</b>
        <br /><b>CLS-07</b>
        <br /><b>CLS-08</b>
        <br /><b>CLS-09</b>
        <br /><b>CLS-10</b>
        <br /><b>CLS-11</b>
        <br /><b>CLS-12</b>
        <br /><b>CLS-13</b>
        <br /><b>CLS-14</b>
        <br /><b>CLS-15</b>
      </td>
      <td style="text-align:left">Provision unique identities to all cloud servers. Require servers to authenticate
        to each other and to all gateways.
        <br />
        <br />Configure cloud gateways to accept communications from only trusted devices
        and to require encrypted communications. Document authorized ports and
        protocols on cloud gateways, and disable non-authorized ports/protocols.
        Blacklist any unauthorized device that attempts to communicate with your
        system, and log and report the action to an administrator.
        <br />
        <br />Configure gateways to close connection to the cloud upon completion of
        communications and to initiate new connection when they need to send data
        again.
        <br />Work with Cloud Service Providers (CSPs) to ensure the data processed
        within their cloud meets privacy guidelines that are applicable to your
        legal, statutory, and regulatory compliance obligations. Consider implementing
        privacy by design principles before migrating data to the CSP allowing
        data owners to recover and retain data control (in case of SLA breach by
        Cloud Provider).
        <br />
        <br />Configure cloud services securely. Follow the guidance from applicable
        CSP security guidance protocols for your specific CSP.
        <br />
        <br />Keep all cloud infrastructure updated and patched.
        <br />
        <br />Monitor all API calls and alert about any potential API misuse.
        <br />
        <br />Authenticate IoT devices to cloud services. Deny access to any device
        that fails authentication, and log that access attempt. Set thresholds
        for the number of failures in a time period that trigger an alert to security
        administrators, and detail how the alert will be delivered. For example,
        if a device fails authentication more than five times in 30 minutes, then
        flag the sequence as a security event and alert a security administrator.
        <br
        />
        <br />Require authentication to IoT service management consoles. Provision unique
        identities for each operator and administrator with access to the management
        console.
        <br />
        <br />Provision unique identity for each system with access to the management
        system&apos;s API.
        <br />
        <br />Use authentication best practices for management console and API login.
        <br
        />
        <br />Limit network access to the management console and APIs by source IP addresses
        and/or device authentication.
        <br />
        <br />Log and check all administrative activities through the management console
        and APIs.
        <br />
        <br />Protect the computers used to remotely access your management console
        or APIs from malware and other threats.
        <br />
        <br />Implement a secure staging system for Over-The-Air (OTA) updates in order
        to protect from intrusion and malicious logic. Apply integrity controls
        to files prior to transmitting them to edge devices.</td>
      <td style="text-align:left"><b>I3 Insecure Ecosystem Interfaces</b>
        <br />
        <br /><b>I4 Lack of Secure Update Mechanism</b>
        <br />
        <br /><b>I7 Insecure Data Transfer and Storage</b>
        <br />
        <br /><b>I8 Lack of Device Management</b>
        <br />
        <br />
        <br />
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>COM-01</b>
        <br /><b>COM-02</b>
        <br /><b>COM-03</b>
        <br /><b>COM-04</b>
        <br /><b>COM-05</b>
        <br /><b>COM-06</b>
        <br /><b>COM-07</b>
        <br /><b>COM-08</b>
        <br /><b>COM-09</b>
        <br /><b>COM-10</b>
      </td>
      <td style="text-align:left">Define authorized MQTT topics. Create and enforce an access control list
        within the broker to restrict IoT devices from publishing content or subscribing
        to unauthorized message topics.
        <br />
        <br />Ensure all MQTT messages that include a password in the password field
        are encrypted using TLS.
        <br />
        <br />Use certificates to authenticate MQTT transactions instead of the native
        username/password capability.
        <br />
        <br />Consider throttling traffic to MQTT server on both global and per-client
        basis.
        <br />
        <br />Route MQTT traffic through a firewall.
        <br />
        <br />Reduce the maximum MQTT message size to limit an attacker&#x2019;s ability
        to overload the system by sending large messages.
        <br />
        <br />Install MQTT brokers only on hardened OS with secure access.
        <br />
        <br />Encrypt all TCP-based communications (e.g. REST, MQTT, AMQP) between system
        components using X.509-authenticated (<a href="https://tools.ietf.org/html/rfc7525">https://tools.ietf.org/html/rfc7525</a>)
        Transport Layer Security (TLS).
        <br />
        <br />Encrypt all UDP-based communications (e.g. Constrained Application Protocol,CoAP)
        between system components using the Datagram Transport Layer Security (DTLS)
        protocol specified in IETF RFC 7525 or newer standards.
        <br />
        <br />Encrypt all wireless communications in your IoT system.</td>
      <td style="text-align:left"><b>I7 Insecure Data Transfer and Storage</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>DAT-01</b>
        <br /><b>DAT-02</b>
        <br /><b>DAT-03</b>
        <br /><b>DAT-04</b>
      </td>
      <td style="text-align:left">Document data collected, processed, and stored within your IoT system.
        Classify that data based on data type and value (criticality to the organization
        and sensitivity). Tag data with metadata that can be used to identify types
        of data in your system.
        <br />
        <br />Implement data security controls based on the classification of each data
        type.
        <br />
        <br />Catalog internal and third party data sources. Enforce authentication
        on all data hosted within the IoT system. Track the lineage of data throughout
        the system as data is cleaned, reduced, modified, and aggregated. When
        creating these procedures, test and demonstrate the ability of your security
        protocols to effectively pinpoint the source of data and any users or processes
        that have acted upon any data used within an automated IoT decision process.
        <br
        />
        <br />After cataloging data in an IoT system, identify any locations and systems
        that store the data, and apply Data-at-Rest encryption controls to those
        locations and systems. Monitor to ensure new systems and components are
        not implemented without having been evaluated for their security when storing
        sensitive information.</td>
      <td style="text-align:left"><b>I7 Insecure Data Transfer and Storage</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>RMT-01</b>
        <br /><b>RMT-02</b>
      </td>
      <td style="text-align:left">Establish service level agreements with suppliers. These agreements should
        include incident management support (including support during forensic
        investigations) and a timeline for both minimum vulnerability disclosure
        and patch updates.
        <br />
        <br />Establish policies and procedures for third party access and management
        of any leased IoT devices. This includes data that can be transmitted out
        of the organization (e.g. instrumentation data),authorized roles, and minimum
        access security requirements for management of the devices within your
        organization&#x2019;s networks. Enforce these controls and monitor for
        abuse.</td>
      <td style="text-align:left"><b>N/A</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>CRD-01</b>
        <br /><b>CRD-02</b>
        <br /><b>CRD-03</b>
        <br /><b>CRD-04</b>
        <br /><b>CRD-05</b>
        <br /><b>CRD-06</b>
        <br /><b>CRD-07</b>
        <br /><b>CRD-08</b>
        <br /><b>CRD-09</b>
        <br /><b>CRD-10</b>
        <br /><b>CRD-11</b>
      </td>
      <td style="text-align:left">Establish secure key management processes for IoT systems that include,
        at a minimum, key generation; key derivation; key establishment/transport;
        key storage; key lifetimes; and key zeroization/destruction. Keys should
        be generated on devices whenever possible, assuming those devices have
        a sufficiently random source of entropy. Central key generation and distribution
        is acceptable if secure transport mechanisms are used to deliver key material
        (including out-of-band provisioning).
        <br />
        <br />Establish policy to ensure private keys are never shared across multiple
        devices or groups. Incorporate forward-secrecy whenever possible for key
        derivations (e.g. do not use static mechanisms). Keys should always be
        stored in a secure element (software or hardware) capable of restricting
        access to keys by unauthorized actors. Keys should be limited in lifetime
        when possible to no more than three years and ideally only one year. Use
        automated mechanisms for key updates (e.g. rotation or derivation).
        <br
        />
        <br />Establish a specialized key management user group to configure key management
        securely for your IoT devices and services.
        <br />
        <br />Establish a process for securely bootstrapping IoT devices onto your networks.
        Give preference to IoT devices capable of zero-touch provisioning, as these
        devices are pre-loaded with manufacturer credentials embedded in the hardware.
        Zero-touch provisioning requires a trusted, out-of-band process for loading
        serial numbers and public keys of devices to be provisioned. If zero-touch
        provisioning is unavailable, set up a trusted facility to register device
        serial numbers and preload identities/keys/certificates into the device
        prior to fielding on the network. In all cases, encrypt all account registration
        and update commands.
        <br />
        <br />Audit and identify devices that contain default passwords and change those
        passwords immediately upon deploying (preferably before connecting to a
        network). Identify devices that share passwords with other devices and
        change those passwords immediately. Identify devices that share remote
        access keys and update those devices immediately with unique credentials
        per device
        <br />
        <br />Whenever possible, given the amount of IoT devices that populate networks,
        it is preferable to use certificates instead of passwords for remote access
        of IoT devices. as passwords become difficult to manage as quantities of
        devices increase. If passwords are used to access IoT devices remotely,
        then update those passwords at least once a year. When possible, implement
        mechanisms to update those passwords automatically.
        <br />
        <br />Establish a process and acquire technology to manage the secure update
        of device certificates and trust anchors. Opt for automated update capabililities
        when possible. Restrict access for updating device trust anchors to authorized
        administrators.
        <br />
        <br />Establish certificate management policies. Define minimum requirements
        for validation of device identities (enrollment) prior to certificate provisioning.
        Device identify validation should be based on (a) in-person review, or
        (b) automated provisioning based on established key material (e.g. by manufacturer).
        <br
        />
        <br />Establish operational certificate lifetimes of no more than three years.
        Manufacturers may embed device identity certificates with no expiration,
        but these certificates should only be used to establish short-term operational
        certificates.
        <br />
        <br />Establish automated certificate processes to include renewing certificates.
        <br
        />
        <br />Establish a process for certificate revocation that includes required
        reporting channels, investigation methods, and authorities who can approve/disapprove
        placement on the revocation list.</td>
      <td style="text-align:left"><b>I1 Weak, Guessable, or Hardcoded Passwords</b>
        <br />
        <br /><b>I8 Lack of Device Management</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>EOL-01</b>
      </td>
      <td style="text-align:left">Define end-of-life procedures for IoT system hardware. For any hardware
        storing sensitive information, the procedure should be to dispose of the
        hardware securely and to maintain an audit log of the disposal process,
        including any individual that participates in the process.</td>
      <td style="text-align:left"><b>I8 Lack of Device Management</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>UPD-01</b>
        <br /><b>UPD-02</b>
        <br /><b>UPD-03</b>
        <br /><b>UPD-04</b>
        <br /><b>UPD-05</b>
        <br /><b>UPD-06</b>
      </td>
      <td style="text-align:left">Establish a configuration control board (CCB) to vet modifications/changes
        to IoT systems. The CCB should define processes for updates, which should
        include testing (functional, security, interoperability) of all updates
        prior to fielding.
        <br />Implement a test network that closely mirrors your IoT production environment.
        Test all updates/patches on the test network prior to fielding in production.
        <br
        />Define and follow a quality change control and testing process (e.g. ITIL
        Service Management) with established baselines, testing, and release standards
        that focus on system availability, confidentiality, and integrity of systems
        and services.
        <br />Perform static and dynamic security analysis scans on all third party
        code. Use software composition analysis tools to identify components with
        known vulnerabilities (e.g. OWASP dependency check).
        <br />Store integrity-protected firmware images of all IoT devices. Establish
        processes to restore IoT devices that are confirmed or suspected to have
        been compromised or corrupted. Test update processes at least annually
        across your different device types.
        <br />Configure all IoT devices to validate the software signature on firmware
        prior to updating. Monitor device audit logs to identify signature validation
        failures.Investigate all failures to identify root causes.</td>
      <td style="text-align:left"><b>I4 Lack of Secure Update Mechanism</b>
        <br />
        <br /><b>I5 Use of Insecure or Outdated Components</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>TRN-01</b>
        <br /><b>TRN-02</b>
      </td>
      <td style="text-align:left">&quot;Establish a security training program for IoT administrators. Include
        information on all of the following: allowable use policies, IoT assets
        used within the organization, procedures for bootstrapping trust in IoT
        devices, monitoring the security posture of IoT systems, approved processes
        for securely administrating IoT devices, and incident response procedures.
        <br
        />
        <br />Require that IoT system administrators take this training annually.&quot;
        <br
        />&quot;Establish a user security training program. The training program
        should focus on making all personnel aware of their roles and responsibilities
        in maintaining awareness and compliance with established policies and procedures.
        This includes applicable legal, statutory, and regulatory compliance obligations.
        Training should also focus on maintaining a safe and secure working environment,
        including policies and procedures related to the use of employee-owned
        IoT devices on the corporate network (e.g., smart TVs, wearables, etc.).
        Training should include information about the risks and privacy impact
        associated with IoT devices. If applicable, provide information on procedures
        for interfacing with corporate IoT devices.
        <br />
        <br />Require that all users of IoT systems take this training annually.&quot;</td>
      <td
      style="text-align:left"><b>N/A</b>
        </td>
    </tr>
  </tbody>
</table>
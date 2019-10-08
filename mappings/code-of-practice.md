# Code of Practice for Consumer IoT Security

<table>
  <thead>
    <tr>
      <th style="text-align:left"><a href="https://www.gov.uk/government/publications/code-of-practice-for-consumer-iot-security">Code of Practice for Consumer IoT Security</a>
      </th>
      <th style="text-align:left"><b>Description</b>
      </th>
      <th style="text-align:left">&lt;b&gt;&lt;/b&gt;<a href="https://www.owasp.org/images/1/1c/OWASP-IoT-Top-10-2018-final.pdf"><b>OWASP IoT Top 10 Mapping</b></a>&lt;b&gt;&lt;/b&gt;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>1. No default passwords</b>
      </td>
      <td style="text-align:left">All IoT device passwords shall be unique and not resettable to any universal
        factory default value</td>
      <td style="text-align:left"><b>I1 Weak, Guessable, or Hardcoded Passwords</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>2. Implement a vulnerability disclosure policy</b>
      </td>
      <td style="text-align:left">All companies that provide internet-connected devices and services shall
        provide a public point of contact as part of a vulnerability disclosure
        policy in order that security researchers and others are able to report
        issues. Disclosed vulnerabilities should be acted on in a timely manner.</td>
      <td
      style="text-align:left"><b>N/A</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>3. Keep software updated</b>
      </td>
      <td style="text-align:left">Software components in internet-connected devices should be securely updateable.
        Updates shall be timely and should not impact on the functioning of the
        device. An end-of-life policy shall be published for end-point devices
        which explicitly states the minimum length of time for which a device will
        receive software updates and the reasons for the length of the support
        period. The need for each update should be made clear to consumers and
        an update should be easy to implement. For constrained devices that cannot
        physically be updated, the product should be isolatable and replaceable.</td>
      <td
      style="text-align:left"><b>I4 Lack of Secure Update Mechanism</b>
        <br />
        <br /><b>I8 Lack of Device Management</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>4. Securely store credentials and security-sensitive data</b>
      </td>
      <td style="text-align:left">Any credentials shall be stored securely within services and on devices.
        Hard-coded credentials in device software are not acceptable.</td>
      <td style="text-align:left">
        <p><b>I1 Weak, Guessable, or Hardcoded Passwords</b>
        </p>
        <p>&lt;b&gt;&lt;/b&gt;</p>
        <p><b>I7 Insecure Data Transfer and Storage</b>
        </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>5. Communicate securely</b>
      </td>
      <td style="text-align:left">Security-sensitive data, including any remote management and control,
        should be encrypted in transit, appropriate to the properties of the technology
        and usage. All keys should be managed securely.</td>
      <td style="text-align:left"><b>I3 Insecure Ecosystem Interfaces</b>
        <br />
        <br /><b>I7 Insecure Data Transfer and Storage</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>6. Minimise exposed attack surfaces</b>
      </td>
      <td style="text-align:left">All devices and services should operate on the &#x2018;principle of least
        privilege&#x2019;; unused ports should be closed, hardware should not unnecessarily
        expose access, services should not be available if they are not used and
        code should be minimised to the functionality necessary for the service
        to operate. Software should run with appropriate privileges, taking account
        of both security and functionality.</td>
      <td style="text-align:left"><b>I2 Insecure Network Services</b>
        <br />
        <br /><b>I5 Use of Insecure or Outdated Components</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>7. Ensure software integrity</b>
      </td>
      <td style="text-align:left">Software on IoT devices should be verified using secure boot mechanisms.
        If an unauthorised change is detected, the device should alert the consumer/administrator
        to an issue and should not connect to wider networks than those necessary
        to perform the alerting function.</td>
      <td style="text-align:left"><b>I9 Insecure Default Settings</b>
        <br />
        <br /><b>I10 Lack of Physical Hardening</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>8. Ensure that personal data is protected</b>
      </td>
      <td style="text-align:left">Where devices and/or services process personal data, they shall do so
        in accordance with applicable data protection law, such as the General
        Data Protection Regulation (GDPR) and the Data Protection Act 2018. Device
        manufacturers and IoT service providers shall provide consumers with clear
        and transparent information about how their data is being used, by whom,
        and for what purposes, for each device and service. This also applies to
        any third parties that may be involved (including advertisers). Where personal
        data is processed on the basis of consumers&#x2019; consent, this shall
        be validly and lawfully obtained, with those consumers being given the
        opportunity to withdraw it at any time.</td>
      <td style="text-align:left"><b>I6 Insufficient Privacy Protection</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>9. Make systems resilient to outages</b>
      </td>
      <td style="text-align:left">Resilience should be built in to IoT devices and services where required
        by their usage or by other relying systems, taking into account the possibility
        of outages of data networks and power. As far as reasonably possible, IoT
        services should remain operating and locally functional in the case of
        a loss of network and should recover cleanly in the case of restoration
        of a loss of power. Devices should be able to return to a network in a
        sensible state and in an orderly fashion, rather than in a massive scale
        reconnect.</td>
      <td style="text-align:left"><b>I8 Lack of Device Management</b>
        <br />
        <br /><b>I9 Insecure Default Settings</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>10. Monitor system telemetry data</b>
      </td>
      <td style="text-align:left">If telemetry data is collected from IoT devices and services, such as
        usage and measurement data, it should be monitored for security anomalies.</td>
      <td
      style="text-align:left"><b>N/A</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>11. Make it easy for consumers to delete personal data</b>
      </td>
      <td style="text-align:left">Devices and services should be configured such that personal data can
        easily be removed from them when there is a transfer of ownership, when
        the consumer wishes to delete it and/or when the consumer wishes to dispose
        of the device. Consumers should be given clear instructions on how to delete
        their personal data.</td>
      <td style="text-align:left"><b>I6 Insufficient Privacy Protection</b>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>12. Make installation and maintenance of devices easy</b>
      </td>
      <td style="text-align:left">Installation and maintenance of IoT devices should employ minimal steps
        and should follow security best practice on usability. Consumers should
        also be provided with guidance on how to securely set up their device.</td>
      <td
      style="text-align:left"><b>I8 Lack of Device Management</b>
        <br />
        <br /><b>I9 Insecure Default Settings</b>
        </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>13. Validate input data</b>
      </td>
      <td style="text-align:left">Data input via user interfaces and transferred via application programming
        interfaces (APIs) or between networks in services and devices shall be
        validated.</td>
      <td style="text-align:left"><b>I3 Insecure Ecosystem Interfaces</b>
      </td>
    </tr>
  </tbody>
</table>
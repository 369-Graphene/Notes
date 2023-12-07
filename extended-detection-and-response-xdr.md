# Extended Detection & Response (XDR)

## Detection of Threat <a href="#detection-of-threat" id="detection-of-threat"></a>

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/introduction-microsoft-365-threat-protection/media/compromised-endpoint.png" alt=""><figcaption></figcaption></figure>

* A compromised endpoint is a device that has been infected with malware or otherwise compromised.
* This can happen through a variety of vectors, such as phishing emails, malicious USB drives, or software vulnerabilities.
* Once a device is compromised, attackers can use it to steal data, launch attacks against other devices, or disrupt operations.
* Microsoft Defender helps to protect against compromised endpoints by detecting and responding to threats.
* Microsoft Defender also provides tools to help organizations remediate compromised devices.

## Remediation <a href="#remediation" id="remediation"></a>

MDE (Microsoft Defender) remediates threat – either via automated remediation, security analyst approval of automated remediation, or analyst manual investigation of threat. MDE also remediates this threat across your enterprise and across our Microsoft MDE customers by adding information on this attack to Microsoft Threat Intelligence system

## Share Intelligence and Restore Access <a href="#share-intelligence-and-restore-access" id="share-intelligence-and-restore-access"></a>

Restore Access – Once the infected devices have been remediated, MDE signals Intune to change the device risk status and Entra ID Conditional Access then allows access to enterprise resources (more on the next slide). Remediate Threat Variants in MDO (Microsoft Defender for Office 365) and others – The threat signals in Microsoft Threat intelligence are used by Microsoft tools securing other parts of your organization’s attack surface. MDO and Microsoft Defender for Cloud use the signals to detect and remediate threats in email, office collaboration, Azure, and more.

## from the previous graphic when the user’s device was still compromised <a href="#from-the-previous-graphic-when-the-users-device-was-still-compromised" id="from-the-previous-graphic-when-the-users-device-was-still-compromised"></a>

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/introduction-microsoft-365-threat-protection/media/suspend-access-compromise.png" alt=""><figcaption></figcaption></figure>

* When an endpoint is compromised, it can be used by attackers to steal data, launch attacks against other devices, or disrupt operations.
* To mitigate these risks, it is important to suspend user access to the endpoint until it can be cleaned.
* This can be done by using a security solution such as Microsoft Defender for Endpoints.

**Steps to suspend access during compromise:**

1. Identify the compromised endpoint.
2. Isolate the endpoint from the network.
3. Suspend user access to the endpoint.
4. Clean the endpoint.
5. Restore user access to the endpoint.

**Benefits of suspending access during compromise:**

* Reduces the risk of attackers stealing data or launching attacks against other devices.
* Prevents users from accidentally spreading the malware.
* Gives security teams time to investigate and clean the endpoint.

**Example:**

A company is using Microsoft Defender for Endpoints to protect its network. One day, Microsoft Defender for Endpoints detects that a user's endpoint has been compromised with malware. The security team immediately isolates the endpoint from the network and suspends user access. The security team then investigates the compromise and cleans the endpoint. Once the endpoint is clean, the security team restores user access.

By suspending access during compromise, the company was able to prevent the attackers from stealing data or launching attacks against other devices. The company was also able to prevent the malware from spreading to other endpoints on the network.

## Access Restricted <a href="#access-restricted" id="access-restricted"></a>

* Conditional Access relies on Microsoft Defender for Endpoint (MDE) to assess device risk.
* MDE notifies Intune about any risk detected on a device.
* Intune then updates the device's compliance status in Entra ID.
* If a device is non-compliant, the user's access to corporate resources is restricted.
* This restriction applies to both new resource requests and ongoing access to resources that require continuous access evaluation (CAE).
* Users will still be able to access general internet resources like YouTube and Wikipedia, but not corporate resources.

## Access Restored <a href="#access-restored" id="access-restored"></a>

**Remediation and Access Restoration:**

* After threat removal, MDE updates Entra ID through Intune.
* Conditional Access then reinstates user access to corporate resources.

**2. Risk Mitigation:**

* Quick access denial for compromised devices protects corporate resources.
* Minimizes risk of attackers accessing sensitive information.

**3. Productivity Optimization:**

* Fast access restoration minimizes disruption to user workflows.
* Balances security with minimal impact on business processes.

**Remember:**

* MDE plays a crucial role in mitigating risk and restoring user access.
* Quick response minimizes the impact on users and protects the organization.

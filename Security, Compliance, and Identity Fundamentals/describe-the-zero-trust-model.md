# Describe the Zero Trust model

Zero Trust in a simplified manner:

1. **No implicit trust:** Zero Trust assumes that no area or device within a network is inherently secure, regardless of its location.
2. **Verify everything:** All users, devices, and applications attempting to connect to the network should be verified and authenticated thoroughly, regardless of their location or whether they're within the corporate firewall.
3. **Enhanced security:** Traditional security methods relying on perimeter defenses (like firewalls) are considered insufficient. Zero Trust strengthens security by verifying and validating every access attempt.
4. **Multi-factor authentication:** Instead of relying solely on passwords, Zero Trust employs multi-factor authentication, adding extra layers of security to confirm the user's identity.
5. **Granular access controls:** Rather than granting broad access to resources, Zero Trust limits access to specific applications or data based on the principle of least privilege. Users get access only to what they need for their roles.
6. **Adaptable security approach:** Zero Trust acknowledges the evolving nature of threats and doesn't assume that any part of the network is inherently safe. It continuously evaluates and adapts security measures to minimize risks.

### Zero Trust guiding principles <a href="#zero-trust-guiding-principles" id="zero-trust-guiding-principles"></a>

Three principles of the Zero Trust model:

1. **Verify Explicitly:**
   * Always confirm and allow access based on multiple factors like user identity, location, device, service, data classification, and unusual activities.
   * Authentication and authorization are based on various data points to ensure security.
2. **Least Privileged Access:**
   * Limit the access of users to the bare minimum necessary for their tasks (Just-in-Time/Just-Enough Access).
   * Use risk-based adaptive policies and data protection measures to safeguard both data and productivity.
3. **Assume Breach:**
   * Segment and restrict access based on network, user, device, and application to minimize potential damage.
   * Employ encryption methods to protect data and employ analytics to identify threats and enhance overall security.

These principles collectively ensure a proactive security approach, where trust is not automatically given but continuously verified and limited to the essentials, while always assuming that potential breaches may occur.

### Six foundational pillars <a href="#six-foundational-pillars" id="six-foundational-pillars"></a>

### &#x20;Points of the Zero Trust Model:

**1. Verified Identities:**

* Everyone (users, devices, services) must be verified before accessing resources.
* Strong authentication (e.g., multi-factor) and least privilege access principles are crucial.

**2. Secure Devices:**

* Devices are vulnerable attack surfaces due to data flow.
* Monitoring device health and compliance strengthens security.

**3. Managed Applications:**

* Track and manage all applications used (including "Shadow IT").
* Control application permissions and access.

**4. Protected Data:**

* Classify, label, and encrypt data based on its sensitivity.
* Ensure data safety even outside organizational control.

**5. Secure Infrastructure:**

* Assess infrastructure (on-premises and cloud) for version, configuration, and JIT access.
* Use telemetry to detect threats and anomalies, allowing for automated response and protection.

**6. Segmented Networks:**

* Segment networks with deeper in-network "micro segmentation."
* Employ real-time threat protection, end-to-end encryption, monitoring, and analytics.

**Remember:** All these elements work together in the Zero Trust model to achieve end-to-end security.

<figure><img src="https://learn.microsoft.com/en-us/training/wwl-sci/describe-security-concepts-methodologies/media/2-zero-trust-pillars-v2.png" alt=""><figcaption></figcaption></figure>

A security strategy that employs the three principles of the Zero Trust model across the six foundational pillars helps companies deliver and enforce security across their organization.

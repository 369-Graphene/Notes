# Describe the shared responsibility model

1. **Responsibility Allocation:**
   * **On-Premises Environment:** In traditional on-premises setups, the entire responsibility for security and compliance lies with the organization itself.
   * **Cloud-Based Services:** With cloud services, responsibility is shared between the cloud provider and the customer.
2. **Identifying Security Tasks:**
   * **SaaS:** For Software as a Service, the cloud provider generally manages security of the application itself, but customers are responsible for securing the data they input into the software.
   * **PaaS:** Platform as a Service providers handle the security of the platform infrastructure, while customers are accountable for securing the applications and data they build on that platform.
   * **IaaS:** With Infrastructure as a Service, the cloud provider manages the infrastructure's security, such as storage and networking, while customers are responsible for securing their applications, data, operating systems, and configurations.
   * **On-Premises:** In this scenario, the entire security and compliance responsibility rests solely on the organization.
3. **Clarity in Responsibilities:**
   * The shared responsibility model helps in defining and understanding which security tasks are handled by the cloud provider and which are the customer's responsibility.
   * Responsibilities shift as organizations transition to the cloud, transferring some security obligations to the cloud provider while retaining others within the customer organization.

The following diagram illustrates the areas of responsibility between the customer and the cloud provider, according to where data is held.

<figure><img src=".gitbook/assets/3-shared-responsibility-model.png" alt=""><figcaption></figcaption></figure>

The responsibilities of the customer organization (you) and the cloud provider across different deployment types (on-premises, IaaS, PaaS, and SaaS) in simple points:

**On-Premises Datacenters:**

* **Customer Responsibility:**
  * Entire physical security of the data center.
  * Encryption of sensitive data.
  * Managing all components from hardware to software.
* **Cloud Provider Responsibility:**
  * None, as this infrastructure is maintained and managed entirely by the customer organization.

**Infrastructure as a Service (IaaS):**

* **Customer Responsibility:**
  * Software components, including operating systems, network controls, applications, and data protection on the cloud provider's infrastructure.
  * Security measures for data and applications.
* **Cloud Provider Responsibility:**
  * Physical components such as hardware, network, and data center security.
  * Providing the computing infrastructure.

**Platform as a Service (PaaS):**

* **Customer Responsibility:**
  * Applications and data.
  * Utilizing the environment provided for building, testing, and deploying applications without managing the underlying infrastructure.
  * Data security and application management.
* **Cloud Provider Responsibility:**
  * Managing the hardware and operating systems underlying the PaaS environment.

**Software as a Service (SaaS):**

* **Customer Responsibility:**
  * Data, devices (like mobile and PCs), accounts, and identities.
  * Ensuring security related to data access and identities.
* **Cloud Provider Responsibility:**
  * Hosts and manages the software.
  * Handles everything except data, devices, accounts, and identities.

**General Responsibilities Across All Cloud Deployment Types:**

* **Customer Responsibility:**
  * Information and data security.
  * Managing devices such as mobiles, PCs, printers, etc.
  * Administering accounts and identities, ensuring their security.
* **Cloud Provider Responsibility:**
  * Varies according to the service model but generally encompasses infrastructure, platform, or software management.

This shared responsibility model ensures clarity in understanding the respective responsibilities of both the customer organization and the cloud provider across different cloud deployment types.

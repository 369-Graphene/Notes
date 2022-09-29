# Secure Controls Framework Overview and Instructions

## What is Secure Controls Framework Overview and Instructions?

The Secure Controls Framework™ (SCF) focuses on internal controls. These are the cybersecurity and privacy-related policies, standards, procedures, technologies, and associated processes that are designed to provide reasonable assurance that business objectives will be achieved and undesired events will be prevented, detected, and corrected. The concept is to address the broader People, Processes, Technology, and Data (PPTD) that are what controls fundamentally exist to govern. Using the SCF should be viewed as a long-term tool to not only help with compliance-related efforts but to ensure security and privacy principles are properly designed, implemented, and maintained. The SCF helps implement a holistic approach to protecting the Confidentiality, Integrity, Availability, and Safety (CIAS) of your data, systems, applications, and other processes. The SCF can be used to assist with strategic planning down to tactical needs that impact the people, processes, and technologies directly impacting your organization.

<figure><img src=".gitbook/assets/Screen Shot 2022-09-29 at 10.18.57 AM.png" alt=""><figcaption><p>Secure Controls Framework Overview &#x26; Instructions</p></figcaption></figure>

This “best practices” guide covers the following topics:&#x20;

* Level setting what the SCF is and what it is not;&#x20;
* Integrated Controls Management (ICM) approach to Governance, Risk Management & Compliance (GRC);&#x20;
* Leveraging the Security & Privacy Capability Maturity Model (SP-CMM);&#x20;
* Leveraging the Security & Privacy Risk Management Model (SP-RMM); and&#x20;
* Recommendations to tailor the control set for your needs to operationalize the SCF.&#x20;

The secure controls framework overview & instructions document is designed for cybersecurity & privacy practitioners to gain an understanding of how the SCF is intended to be used in their organization.

## Why should an organization use the SFC?

There is no sales pitch for using the SCF – it is a free resource so there is no financial incentive for us to make companies use it. For companies that have just one 1-2 compliance requirements, the SCF might be considered overkill for your needs. However, for companies that have 3+ compliance requirements (e.g., organization that has requirements to address ISO 27002, SOC 2, PCI DSS, and GDPR), then the SCF is a great tool to streamline the management of cybersecurity and privacy controls.&#x20;

In developing the SCF, we identified and analyzed over 100 statutory, regulatory and contractual frameworks. Through analyzing these thousands of legal, regulatory, and framework requirements, we identified commonalities and this allows several thousand unique controls to be addressed by the over 1,000 controls that make up the SCF. For instance, a requirement to maintain strong passwords is not unique, since it is required by dozens of laws, regulations, and frameworks. This allows one well-worded SCF control to address multiple requirements. This focus on simplicity and sustainability is key to the SCF since it can enable various teams to speak the same control language, even though they may have entirely different statutory, regulatory or contractual obligations that they are working towards.&#x20;

The SCF targets silos since siloed practices within any organization are inefficient and can lead to poor security, due to poor communications and incorrect assumptions.

#### The SCF is not:&#x20;

* A substitute for performing due diligence and due care steps to understand your specific compliance needs.
* A complete technology or documentation solution to address all your security & privacy needs (e.g., the policies, standards, procedures, and processes you need to have in place to be secure and compliant).
* Infallible or guaranteed to meet every compliance requirement your organization offers, since the controls are mapped based on expert-derived assessments to provide the control cross walking that relies on human expertise and that is not infallible.

## Understanding what it means to adopt the "Secure by Design" Principle

For an organization that just “does ISO”, it is easy to say, “We’re an ‘ISO shop’ and we exclusively use ISO 27001 cybersecurity principles for an Information Security Management System (ISMS)” and that would be routinely accepted as being adequate as a reasonable path to follow for many organizations. However, what about companies that have complex cybersecurity and compliance needs, such as a company that has to address SOC2, NIST SP 800-171, ISO 27002, CCPA, EU GDPR, PCI DSS, NY DFS, etc.? In these complex cases that involve multiple frameworks, ISO 27002 controls alone do not cut it. This is why it is important to understand what secure principles your organization is aligned with so that the controls it implements are appropriate to build secure and compliant processes. What works for one company or industry does not necessarily work for another, since requirements are unique to the organization.&#x20;

Most companies have requirements to document security and privacy processes but lack the knowledge and experience to undertake such documentation efforts. That means organizations are faced with either outsourcing the work to expensive consultants or they ignore the requirement and hoping they do not get in trouble for being non-compliant. In either situation, it is not a good place to be.

#### Secure practices are common expectations&#x20;

While the European Union General Data Protection Regulation _(EU GDPR)_ made headlines by requiring organizations to demonstrate security & privacy principles are both “by default and by design.” However, security & privacy engineering principles are not just limited to EU GDPR and are actually very common requirements, as shown below:

* NIST 800-53 - _SA-8_&#x20;
* NIST Cybersecurity Framework - _PR.IP-2_&#x20;
* ISO 27002 - _14.2.5 & 18.1.4_&#x20;
* Defense Federal Acquisition Regulations Supplement (DFARS) 252.204-7012 (NIST 800-171) - _3.13.1 & 3.13.2_&#x20;
* Federal Acquisition Regulations (FAR) 52.204-21 - _4_&#x20;
* National Industrial Security Program Operating Manual (NISPOM) - _8-302 & 8-311_&#x20;
* ISACA Trust Services Criteria (TSC) (SOC 2) - _CC3.2_&#x20;
* Generally Accepted Privacy Principles (GAPP) - _4.2.3, 6.2.2, 7.2.2 & 7.2.3_&#x20;
* New York State Department of Financial Service (DFS) - _23 NYCRR 500.08_&#x20;
* Payment Card Industry Data Protection Standard (PCI DSS) - _2.2_&#x20;
* Center for Internet Security Critical Security Controls (CIS CSC) - _1.2, 5.9, 6.2, 6.3, 6.4, 6.5, 7.1, 7.2, 7.3, 7.4, 7.5, 7.6, 7.7, 7.8, 8.6, 9.1, 9.2, 9.3, 9.4, 9.5, 9.6, 11.4, 11.5, 11.6, 11.7, 13.4, 13.5 & 16._

<figure><img src=".gitbook/assets/Screen Shot 2022-09-29 at 11.02.54 AM (1).png" alt=""><figcaption><p>Diagram of Security by Design &#x26; Privacy by Design</p></figcaption></figure>

## Security & Privacy by Design (S|P) Principles

The concept of building security and privacy into technology solutions both by default and by design is a basic expectation for businesses, regardless of the industry. The adoption of security and privacy principles is a crucial step in building a secure, audit-ready program.

The S|P establishes 32 common-sense principles to guide the development and oversight of a modern security and privacy program. Those 32 S|P principles are listed below:

| #  | SCF Domain                      | Identifier | Security & Privacy by Design (S\|P) Principle                                                                                                                                                                             | S\|P Principle Intent                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| -- | ------------------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | Security & Privacy Governance   | GOV        | Govern a documented, risk-based program that encompasses appropriate security and privacy principles to address all applicable statutory, regulatory and contractual obligations.                                         | Organizations specify the development of an organization’s security and privacy programs, including criteria to measure success, to ensure ongoing leadership engagement and risk management.                                                                                                                                                                                                                                                                         |
| 2  | Asset Management                | AST        | Manage all technology assets from purchase through disposition, both physical and virtual, to ensure secured use, regardless of the asset’s location.                                                                     | Organizations ensure technology assets are properly managed throughout the lifecycle of the asset, from procurement through disposal, ensuring only authorized devices are allowed to access the organization’s network and to protect the organization’s data that is stored, processed or transmitted on its assets.                                                                                                                                                |
| 4  | Capacity & Performance Planning | CAP        | Govern the current and future capacities and performance of technology assets.                                                                                                                                            | Organizations prevent avoidable business interruptions caused by capacity and performance limitations by proactively planning for growth and forecasting, as well as requiring both technology and business leadership to maintain situational awareness of current and future performance.                                                                                                                                                                           |
| 5  | Change Management               | CHG        | Govern change in a sustainable and ongoing manner that involves active participation from both technology and business stakeholders to ensure that only authorized changes occur.                                         | Organizations ensure both technology and business leadership proactively manage change. This includes the assessment, authorization and monitoring of technical changes across the enterprise so as to not impact production systems uptime, as well as allow easier troubleshooting of issues.                                                                                                                                                                       |
| 6  | Cloud Security                  | CLD        | Govern cloud instances as an extension of on-premise technologies with equal or greater security protections than the organization’s own internal controls.                                                               | Organizations govern the use of private and public cloud environments (e.g., IaaS, PaaS and SaaS) to holistically manage risks associated with third-party involvement and architectural decisions, as well as to ensure the portability of data to change cloud providers if needed.                                                                                                                                                                                 |
| 7  | Compliance                      | CPL        | Oversee the execution of cybersecurity and privacy controls to create appropriate evidence of due care and due diligence, demonstrating compliance with all applicable statutory, regulatory and contractual obligations. | Organizations ensure controls are in place to be aware of and comply with applicable statutory, regulatory and contractual compliance obligations, as well as internal company standards.                                                                                                                                                                                                                                                                             |
| 8  | Configuration Management        | CFG        | Govern the establishment and ongoing management of secure configurations for systems, applications, and services according to vendor-recommended and industry-recognized secure practices.                                | Organizations establish and maintain the integrity of systems. Without properly documented and implemented configuration management controls, security features can be inadvertently or deliberately omitted or rendered inoperable, allowing processing irregularities to occur or the execution of malicious code.                                                                                                                                                  |
| 9  | Continuous Monitoring           | MON        | Maintain situational awareness of security-related events through the centralized collection and analysis of event logs from systems, applications, and services.                                                         | Organizations establish and maintain ongoing situational awareness across the enterprise through the centralized collection and review of security-related event logs. Without comprehensive visibility into infrastructure, operating system, database, application, and other logs, the organization will have “blind spots” in its situational awareness that could lead to system compromise, data exfiltration, or unavailability of needed computing resources. |
| 10 | Cryptographic Protections       | CRY        | Utilize appropriate cryptographic solutions and industry-recognized key management practices to protect the confidentiality and integrity of sensitive data both at rest and in transit.                                  | Organizations ensure the confidentiality of the organization data by implementing appropriate cryptographic technologies to protect systems and data.                                                                                                                                                                                                                                                                                                                 |






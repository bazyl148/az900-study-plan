
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" alt="Azure Icon" width="130"/>

![mct-az900-yellow](https://img.shields.io/badge/mct-az900-yellow)![study_plan-red](https://img.shields.io/badge/study_plan-red)

## Study Plan : AZ-900 Microsoft Azure Fundamentals 
#### Prepare for this exam with this structured, activity-rich, and technically detailed plan.  
- Review the latest [skills measured](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#skills-measured-as-of-january-23-2024)
- Visit the official [learning path](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/?practice-assessment-type=certification)

---

<!--
![Cloud Icon](https://img.icons8.com/ios-filled/100/000000/cloud.png) -->

## Week 1: Cloud Concepts

<img src="https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/identity/images/azure-ad.png" alt="Integrate on-premises Active Directory domains with Microsoft Entra ID" width="550" />

**Official Modules:**
- [Describe cloud computing](https://learn.microsoft.com/en-us/training/modules/describe-cloud-compute/)
- [Describe the benefits of using cloud services](https://learn.microsoft.com/en-us/training/modules/describe-benefits-cloud-services/)
- [Describe cloud service types](https://learn.microsoft.com/en-us/training/modules/describe-cloud-service-types/)

**Technical Focus:**
- **Core Principles:** Scalability, elasticity, high availability, disaster recovery, fault tolerance.
- **Service Models:**  
  - IaaS (e.g., Azure Virtual Machines): User manages OS, middleware, runtime, data, and apps.
  - PaaS (e.g., Azure App Service): User manages apps and data; Azure manages the rest.
  - SaaS (e.g., Microsoft 365): Azure manages everything; user just uses the software.
- **Deployment Models:**  
  - Public Cloud (Azure), Private Cloud (on-premises), Hybrid Cloud (combination).

**Distinct Activities:**
- **Concept Mapping:** Diagram IaaS, PaaS, SaaS, and deployment models with real-world examples.
- **Benefits Debate:** Teams debate and present business migration scenarios. ie. Cost savings opportunities.
- **Azure Free Trial Setup:** Register for a [free Azure account](https://azure.microsoft.com/en-ca/Free), create a resource group, and explore the portal.
- **Scenario Practice:** Given a business need, select the best service and deployment model.
- **Quick Quiz:** Take the [Cloud Concepts Knowledge Check](https://learn.microsoft.com/training/modules/describe-cloud-compute/7-knowledge-check/)

---

## Week 2: Core Azure Services

<img src="https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/images/compute-choices.svg" alt="Choose an Azure compute service" width="550" />

**Official Modules:**
- [Describe core Azure architectural components](https://learn.microsoft.com/en-us/training/modules/describe-core-architectural-components-of-azure/)
- [Describe features and tools for managing and deploying Azure resources](https://learn.microsoft.com/en-us/training/modules/describe-features-tools-manage-deploy-azure-resources/)
- [Describe Azure compute and networking services](https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/)
- [Describe Azure storage services](https://learn.microsoft.com/en-us/training/modules/describe-azure-storage-services/)

**Technical Focus:**
- **Azure Regions & Availability Zones:** Understand physical and logical resource organization for resiliency.
- **Resource Groups:** Logical containers for managing resources.
- **Compute:**  
  - Azure Virtual Machines (VMs): Infrastructure for Windows/Linux workloads.
  - Azure App Service: Host web apps and APIs.
  - Azure Functions: Serverless compute.
  - Azure Kubernetes Service (AKS): Container orchestration.
- **Networking:**  
  - Virtual Network (VNet), Subnets, Network Security Groups (NSGs), VPN Gateway, ExpressRoute.
- **Storage:**  
  - Blob, File, Queue, Table Storage; redundancy options (LRS, GRS).
- **Databases:**  
  - Azure SQL Database, Cosmos DB, Azure Database for MySQL/PostgreSQL, Synapse Analytics.

**Distinct Activities:**
- **Exercise:** [Create a storage blob](https://learn.microsoft.com/en-ca/training/modules/describe-azure-storage-services/5-exercise-create-storage-blob/?ns-enrollment-type=learningpath&ns-enrollment-id=learn.wwl.azure-fundamentals-describe-azure-architecture-services)
- **Lab:** Deploy a Windows VM, configure NSG rules, and connect via RDP.
- **Scenario Challenge:** Design a multi-tier web app using App Service, Storage, and SQL Database.
- **CLI/Portal Comparison:** Create a resource using both Azure Portal and Azure CLI.
- **Video Recap:** Watch an official Azure overview video and summarize key takeaways.
- **Example VM setup:** [Multilayered protection for Azure virtual machine access](https://learn.microsoft.com/en-us/azure/architecture/solution-ideas/media/multilayered-protection-azure-vm-architecture-diagram.svg).

---

## Week 3: Security, Identity, and Governance

<img src="https://learn.microsoft.com/en-us/azure/architecture/guide/security/images/security-overview.png" alt="Security Architecture Design" width="550"/>

**Official Modules:**
- [Describe Azure identity services](https://learn.microsoft.com/en-us/training/modules/describe-azure-identity-access-security/)
- [Describe Azure governance features](https://learn.microsoft.com/en-us/training/modules/describe-features-tools-azure-for-governance-compliance/)
- [Describe Azure monitoring tools](https://learn.microsoft.com/en-us/training/modules/describe-monitoring-tools-azure/)

**Technical Focus:**
- **Azure Active Directory (Entra ID):** User, group, and application management; SSO; MFA.
- **Role-Based Access Control (RBAC):** Assign permissions at resource, group, or subscription level.
- **Security Tools:**  
  - Sentinel, Defender for Cloud, Azure Key Vault.
- **Governance:**  
  - Azure Policy, Blueprints, Resource Locks, Cost Management.
- **Compliance:**  
  - Understand GDPR, ISO, and Azure’s compliance offerings.

**Distinct Activities:**
- **Lab:** Configure RBAC for a resource group, create a custom role, and test access.
- **Exercise:** [Configure a resource lock](https://learn.microsoft.com/en-ca/training/modules/describe-features-tools-azure-for-governance-compliance/5-exercise-configure-resource-lock)
- **Policy Workshop:** Implement an “Allowed Locations” policy and audit compliance.
- **Security Simulation:** Respond to a simulated security incident using Defender for Cloud recommendations.
- **Trust Center Exploration:** Research a compliance certification in the [Microsoft Trust Center](https://servicetrust.microsoft.com/) and present findings.
- **Monitoring Demo:** Set up basic monitoring/alerts with Azure Monitor and Log Analytics.
- **Video course by John:** [Functionality of Conditional Access, MFA and SSO ](https://youtu.be/DFwERh9Xxk0?si=eX3BLgAgfH9J0WBm)

---

## Week 4: Cost Management & Exam Prep

<img src="https://learn.microsoft.com/en-us/azure/architecture/guide/multitenant/approaches/media/cost-management-allocation/tags.png" alt="Architectural approaches for cost management and allocation in a multitenant solution" width="550"/>

**Official Modules:**
- [Describe cost management in Azure](https://learn.microsoft.com/en-us/training/modules/describe-cost-management-azure/)
- [Describe features and tools in Azure for governance and compliance](https://learn.microsoft.com/en-us/training/modules/describe-features-tools-azure-for-governance-compliance/)
- [Take the Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#take-a-free-practice-assessment)

**Technical Focus:**
- **Pricing Models:** Pay-as-you-go, reserved instances, spot pricing.
- **Cost Management Tools:**  
  - Azure Pricing Calculator, TCO Calculator, Cost Analysis, Budgets, Alerts.
- **Service Level Agreements (SLA):** Interpret SLA terms and calculate composite SLAs.
- **Support Plans:** Compare Basic, Developer, Standard, and Professional Direct support.
- **Governance Tools:** Resource tagging, automation for cost control.

**Distinct Activities:**
- **Lab:** Use the [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/) to estimate costs for a real-world scenario.
- **Case Study:** Analyze a sample Azure bill and recommend optimizations (e.g., reserved instances, right-sizing).
- **Mock Exam:** Take a full-length [Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#take-a-free-practice-assessment) and review rationale for each answer.
- **Exam Strategy Workshop:** Practice scenario-based and drag-and-drop questions, discuss time management, and review common pitfalls.
- **Review Session:** Recap all domains, clarify doubts, and last-minute tips.

---

## Final Reviews

- Reasses your knowledge on the [Skills Measured](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#review-the-skills-measured-as-of-january-23-2024)
- Review the [Exam Policy](https://learn.microsoft.com/en-us/credentials/support/exam-duration-exam-experience)
- Try the [Exam Sandbox](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#exam-sandbox)
- Use the official [Practise Assessment](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/practice/assessment?assessment-type=practice&assessmentId=23&practice-assessment-type=certification)
- Schedule your exam via your [Microsoft Learn profile](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900#your-microsoft-learn-profile)

---

**References:**  
[Microsoft AZ-900 Study Guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900)

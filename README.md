<h1 align="center">Adnan Ahmed (Addy)</h1>
<h3 align="center">Senior Azure &amp; EUC Architect · Azure Virtual Desktop · Windows 365 · Citrix · Azure Landing Zones · AWS</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft-MCT-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="MCT">
  <img src="https://img.shields.io/badge/Azure-Solutions_Architect_Expert-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure Solutions Architect Expert">
  <img src="https://img.shields.io/badge/AZ--140-Azure_Virtual_Desktop-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="AZ-140">
  <img src="https://img.shields.io/badge/Citrix-CCP--V_%7C_CCA--V-452170?style=flat-square" alt="Citrix CCP-V and CCA-V">
  <img src="https://img.shields.io/badge/Nerdio-Certified_Engineer-00A4EF?style=flat-square" alt="Nerdio Certified Engineer">
  <a href="https://www.linkedin.com/in/adnan-a-siddiqui-768b5714"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center">
  <b>12+ years</b> · <b>18,000+ users</b> on enterprise virtual desktop platforms · <b>Citrix-to-AVD</b> and <b>Windows 365</b> modernization · <b>Azure landing zones</b> and hybrid Azure/AWS
</p>

---

I design, migrate, and operate enterprise end-user computing platforms. My work spans the full stack behind a virtual desktop: the Azure landing zone and hub-and-spoke network underneath it, identity and Zero Trust access in front of it, the Citrix, Azure Virtual Desktop, or Windows 365 platform itself, and the automation, monitoring, and disaster recovery that keep it running 24x7.

I have delivered this for cruise-line, airline, banking, and higher-education organisations, on-premises, in Azure, and in AWS. I now also build AI tooling for IT operations: MCP servers, RAG pipelines, and diagnostic agents for AVD and Citrix estates.

## Career highlights

- **Citrix-to-AVD migration:** led the end-to-end migration of **2,000+ users** from on-premises Citrix XenDesktop to Azure Virtual Desktop, covering assessment, landing zone design, pilot cohorts, and phased cutover, with **zero unplanned downtime**.
- **Enterprise Citrix at scale:** architected and scaled three major Citrix CVAD environments of **10,000+, 5,000+, and 4,000+ VDIs** across multiple production datacenters for airline, cruise-line, and banking users.
- **Multi-brand hybrid estate:** own a hybrid Citrix estate for **5,000+ users** across several cruise brands, spanning on-premises datacenters, Citrix Cloud on Azure, and Citrix Cloud on AWS, and lead its phased migration to Azure Virtual Desktop.
- **Hybrid Citrix DaaS on Azure and AWS:** designed resource locations in both clouds with redundant Cloud Connectors, giving users the same VDI and published-app experience on either cloud.
- **Windows 365 modernization:** provision and manage Cloud PCs end to end with Intune, Autopilot, compliance policies, and Conditional Access, and evaluated Windows 365 alongside AVD for brand-level rollout decisions.
- **Profile modernization:** moved FSLogix profiles from on-premises file servers to Azure Files and Azure NetApp Files, removing profile corruption and **cutting average logon time by over 40%**.
- **Mission-critical airline VDI:** built a **10,000-seat** active-active Citrix platform that delivered the airline reservation system and 100+ business applications, and extended it into **AWS** to onboard about **2,000 additional users**.
- **Operations leadership:** senior escalation point for 24x7 environments; managed and mentored offshore and vendor teams of up to **16 engineers**, reducing L3 escalations.

## Azure landing zone and infrastructure

- **Hub-and-spoke network** for migrated brands supporting **2,000+ AVD session hosts**: a central hub with shared firewall, DNS, and identity services, and per-business-unit spoke VNets aligned to Azure landing zone principles.
- **Hybrid connectivity** from on-premises datacenters to Azure over **ExpressRoute**, with AVD integrated into Entra ID, Intune, Autopilot, and Conditional Access.
- **Governance and security:** Azure Policy, RBAC, NSGs, Privileged Access Management, Zero Trust access, and TLS/SmartAccess hardening on Citrix ADC / NetScaler.
- **Business continuity:** DR planning and recovery testing across Citrix and AVD, aligned with Azure Backup and Azure Site Recovery.
- **FinOps and monitoring:** cloud cost governance with Apptio Cloudability; platform health with Dynatrace, Azure Monitor, and Log Analytics.
- **Infrastructure as code:** Terraform, Bicep/ARM, and PowerShell DSC through Git-based CI/CD; Nerdio Manager for Enterprise for autoscale, image lifecycle, and patching.

## What I work on

| Area | Details |
|---|---|
| **Azure Virtual Desktop** | Host pool design, FSLogix on Azure Files / Azure NetApp Files, MSIX App Attach, golden images, scaling plans, Nerdio Manager for Enterprise |
| **Windows 365** | Enterprise Cloud PCs, provisioning policies, Azure Network Connections, Intune and Autopilot, Conditional Access |
| **Citrix** | CVAD, Citrix Cloud / DaaS, PVS, MCS, StoreFront, WEM, Citrix ADC / NetScaler Gateway, Citrix Director |
| **Cloud platform** | Azure landing zones (CAF), hub-and-spoke, ExpressRoute, Entra ID, Azure Policy, AWS (FSx, CloudWatch, Citrix on AWS) |
| **Endpoint** | Intune, Autopilot, SCCM/MECM, application packaging, HP and Dell thin-client fleets |
| **Automation and AI** | Terraform, Bicep, PowerShell, Azure DevOps, GitHub Actions, MCP servers, RAG pipelines (Python, Qdrant), n8n |

## Featured projects

| Repository | What it is |
|---|---|
| [azure-virtual-desktop-enterprise-architecture](https://github.com/AddySidd27/azure-virtual-desktop-enterprise-architecture) | Enterprise AVD architecture with Terraform, hands-on labs, draw.io diagrams, runbooks, and interview preparation |
| [Azure_landing_zone](https://github.com/AddySidd27/Azure_landing_zone) | Build and operate an Azure Landing Zone with Terraform: CAF design areas, Corp/Online archetypes, policy model, and Day-2 operations |
| [Windows365-enterprise-engineering](https://github.com/AddySidd27/Windows365-enterprise-engineering) | Windows 365 Enterprise design and operations: provisioning, networking, Intune, security, and lifecycle labs |
| [terraform-azure-avd-autoscaling-cost-optimization](https://github.com/AddySidd27/terraform-azure-avd-autoscaling-cost-optimization) | Terraform for AVD scaling plans and cost optimisation |
| [Linux-essentials-for-cloud-engineer](https://github.com/AddySidd27/Linux-essentials-for-cloud-engineer) | Create, configure, operate, and troubleshoot Linux VMs on Azure, AWS, and Google Cloud, tested on real systems |

## Certifications

- Microsoft Certified Trainer (MCT)
- Microsoft Certified: Azure Solutions Architect Expert
- Microsoft Certified: Azure Virtual Desktop Specialty (AZ-140)
- Microsoft Certified: Azure Administrator Associate
- Citrix Certified Professional – Virtualization (CCP-V)
- Citrix Certified Associate – Virtualization (CCA-V)
- Citrix Virtual Apps and Desktops 7 on Citrix Cloud
- Nerdio Certified Engineer (NCE)

## Tech stack

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Citrix](https://img.shields.io/badge/Citrix-452170?style=flat-square)
![Windows 365](https://img.shields.io/badge/Windows_365-0078D4?style=flat-square&logo=windows&logoColor=white)
![Intune](https://img.shields.io/badge/Intune-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Connect

- LinkedIn: [adnan-a-siddiqui-768b5714](https://www.linkedin.com/in/adnan-a-siddiqui-768b5714)
- Based in the Dallas–Fort Worth area, Texas

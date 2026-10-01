# 👋 Hi,

**Infrastructure & Cloud Engineer** · Azure · Microsoft 365 · Entra ID · Intune · Terraform · Docker

I'm an IT contractor with 8+ years delivering infrastructure projects, cloud migrations and end-user computing for global law firms, a global travel management company, education and enterprise clients. I'm equally effective as the sole engineer on a high-visibility project or as part of a larger infrastructure team, and I take pride in delivering on time with minimal disruption to the business.

I'm now building on that experience with infrastructure as code, containers and cloud platforms. Everything here is a hands-on lab I have built, tested and written up myself.

---

### 🏆 Delivery highlights

| Project | Scale | What I did |
|---|---|---|
| Active Directory domain consolidation | 600+ users, UK, EU and India | Lead migration engineer, consolidating three domains into one using ADMT with no significant downtime. Designed the GPO structure and security group model for the new domain |
| Hybrid identity migration | Organisation-wide | Sole engineer on an Azure Cloud Sync project, updating Immutable IDs with PowerShell and validating sign-in end to end before cutover |
| GDPR data-residency remediation | 1,000+ SharePoint and OneDrive accounts | Relocated all affected accounts to the correct region, then designed an onboarding procedure as a preventative control to close the audit finding |
| Document management migration | 4,000+ users | Migrated a global law firm to iManage, including full UAT and QA within Citrix and KB articles for every issue found |
| Full estate rebuild after a malware attack | 700+ users, multi-site | Rebuilt Active Directory, Azure AD, Group Policy, ADFS and SSO from the ground up, redeployed every endpoint and introduced Intune |
| Security uplift | Organisation-wide | Remediated vulnerabilities with Tenable Nessus, hardened to CIS benchmarks and helped achieve Cyber Essentials Plus |

---

### 🧪 Hands-on labs

| Repository | What it shows |
|---|---|
| [docker-asset-register](https://github.com/iM-MQ/docker-asset-register) | A containerised two-tier web app (Flask and PostgreSQL) with Docker Compose, an internal-only database network, persistent storage, a non-root container and a GitHub Actions pipeline publishing images tagged by commit |
| [terraform-azure-labs](https://github.com/iM-MQ/terraform-azure-labs) | Five labs building Azure infrastructure as code: the Terraform workflow, segmented networking with NSGs, reusable modules with validation, remote state with locking and versioning, and a capstone deploying the Asset Register to Azure Container Apps with a managed PostgreSQL database |

The two projects connect. The image built by the Docker pipeline is the one deployed to Azure in [Terraform Lab 05](https://github.com/iM-MQ/terraform-azure-labs/tree/main/lab-05-capstone), pinned to a specific commit. Each lab includes the problems I hit and how I worked them out, not just the parts that went smoothly.

### 🚧 Currently working on

- Kubernetes on Azure (AKS), built with Terraform
- An Azure Landing Zone: management groups, Azure Policy and hub-and-spoke networking
- Rebuilding the Asset Register as a REST API with FastAPI, with automated tests in the pipeline

---

### 🔧 What I work with

| Area | Technologies |
|---|---|
| **Cloud & Identity** | Azure, Entra ID, Entra Connect, Azure Cloud Sync, Hybrid Azure AD Join, AVD, Conditional Access, ADFS, SSO, AWS (EC2, S3, VPC, IAM) |
| **Microsoft 365** | Exchange Online, SharePoint Online, Teams, OneDrive, Intune / Autopilot, E3 / E5 licensing |
| **Infrastructure** | Active Directory, GPO, ADMT, Windows Server, Hyper-V, VMware ESXi, DFSR, SCCM / MECM, Citrix |
| **Networking & Security** | TCP/IP, DNS, DHCP, VLANs, VPN, FortiGate, SonicWall, Palo Alto GlobalProtect, CrowdStrike, Tenable Nessus, BitLocker, LAPS, Cyber Essentials Plus |
| **Infrastructure as Code & DevOps** | Terraform (Azure, modules, remote state), Docker, Docker Compose, Azure Container Apps, Git, GitHub Actions, PowerShell |

### 🤝 How I work

- **Changes go through proper control.** I've presented and delivered changes through CAB, with risk, impact and rollback plans, and I apply the same thinking to `terraform plan`.
- **Test at every stage.** On migrations I test before moving users across. In my labs, I read every plan before applying and check anything I don't expect.
- **Write it down.** I document issues and fixes as I go, whether as KB articles on a migration or as the write-ups in these repositories.
- **Explain it plainly.** I'm comfortable translating technical work into plain language for stakeholders at every level.

---

### 🎓 Certifications

**Cisco**
- Cisco Certified Network Associate (CCNA) – Nov 2022

**Microsoft**
- Microsoft Certified: PL-900 Power Platform Fundamentals – Apr 2021
- Microsoft Certified: AI-900 Azure AI Fundamentals – Apr 2021
- Microsoft Certified: AZ-900 Azure Fundamentals – Apr 2021

**Amazon Web Services**
- AWS Certified Solutions Architect – Associate – Jun 2020

---

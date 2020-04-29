# Christopher J. Tarricone

194 Hebron Rd, Bolton, CT, 06043
Phone: 860-316-7617 E-Mail: chris@uconn.edu Web: http://www.linkedin.com/in/christarricone

## Skills

- **Project Management:** Long and short-term multi-phase projects for network implementations.
- **Customer/Client Interaction:** Able to take complex concepts and explain them to C-Level executives, Faculty and general staff
- **Directory Services:** Microsoft Active Directory, OpenLDAP, NDS, and NIS
- **Disaster Recovery:** Analysis, prioritization, planning and implementation.
- **VoIP:** SIP Based solutions from 3CX, Asterix, Cisco and Polycom.
- **SAN Design:** EMC VNXe, Dell EqualLogic, HP StorageWorks (MSA, P2000 & P4000/Left Hand) using SAS, NFS & iSCSI.
- **Virtualization:** VMware vSphere & ESXi, RHEV/XEN and Microsoft Hyper-V.
- **Programming:** C#, C++, Python, PHP, Java and PowerShell Scripting.
- **Microsoft Exchange:** Server versions 2003-2010, Exchange Clustering.
- **Microsoft SQL:** Server versions 2000-2018, SQL Server Clustering.
- **HP Networking:** ProCurve Switches and MSM Wireless solutions.
- **Cisco Networking:** Cisco UCS w/6200 Series FIs, Cisco IOS routing and ASA firewall configuration.
- **Windows Networking:** Server versions NT3.51-2018, Active Directory, DFS, DNS, WINS and Group Policies.
- **Linux:** OpenLDAP, NIS and AD integration, Extensive experience with Red Hat & Debian based distributions.
- **Apple:** Extensive Experience with Appletalk, OS9, OSX and Windows integration with Apple products. Additional experience with Linux Firewalls, Network Monitoring or Windows Server or workstation replacement.
- **IP Networking:** IPv4 subnetting, routing (RIP, OSPF and BGPv4) and VLAN setup and configuration.
- **UNIX:** SunOS / Solaris, BSD Firewalls, NAS and Networking Solutions.
- **Firewalls:** Management of Fortinet/Fortigate, Management of other vendors (Cisco, SonicWALL, WatchGuard, Linux, BSD). Professionally trained in Palo Alto firewall design and implementation.
- **Management:** Oversaw all technical staff at InCHIP.
- **Monitoring:** Extensive use of Splunk and Zabbix. Exposure to Nessus.

---

## Experience

### University Information Technology Services (ITS) / UConn

**Dates Worked:** 2017 - Present

Titles:
UCP10 - Computer Technical Support Consultant 4
Solutions Technologist

#### Responsibilities

- I interact between the ITS groups of Networking, Security, Storage & Virtualization, Server Systems and vendors and translate communications that help break down roadblocks.
- I administer OpenLDAP by deploying schema updates, ensuring patch compliance, and writing scripts that monitor the cluster as a whole.
- I have significant experience in scripting languages such as Ansible, BASH and PowerShell so I am a resource for providing scripted Automation of routine tasks.
- For period of time was the Interim Splunk administrator will the ITS Security team was being rebuilt. I have been slowly training Zach on most of the tasks as tickets come in requesting changes or adds. I also created how-to guides for many of these tasks.
- Providing technical assistance to the design and implementation of Object Storage

#### Major Projects

- **OpenLDAP:** I re-architected the design of OpenLDAP to be more resilient to failure and allow continued operation. In its current incarnation OpenLDAP stays online and available for authentication services, even when the entire Storrs campus is off-line. The entire build process is completely documented so that anyone with access to build VM’s and Stash would be able to restore the environment, even without Actifio.
- **CAS6:** I upgraded CAS to the current version. In RHEL 8, Red Hat dropped package support for Tomcat in favor of JBoss Enterprise Application Platform 7. This required a complete change in build process for the new version of CAS. This was done along with implementing Infobox Global Server Load Balancing (GSLB). GSLB allows students to access externally hosted services like HuskyCT even when Storrs is completely down. As with OpenLDAP the entire build process has been documented.
- **Shibboleth 3:** I am currently wrapping up our Shibboleth upgrade. Like with CAS, this will be a fully redundant design leveraging GSLB. As with OpenLDAP the entire build process has been documented. This latest version still runs Tomcat on RHEL 8. Since Red Hat has decided to discontinue packaging Tomcat, I wrote a script that checks in with Apache, downloads the product, validates SHA256 hashs and performs the upgrade.
- **SailPoint:** I rewrote a significant number of our current ID System extracts in C# for our eventual migration to the SailPoint ID System Framework. I also worked closely with the IAM team to help write many of the ingest rules to from the old ID System into SailPoint.
- **UCAutomate:** I wrote the automated system deployment in C# and Ansible that allows for Windows or Linux systems to be deployed quickly. The code interacts with the APIs of VMware, Satellite, and Infoblox and writes data to MS SQL and Ansible AWX.
- **Syslog:** Upgraded all of the syslog servers to RHEL8 and load-balanced them behind the NetScaler. Once the upgrades were complete, I also created a companion build guide.

---

### Institute for Collaboration on Health, Intervention, and Policy / UConn

**Dates Worked:** 2013 - 2017

Titles:
UCP10 – Computer Technical Support Consultant 4
Director of Information Technology at InCHIP
Director of CHIP Advanced Storage Solutions

#### Responsibilities

- Evaluate new eHealth/mHealth sensors and devices that are consistent with the goals and objectives of InCHIP is its researchers.
- Provide technical and administrative coordination and leadership for InCHIP's IT department.
- Resolve Complex software, hardware, network, systems integration and/or related IT problems, as they pertain to InCHIP's research projects and initiatives.
- Select, acquire and install new technology as needed to support InCHIP's research personnel especially in the areas of eHealth/mHealth sensors, services and software.
- Review, design and implement InCHIP’s technical policies and procedures with significant weight on efficiency and business continuity.
- Design, Implement and monitor data security protocols and access control mechanisms.
- Maintain InCHIP's VMware vSphere and Horizon View infrastructure.
- Maintain InCHIP's EqualLogic and EMC storage area networks.
- Maintain InCHIP’s active directory structure and provision accounts and security groups for affiliated Principle investigators and their staff.

#### Major Projects

- I migrated InCHIP from using disparate Dell Servers to the Cisco UCS platform. I was responsible for designing, setting up, testing and implementing the complete solution.
- We migrated away from Dell EqualLogic PS arrays to EMC’s VNXe series of storage. This combined with the UCS platform staged us for the upgrade from 3/4Gbit storage to 10Gbit storage.
- Upgraded the storage back end from multi-single Gb links to multi-10GB links.
- I designed and coded multiple web applications that leverage CAS/NetID. An example of one of these web-apps is our grant tracking program. We can tell, based on staff entry and grant holder feedback where we are in the grant approval process. Reports can be run on previous and current grants.

---

### Progressive Data Systems, Inc. / pds2k

**Dates Worked:** 1997-2013

Titles:
Partner
Technical Services Manager

#### Responsibilities:

- Evaluate client networks for physical, logical and procedural technology limitations and generate a report to be presented to executive management. These reports included risks, recommendations, estimated costs and time-lines.
- Developed a three phase business evaluation tool for helping companies evaluate their network, security profile/posture and readiness for common disasters.
- Implementation and management of long-term multi-phase projects. During my tenure our customers included a wide variety of education, health care, manufacturing and local government offices.
- Design, install and setup multi-carrier Wide Area IP Networks using MPLS, Frame-Relay, Cable, DSL, VPN and Point-To-Point technologies.
- Design & support Active Directory & group policies
- Design, setup and manage Lync, Exchange and SQL Server systems in single and clustered environments for high availability and disaster recovery.
- Design, specify, install and migrate clients to VMware virtualization. The virtualization platform allowed us to provide high availability and disaster recovery with a reduction in electrical and cooling costs and less hardware to maintain. At a single client we reduced the overall equipment to maintain by over 50% while still adding a fully redundant server facility.
- The virtualization solutions were powered using HP SANs using iSCSI and FC technologies.
- Design, setup and train clients on how to use 3CX VoIP PBX Systems. The VoIP phone systems we installed provided the latest Unified Communications platform for less than one half the cost of a traditional PBX system. This is done without any sacrifice to feature-sets or functionality.
- Maintain private computing clouds for pds2k.com’s hosted clients.
- Install and support clients firewall from Cisco, SonicWALL, Watchguard and various Linux distributions. Many of our clients that needed managed firewall services opted for the Linux based firewall solutions to avoid having to maintain yearly licensing and maintenance costs that are typically associated with traditional firewall solutions.
- Setup, install and maintain Red Hat, Centos & Fedora Core web and mail servers running various versions of Apache, MySQL & Q-Mail.
- Developed a national 56K dial-up program that would use a series of MySQL powered RADIUS servers. MySQL allowed for data to be quickly replicated across multiple locations preventing a service outage.

#### Major Projects:

- **The Bushnell:** We performed a series of reviews on their network capabilities, security posture and readiness, and disaster preparedness to ensure that their network was secure. They would accept credit card payments for tickets in multiple internet connected kiosks and POS Terminals that had some level of internet connectivity.
- **EDAC Aerospace:** They acquired a new company. We helped them migrate over 100 workstations and a dozen servers to their existing Active Directory. After completion of that project we helped them move from a local Exchange infrastructure to Microsoft Business Productivity Online Standard (MS BPOS), the predecessor to Office 365.
- **Pine Point School:** Our initial project with the school was to help them acquire a pair of file-servers for the business office and for the students. This required creating a full Identity Access program leveraging Active Directory. This was a ground-up program as nothing was in place. Additionally we were part of the design committe for their new Library & Technology Centre.
- **Community Prevention and Addiction Services (CPAS):** This company focused on providing drug and alcohol interventions for at risk individuals. We helped them prepare for their HIPAA audit and performed routing evaluations of their network, servers, workstation, and policies to ensure they maintained compliance.

---

### Education

**University of Connecticut**

- 1995-1996
- Studied in computer programming and electronic engineering

**Lyman Memorial High School**

- 1993-1995
- Became secondary network administrator for the school’s Novel network.
- Provided desktop and application support to teachers and students.
- Repaired and maintained the schools 75 workstations.

**St. Bernard’s High School**

- 1991-1993

# NSX Demos Organized by Use Case
This is a collection of curated, recent demos covering key NSX Use Cases.


## Table of Contents

* [Multi Cloud Networking](#multi-cloud-networking) (9)

* [Security](#security) (9)

* [Networking and Security for Cloud Native Apps](#Networking-and-Security-for-Cloud-Native-Apps) (3)

* [Automation](#automation) (3)

* [Cloud Scale Networking](#cloud-scale-networking) (1)

## Multi Cloud Networking
Title | Description | Link
---|---|---
NSX-T Federation Demo 1: Networking & Security | NSX-T offers the ability to manage and operate simply and centrally Network and Security services with NSX-T Federation. This is done with our new element: NSX-T Global Manager (GM). This first demo will drive you through GM UI where different stretched network and security are configured.| https://youtu.be/Dcx-0lvwvPs
NSX-T Federation Demo 2: Disaster Recovery |NSX-T offers the ability to manage and operate simply and centrally Network and Security services with NSX-T Federation. This is done with our new element: NSX-T Global Manager (GM). This second demo will drive you through Disaster Recovery (DR) use case where 1 Location is lost, and Network and Security services are simply recovered thanks to NSX-T.| https://youtu.be/kuVfCw1q5g8
VMware Cloud on AWS – Transit Connect Demo: SDDC to SDDC |The Transit Connect feature in VMware Cloud on AWS offers customers the ability to interconnect resources using a VMware managed Transit Gateway in a very simple and easy to use method. This first demonstration shows how to setup two SDDCs to use this feature. | https://youtu.be/UejYkwbTE9E
VVMware Cloud on AWS – Transit Connect Demo: SDDC to VPC |The Transit Connect feature in VMware Cloud on AWS offers customers the ability to interconnect resources using a VMware managed Transit Gateway in a very simple and easy to use method. This second demonstration shows how to setup a native AWS VPC to utilize this feature. | https://youtu.be/C9Ds9CL0yG8
VMwware Cloud on AWS – Multi Edge SDDC Demo |The Multi Edge SDDC feature in VMware Cloud on AWS empowers customers to scale their edge resources and redirect traffic with surgical precision. This demonstration reviews this capability and walks through the steps to deploy new edges. | https://youtu.be/5XStlDORqZk
Micro-segmentation of Horizon Cloud on Azure Desktops using NSX Cloud. | In this demo, learn how VMware NSX Cloud can be deployed to micro-segment virtual desktops that are deployed by VMware’s Horizon Cloud on Azure. The NSX micro-segmentation policy can control traffic between desktops within Azure VNET as well as traffic destined to on-prem. | https://youtu.be/FlTtflqZYo4
VMware NSX Cloud Demo: Single Micro-Segmentation Policy across Hybrid Cloud  |Learn how VMware NSX Cloud can help extend your security policies from on-prem to AWS and Azure. You will see how Security policies are defined based on Application requirements and are agnostic to the Cloud in which they are running in. | https://youtu.be/RsGQfpagHNQ 
AVS 2.0 Demo: Workload VMs Inbound Internet Access via Azure Application Gateway | AVS runs in an isolated environment within Azure. Workload VMs are not accessible from Internet. Azure Application Gateway enables users to provide inbound Internet access for AVS 2.0 workloads. This demo demonstrates this capability.| https://youtu.be/IeO822EMLPE
AVS 2.0 Demo: Workload VMs Inbound Internet Access via Destination NAT(DNAT) | AVS runs in an isolated environment within Azure. Workload VMs are not accessible from Internet. Destination NAT(DNAT) enables users to provide inbound Internet access for AVS 2.0 workloads. This demo demonstrates this capability.  | https://youtu.be/K1VSE0ylT9g

## Security
Title | Description | Link
---|---|---
How to Segment Your Data Center Using VMware NSX and vSphere 7 |Easily achieve data center segmentation with a few simple steps without changing any of the underlying physical network configurations with VMware NSX and vSphere 7. This step by step tutorial will allow you to achieve your goals of application and environment segmentation to prevent lateral movement in the data center | https://youtu.be/eFYXaejriIE
Network segmentation without networking changes or hairpinning  | Using the NSX Service-defined firewall, organizations can gain visibility into traffic and easily create network segmentation by defining them entirely in software — no need to change your network or hairpin traffic by deploying discrete appliances. This demo covers a phased approach enabling customers to quickly implement zone-based segmentation – for example between development and production – and then gradually deepen their security with application isolation, micro-segmentation and IDS/IPS over time. | https://youtu.be/1s00ZbsNXgA
VMware NSX-T Identity Firewall for VDI and RDSH | The NSX Service-Defined Firewall enables user-based or identity firewalling (IDFW). With IDFW, customers can create firewall rules based on active directory user groups to provide granular per-user access to applications. In this demo, we walk through a realistic scenario, and cover the configuration steps to implement user-based application-access policies. | https://youtu.be/94HSHjKqgxo
Preventing Lateral Movement with NSX IDS/IPS |The unique distributed architecture of the NSX Distributed IDS/IPS enables organizations to detect and prevent any stage of an attack against any workload regardless of network connectivity. Attackers spend most of their time on active attack phase, moving laterally after they have breached the perimeter.  In this demo, we walk through an attack scenario and cover how applying the NSX IDS/IPS can be done in just 3 steps without any network changes. | https://youtu.be/PIj-RGQTKsg
Consistent Security Policies across Locations with NSX-T Federation  |With Federation, NSX-T enables VMware customers to apply a security policy orchestration across locations or regions from a single Global Manager. In addition, NSX supports seamless migration of workloads between sites. This demo covers the creation of global and location-specific groups as well as infrastructure and environment policies enabling network-independent segmentation globally. We also showcase how a firewall policy moves with a workload as the workload moves between locations.  | https://youtu.be/rXhs42pdoE4
Secure Remote Workers with VMware NSX and Horizon  |Many organizations having shifted their business online with large numbers of employees working from home.  This new “work from anywhere and any device” reality illustrates why traditional security focused on the perimeter is not adequate.  In this session we will cover what the security challenges are that come with working from home and how VMware NSX provides simple and comprehensive protection for your Horizon VDI deployments.    | https://youtu.be/pLm6GzMaXMI
Security Field Day: Operationalizing East – West Security at Scale with NSX Firewall |VMware’s software-defined firewalling approach allows enterprises to easily operationalizing East-West security at scale and ensure threats are not able to spread laterally through the network. Enterprises can now buy and deploy VMware NSX Firewall as a standalone security product. No longer do you need to be an existing NSX customer to take advantage of our innovative software-based approach. There are no more excuses for why you can’t modernize your security strategy today. | https://youtu.be/4cyrBb5cle0
Security Field Day: Segmentation Made Easy: A Practical Demo | This session will walk you through a real-world example of how you can secure VMware vSphere workloads with NSX Firewall. This allows you to implement segmentation in your network with just a few simple steps, in a matter of minutes, and without making any changes to your existing environment. Don’t believe us? Watch the demo and finally achieve your goal of segmenting applications and prevent lateral movement within the data center. | https://youtu.be/gkg0vrWXCTg
Security Field Day: Level Up Threat Prevention Inside the Data Center | With the acquisition of Lastline, VMware further extended its capabilities for NSX Firewall to deliver VMware NSX Advanced Threat Prevention (ATP). This solution includes capabilities consisting of VMware NSX Distributed IDS/IPS and Network Sandboxing and Network Traffic Analysis (NTA/NDR). NSX Advanced Threat Prevention allows security teams to stop the spread of attacks that breach the perimeter. The IDS/IPS can detect network threats by combining industry-leading signature sets and protocol decoders, the network sandbox provides complete malware analysis of artifacts traversing your data center and network traffic analysis detects lateral threats and anomalies in the traffic flow between hops. | https://youtu.be/UWvbS1E2r9I

## Networking and Security for Cloud Native Apps
Title | Description | Link
---|---|---
Showcasing NSX-T and vSphere with Tanzu  | This demo covers deploying an app on vSphere with Kubernetes, both on a supervisor cluster and a Tanzu Kubernetes Guest Cluster, and how NSX provides networking services.| https://youtu.be/vwaT0583v6E
Showcase connectivity between standalone Antrea cluster and NSX-T  | This demo showcases the connectivity between an NSX-T infrastructure and a standard Kubernetes cluster with Antrea as the CNI. | https://youtu.be/0oVrOA38Ijk
Introduction to Antrea  |An introduction to Project Antrea | https://youtu.be/X9ks1HPyMDo

## Automation
Title | Description | Link
---|---|---
Automated NSX-T Upgrade using Ansible   | Automated upgrade of NSX-T using Ansible modules | https://youtu.be/j_qgjFYK6AY
vRealize Automation (vRA) and NSX-T Integration   | vRA and NSX-T Integration (VMworld 2020) Demo showing deploying a 3-Tier app using vRA and NSX-T. The blueprint used in the demo can be found here: https://github.com/vmware-samples/nsx-t/tree/master/vRA  | https://youtu.be/qjpWlqJo2WA
Deploy 3-Tier App using vSphere and NSX-T Terraform Providers | Deploy a 3-Tier app using vSphere Terraform Provider and NSX-T Terraform Provider  | https://youtu.be/M73Y_KXyFdM

## Cloud Scale Networking
Title | Description | Link
---|---|---
NSX-T and ECMP   | Everything you need to know about ECMP within NSX-T | https://youtu.be/XdSs-S2a5fc




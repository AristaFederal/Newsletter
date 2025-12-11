<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-74HMNYLH82"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-74HMNYLH82');

</script>

[![Image Placement][1]][2]
[1]: img/arista-federal-logo.png
[2]: http://www.aristafederal.com


# Welcome to the December 2025 Edition of the Arista Federal Newsletter!

Welcome to the December 2025 Edition of the Arista Federal Newsletter!
As we close out another impactful year, December gives us the perfect opportunity to reflect on the progress we’ve made together across the Federal and System Integrator community. From modernizing network architectures to advancing automation and strengthening security, your partnership has helped drive meaningful innovation across the missions we collectively support.
This season also brings a chance to pause and appreciate the collaboration, trust, and shared commitment that have defined 2025. Whether through deployments, briefings, workshops, or long-term planning, we’re grateful for the continued opportunity to work alongside you.

As we head into the holiday season and prepare for an exciting new year, the Arista Federal Team extends our warmest wishes to you and your families. May your holidays be safe, restful, and filled with connection and may 2026 bring new possibilities, new successes, and continued momentum for all of us.

Happy Holidays from **Arista Federal!**

In this month’s newsletter, you’ll find:

- **Unlocking a New Era for Enterprise Networking**
Arista Federal SEs Michael Reyes and Michael Ignoffo highlight how today’s IT environments demand far more from the network than simple connectivity. As organizations scale across data centers, campuses, and cloud environments, network teams are under increasing pressure to deliver availability, security, compliance, and agility all while managing fragmented tools and manual processes that simply can’t keep pace with modern demands.
- **Benefits of Replacing Legacy MPLS VPN Services with EVPN**

Arista Federal SE Jeff Colburn explains how Ethernet VPN (EVPN) has become the modern control plane of choice, one that not only replaces legacy MPLS VPN services, but delivers improved scalability, flexibility, and operational simplicity across data center, WAN, and campus environments. EVPN enables agencies and integrators to modernize their network architecture with an open, standards-based approach that supports today’s cloud-first and mission-critical demands.

This newsletter is for you and we welcome your feedback, ideas, and requests at fed@aristafederal.com.
Thank you for reading the Arista Federal Newsletter — your go-to source for the latest innovations, industry insights, and mission-focused networking solutions for Federal Agencies and System Integrators.



---

## **Arista Blog**

[![Image Placement][3]][4]
[3]: img/blog.png
[4]: https://blogs.arista.com/blog


---

## **Unlocking a New Era for Enterprise Networking**
By: Michael Reyes and Michael Ignoffo, Systems Engineer, US Federal

In modern IT environments, the network is more than just a connection backbone, it is the critical infrastructure that underpins compute, storage, applications, and user access. As enterprises expand across data centers, campuses, and cloud environments, network operations teams are under intense pressure to ensure availability, security, compliance, and agility, often across disparate domains. Traditional network-management tools, relying on manual configuration, polling-based monitoring, and domain-specific systems, are increasingly unable to keep up. 

Recognizing these challenges, Arista Networks developed CloudVision to bring “cloud-networking” principles, software-driven automation, standardization, and scalability into enterprise networks of any size. Arista has long been delivering network solutions with a unique software-driven approach to building reliable networks designed around the principles of best practices, standardization, simplification, cost-savings, and automation. 

**What Is CloudVision: Unified, Multi-Domain Network Management Platform**

CloudVision is Arista’s modern, multi-domain network management platform built on cloud networking principles for telemetry, analytics, and automation. Within the automation domain, CloudVision Studios provides GUI-based automation for deploying and managing networks. 

A key component behind this unification is the concept of a global “state repository” called NetDL (Network Data Lake). NetDL aggregates time-series state data streamed from all connected EOS-based devices including configurations, protocol state, hardware status, flow data, and can even integrate third-party data from partner tools. This aggregated, historic and real-time view enables network teams to manage and understand the network as a holistic entity, rather than a collection of individual devices. Since the data is stored in a timeseries, the operator can even go back in time to see a past picture of the network and its state to perform root cause analysis of any encountered problems. This vast wealth of knowledge is utilized by each feature within CloudVision to offer unparalleled visibility into a multi-domain enterprise network.

<figure markdown>
![Image Placement](img/dec25_pic3.png)
    <figcaption></figcaption>
</figure>

Beyond data consolidation, CloudVision supports multiple deployment models. Organizations can deploy it on-premises as physical or virtual appliances or opt for a fully managed cloud model, “CloudVision-as-a-Service (CVaaS)”. The features and user experience remain largely identical across deployment types, giving enterprises flexibility depending on their infrastructure, compliance, and operational preferences. 

<figure markdown>
![Image Placement](img/dec25_pic4.png)
    <figcaption></figcaption>
</figure>

**CloudVision Portal: Your Single Pane of Glass for NetOps**

The heart of day-to-day interaction with CloudVision is the Web Portal interface. The CloudVision portal combines the most common operational tasks in a web-based dashboard view, decoupled from the underlying hardware. Workflow automation in CloudVision permits operators to execute common deployment and configuration tasks from a single visual touchpoint. 

The portal includes a turnkey solution for Arista’s Zero Touch Provisioning (ZTP) which automates initial device provisioning, ongoing change controls, and device replacements over the operational life cycle of the network. Additionally, the CloudVision portal allows operators the ease of execution on tasks such as firmware upgrades, configuration changes, or compliance audits, which can now be handled in a centralized, workflow-driven manner.This reduces human error, ensures configuration standardization, and simplifies ongoing change management. 

Moreover, because CloudVision stores a versioned history of configurations, device state, and software versions, network teams can generate snapshots for pre- and post-change validation and even roll back changes if needed; a critical feature for minimizing risk and ensuring stable operations.

**State Streaming & Real-Time Telemetry: Polling vs Streaming**

Unlike legacy systems which rely on periodic polling or SNMP-based queries, CloudVision employs a state-streaming model: each EOS-based device runs a streaming agent that sends real-time device-state data into NetDL. 

This streaming-based telemetry enables CloudVision to deliver instantaneous visibility into network health from interface statistics, routing and protocol states, flow analytics, to hardware telemetry such as power, temperature, and fan status. That means network teams can spot anomalies, detect intermittent issues, or catch resource exhaustion events as they emerge rather than waiting for the next polling interval. 

Capturing time-stamped historical data also means the platform supports retrospective analysis: you can “rewind time” to inspect what the network looked like at any previous point. This has proven to be a powerful tool for root-cause analysis of outages or performance regressions. 

**AI/ML:Turning Data into Insights & Proactive Alerts**

CloudVision doesn’t just store data, it builds intelligence on top of it. By configuring devices to stream device-state and telemetry data to CloudVision, the 
Analytics Engines along with the CloudVision applications use Machine Learning (ML) algorithms to provide valuable insights into the entire state of the network, highlighting observed anomalies, and providing real-time data, updates, and alerts. 

<figure markdown>
![Image Placement](img/dec25_pic5.png)
    <figcaption></figcaption>
</figure>

For example, the system applies machine learning models to telemetry streams to detect emerging issues before they impact service. By correlating device events, topology context, and historical patterns, CloudVision provides proactive observability that helps pinpoint root causes across the network. 

For administrators, this means a shift from reactive troubleshooting to proactive network assurance closing the gap between incident detection and remediation, reducing Mean Time to Innocence (MTTI), and helping maintain consistent performance and reliability even as network complexity grows. 

**CloudVision: Seeing is Believing**

As networks continue to grow in complexity across data center, campus, branch, WAN and cloud domains, CloudVision represents a powerful, unified solution to bring simplicity and control. Its cloud-native architecture backed by real-time state streaming, a comprehensive NetDL and embedded AI/ML analytics delivers enterprise-wide visibility, predictive insights, and automation that help eliminate traditional manual toil and reduce human-error risk. 

For organizations seeking to modernize their NetOps, CloudVision offers more than just a management dashboard; it becomes the single pane of glass for real-time monitoring, configuration, compliance and change control across the entire network. By adopting this software-driven, cloud networking approach, enterprises can achieve scalable, reliable operations with faster provisioning, proactive troubleshooting and ongoing compliance ensuring their network scales smoothly to meet the continuously evolving network landscape, enabling operators to meet and exceed current day global business and industry demands. 
For more information on CloudVision and any other Arista products or services visit our website at www.arista.com.

---

## **Benefits of Replacing Legacy MPLS VPN Services with EVPN**

By: Jeff Colburn, Systems Engineer, US Federal

For nearly two decades, Multiprotocol Label Switching (MPLS) has served as the foundation of carrier-grade VPN and service delivery. However, as enterprise and service provider networks evolve toward cloud-native, software-defined (SDN), and virtualization-driven architectures, traditional MPLS pseudowire, Layer 2 (VPLS) and Layer 3 VPN (IP-VPN) services increasingly reveal their limitations. Ethernet VPN (EVPN) has emerged as the modern control plane that not only replaces legacy MPLS services but also enhances scalability, flexibility, and operational simplicity across data center, WAN, and campus environments.

Traditional MPLS VPNs, whether pseudowire, IP-VPN or VPLS, use a combination of LDP and BGP to build forwarding tables and isolate customer traffic. While robust, these technologies were designed for static, service-provider-centric environments and lack the simplificity and efficiency required in cloud-scale networks.

EVPN redefines this approach by using BGP as a unified control plane for pseudowire, Layer 2 and Layer 3 VPN services. It introduces a route-type framework that enables MAC and IP information to be distributed efficiently, reducing flooding and improving convergence.

| **Route-Type** | **Name** | **Description** |
| --- | --- | --- |
| 1   | Ethernet Auto-Discovery (AD) route | Remote discovery of dual-homed segments |
| 2   | MAC/Host IP route | Locally learned MAC address and Host IP address |
| 3   | Inclusive Multicast Ethernet Tag (IMET) Route | EVI membership advertisement |
| 4   | Ethernet Segment Route | Discover Ethernet Segment peers |
| 5   | IP Prefix Route | IP prefix advertisement |

The following are the key benefits of EVPN over legacy MPLS VPN services:

- **Control Plane MAC Address Learning**

MAC address learning is accomplished through the control plane using BGP, rather than through VPLS' flood-and-learn mechanism across the data plane. MAC moves and changes are no longer dependent on aging timers and flooding. EVPN's use of BGP provides near-real time updates and faster convergence.

- **Multi-Tenancy Support**

EVPN provides multi-tenant support by using BGP as a unified control plane to carry both Layer 2 and Layer 3 VPN information. Each tenant is assigned a unique EVPN Instance (EVI) identified by a Route Distinguisher (RD) and Route Target (RT), ensuring complete isolation of control and data planes. IP Virtual Routing and Forwarding (VRF) instances are used to isolate each tenant's routed domain, while MAC VRFs provide tenants their own isolated Ethernet domain. EVPN Integrated Routing and Bridging (IRB) permits seamless Layer 2 and Layer 3 connectivity for each tenant. Traffic for each tenant is encapsulated with distinct MPLS service labels, allowing multiple tenants to share the same physical infrastructure while keeping their traffic isolated from each other.

- **Unified Control Plane**

The complexity of multiple BGP address families and LDP signaling is no longer required to provide Layer 2 and Layer 3 services. EVPN consolidates Layer 2 and Layer 3 services into a single control plane by using the Route Types for address advertisements. This simplification reduces operational overhead and streamlines service deployment.

<figure markdown>
![Image Placement](img/dec25_pic1.png)
    <figcaption></figcaption>
</figure>

- **Transport Independent**

EVPN is transport agnostic, supporting both MPLS and VXLAN data planes. Multi-tenant Layer 2 and Layer 3 service offerings can span both environments under a shared control plane. This is especially valuable when VXLAN-based data centers are interconnected over a MPLS WAN.

<figure markdown>
![Image Placement](img/dec25_pic2.png)
    <figcaption></figcaption>
</figure>

- **Load Balancing & Availability**

EVPN supports Active-Active Multihoming with Ethernet Segment Identifier (ESI). Clients may connect to multiple PEs that are members of the same ESI for improved availability. EVPN advertises ESI membership, enabling Equal Cost Multi Path (ECMP) from the remote PEs. The Designated Forwarder (DF) election mechanism identifies the receiving PE for BUM traffic per ESI, ensuring loop-free redundancy and load balancing.

- **Multicast Support**

EVPN enhances multicast functionality using dedicated route types to control group membership and replication. In MPLS environments, Route Types 3, 6, 7, and 8 are used for multicast group signaling and selective replication. Route Type 10 applies to VXLAN environments for optimized overlay multicast group to underlay multicast group mapping.

| **Route-Type** | **Name** | **Description** |
| --- | --- | --- |
| 6   | IGMP & MLD Proxy route | Advertise and proxy local IGMP joins/leaves |
| 7   | IGMP/MLD Join Sync route | Advertise/sync local IGMP Join in multi-home topology |
| 8   | IGMP/MLD Leave Sync route | Advertise/sync local IGMP Leave in multi-home topology |
| 10  | S-PMSI-AD route | Overlay to Underlay multicast group mapping (VXLAN) |

- **Standards Based**

EVPN is a standards-based (RFC 7432) technology with broad multi-vendor interoperability verified across leading networking vendors. EVPN ensures open, future-proof architectures and eliminates the potential for vendor lock-in.

- **Migration Ready**

As VXLAN adoption expands across campus, data center, and WAN environments, EVPN simplifies migration from MPLS to VXLAN. Its shared control plane allows operators to deploy both transports simultaneously, enabling a phased, non-disruptive transition.

While MPLS remains a viable transport option, traditional Layer 2 and Layer 3 VPN services are increasingly inefficient and operationally complex. EVPN provides a transport-independent, unified control plane that delivers these services more efficiently, while allowing seamless coexistence and gradual migration from IP VPN and VPLS to EVPN-based services.

---

## __*Upcoming Events*__  
Arista hosts various events throughout the year for you! Members of our team organize these informative events to showcase Arista's ability to not only help improve your network, but to also assist by providing a set of tools to improve your operations! Click on the boxes below to be directed to Arista's website for lists of Webinars and Events.

<div class="grid cards" markdown>

-   __Arista Network Webinars Series with Carahsoft__

    __For Channel Partners Only__

    [![Image Placement][5]][6]
    [5]: img/arista-carasoft-v2.png
    [6]: https://carahevents.carahsoft.com/Event/Details/618442-arista-networks

    __Please check back next quarter for our 2026 schedule!__

    |  Date | Name| Description | 
    | :-----------: | :-----------: | :-----------: |
    | __TBD__ | TBD | TBD |

    [Register Here](https://carahevents.carahsoft.com/Event/Details/618442-arista-networks){.md-button}

</div>


<div class="grid cards" markdown>

-   __Webinars__  

    --- 

    We make is easy for you to view products that are of interest, all virtually! Technical memebers of the team showcase outstading explanation of the products. Click below to see our list of Webinars. 

    [Arista Webinars](https://www.arista.com/en/company/news/webinars){.md-button}

-   __Events__ 

    ---
    Join us in person to get a closer look in our list of produts and solution, as well as get the chance to meet members of the team. Click below to see our list of ipcoming Events. 

    [Upcoming Events](https://www.arista.com/en/company/news/events){ .md-button }


</div>

--- 
## __*Software Updates*__
<figure markdown>
![Image Placement](img/pictureOfCloudVision.jpeg){: style="height:200px;width:300px"}    
    <figcaption></figcaption>
</figure>
For new code releases, click [here](https://www.arista.com/en/support/software-download) 


   |  Softwares    | Versions      |  Release Date |
   | :-----------: | :-----------: | :-----------:
   | __EOS__           | 4.34.3.1M <br>4.32.8M <br> 4.34.3M <br> 4.35.0F <br>  | November 4th, 2025 <br>October 27th, 2025 <br> October 6th, 2025 <br> October 6th, 2025 <br> 
   | __CVP__           | Portal 2025.2.1 <br> Appliance 7.0.1 <br> Sensor 1.2.0 <br>    | August 21st, 2025 <br> January 28th, 2025<br> September 8th, 2025 <br>
   | __DMF__           | 8.8.0 <br >| August 15th, 2025 <br> 
   | __WLAN__ <br>CV-CUE<br> | <br> 19.0.0 <br>      | <br> July 25th, 2025<br>  
   | __Arista NDR__         | 5.3.5         | July 16th, 2025
   | __TerminAttr__    | 1.39.1 <br>       | July 18th, 2025 <br>  
   | __VeloCloud SD-WAN__  <br>Orchestrator/ Gateway / Edge<br>  | <br>6.4.0 <br>       | <br> May 2nd, 2025 <br> 

---

## __*Software Advisories*__
Below is a list of advisories that are announced by Arista. To view more details on the specific advisories, please click the links in the middle row.

| Name          | Advisory Link           | Date of Advisory Notice  |
| :-----------: |:-------------:| :-----:|
|  __Arista DANZ Monitoring Fabric__   | [Security Advisory 0124](https://www.arista.com/en/support/advisories-notices/security-advisory/22538-security-advisory-0124)  | October 22nd, 2025   |  
|  __Arista Edge Threat Management NGFW__   | [Security Advisory 0123](https://www.arista.com/en/support/advisories-notices/security-advisory/22535-security-advisory-0123)  | October 21st, 2025   |  
|  __WiFi 7 Access Points Firmware Version 21.0__   | [Field Notice 0117](https://www.arista.com/en/support/advisories-notices/field-notice/22534-field-notice-0117)  | October 16th, 2025   |  
|  __SwitchApp Interfaces starting with EOS 4.35.0F__   | [Field Notice 0116](https://www.arista.com/en/support/advisories-notices/field-notice/22528-field-notice-0116)  | October 14th, 2025   |  

 

For a list of the most current advisories and notices, click [Here](https://www.arista.com/en/support/advisories-notices)

---

## __*Product Updates*__
<figure markdown>
![Image Placement](img/pictureOfSwitches.jpeg){: style="height:200px;width:400px"}   
    <figcaption></figcaption>
</figure>
**End of Sale** notices are listed below.

| Device        | Name           | End Of Sale Date  |
| :-----------: |:-------------: |     :----:        |
| Software      | [End of Software for CloudVision Portal 2023.2](https://www.arista.com/en/support/advisories-notices/end-of-support/21412-end-of-software-support-for-cloudvision-portal-2023-2-release-train)<br>[End of Software Support for EOS 4.28](https://www.arista.com/en/support/advisories-notices/end-of-support/21275-end-of-software-support-for-eos-4-28)<br>[DMF and CCF Deployments on Accton/ Edgecore Switches](https://www.arista.com/en/support/advisories-notices/end-of-support/21094-end-of-support-for-dmf-and-ccf-deployments-on-accton-edgecore-switches)<br>[EOS-4.34 and later no longer supported on select switches](https://www.arista.com/en/support/advisories-notices/end-of-support/21089-end-of-software-support-for-7280r-r2-7500r-r2-and-7020r-series)<br> | May 27th. 2025 <br> March 14, 2025 <br>January 31st, 2025 <br>January 15th, 2025 <br> |
| CVP           | [CVP IPAM Application](https://www.arista.com/en/support/advisories-notices/endofsupport) <br> [CVP 2023.3](https://www.arista.com/en/support/advisories-notices/end-of-support/21627-end-of-software-support-for-cloudvision-portal-2023-3-release-train)          |  July 14th, 2025 <br> June 17th, 2025   |
| DMF           | [DMF Service Node DCA-DM-SC2](https://www.arista.com/en/support/advisories-notices/end-of-sale/22537-end-of-sale-end-of-life-for-arista-service-node-appliance-dca-dm-sc2)          |  October 22nd, 2025           |  
| CCF           | [CCF Product Line](https://www.arista.com/en/support/advisories-notices/end-of-sale/22430-end-of-sale-end-of-life-for-arista-ccf-product-line)          |  October 1st, 2025           |  
| Switches      | [7010TX-48-DC Switch](https://www.arista.com/en/support/advisories-notices/end-of-sale/22421-end-of-sale-of-the-arista-7010tx-48-dc-switches)<br> [7050CX3-32S Switch](https://www.arista.com/en/support/advisories-notices/end-of-sale/22419-end-of-sale-of-the-arista-7050cx3-32s-switches)<br> [CCS-720XP-96ZC2 Switch with 4GB DRAM](https://www.arista.com/en/support/advisories-notices/end-of-sale/22403-end-of-sale-of-the-arista-ccs-720xp-96zc2-switches-with-4gb-dram)<br> [CCS-720D Switches with 4GB DRAM](https://www.arista.com/en/support/advisories-notices/end-of-sale/22402-end-of-sale-of-the-arista-ccs-720d-switches-with-4gb-dram)<br> [CCS-710P-12 Switch](https://www.arista.com/en/support/advisories-notices/end-of-sale/22401-end-of-sale-of-the-arista-ccs-710p-12-switch) |  September 19th, 2025<br> September 19th, 2025<br> Septemebr 12th, 2025<br> September 12th, 2025<br> September 12th, 2025 |
| Access Points      | [AP Mounts](https://www.arista.com/en/support/advisories-notices/end-of-sale/22536-end-of-sale-of-ap-mounts-mnt-ap-flat-c130-mnt-ap-flat-c100-mnt-ap-flat-14cm-a)<br> |  October 22nd, 2025 <br> | 
| VeloCloud      | [SASE Secured by Symantec](https://www.arista.com/en/support/advisories-notices/end-of-sale/22072-end-of-sale-life-velocloud-sase-secured-symantec)<br> [Software Defined (SD) Access](https://www.arista.com/en/support/advisories-notices/end-of-sale/21653-end-of-sale-end-of-life-for-velocloud-software-defined-sd-access) <br> |  August 20th, 2024 <br> July 1st, 2025 | 




**New Releases** of Arista's device are listed below 

|  Device       | More Information |  Release Date 
    | :-----------: | :-----------:    | :-----------:
    | Arista VeloCloud | [VeloCloud Acquisition](https://www.arista.com/en/company/news/press-release/21646-pr-07012025) | Q3 2025
    |  Arista SWAG    |   [Modern Stacking for Campus](https://www.arista.com/en/company/news/press-release/20693-pr-12032024)                | Q1 2025 
    | Arista Multi-Domain Segmentaton Service  | [Arista MSS](https://www.arista.com/en/company/news/press-release/19297-pr-20240430)         | Q3 2024
    | Arista CV UNO  | [CloudVision Universal Network Observability](https://www.arista.com/en/company/news/press-release/19195-pr-20240305)  | Q1 2024

---
# *Feel Free to Reach Out To Us For Your Network Needs* 
<figure markdown>
![Image Placement](img/pictureOfNetworks.jpeg){: style="height:300px;width:800px"}  
    <figcaption></figcaption>
</figure>
We thank you for taking the time to read out newsletter today. Feel free to reach out to your SE or ASE for more information or questions regardsing your network operations. Until next month, have a good one! 
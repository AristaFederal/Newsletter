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


# Welcome to the February 2026 Edition of the Arista Federal Newsletter!

**USA – USA – USA!** As we celebrate and show our support for Team USA at the 2026 Winter Games in Milan, Italy, we’re proud to share this month’s Arista Federal Newsletter highlighting how Arista continues to perform at a Gold Medal level in delivering mission-critical networking.

Just as Olympians train for precision, consistency, and peak performance, Arista is built for operational excellence. As a recognized network leader, Arista delivers best-in-class solutions across Campus, Data Center, WAN, and AI infrastructure. With a consistent operating model powered by EOS, NetDL, and CloudVision, we help organizations simplify operations, enhance reliability, and scale with confidence.

We’re proud to stand on the podium alongside our Federal and System Integrator partners and look forward to continuing our work together supporting your mission, overcoming new challenges, and delivering Gold Medal-level performance in the year ahead. 

Together, let’s push forward, aim higher, and deliver Gold Medal performance with Arista Networks.  

In this month’s newsletter, you’ll find:



- **The Arista DANZ Monitoring Fabric: Visibility Without Compromise**

    Arista Federal Systems Engineer Peter Gore explores how the Arista DANZ Monitoring Fabric (DMF) delivers centralized, end-to-end network visibility across hybrid infrastructures ensuring the right data reaches the right tools at the right time, without impacting production traffic.

- **Arista Networks Delivering Media and Entertainment Solutions**

    Ryan Morris and Gerard Phillips, Arista Systems Engineers and Media & Entertainment Technical Leads, provide valuable insight into how Arista delivers the performance, timing precision, and reliability required for modern IP-based video and audio distribution across Federal and mission-critical environments.

  
This newsletter is for you and we welcome your feedback, ideas, and requests at <fed@aristafederal.com>.

Thank you for reading the Arista Federal Newsletter — your go-to source for the latest innovations, industry insights, and mission-focused networking solutions for Federal Agencies and System Integrators.


---

## **Arista Blog**

[![Image Placement][3]][4]
[3]: img/blog.png
[4]: https://blogs.arista.com/blog


---

## **The Arista DANZ Monitoring Fabric: Visibility Without Compromise**
By: Peter Gore, Systems Engineer, US Federal

In today’s complex Federal and mission-critical environments, network visibility is no longer
optional—it&#39;s essential. Security teams need to see threats, operations teams need to troubleshoot
performance issues, and compliance officers need to prove they&#39;re monitoring the right traffic.
But here&#39;s the problem: most organizations are unaware of various parts of their infrastructure,
caused by patchwork solutions that create gaps.

The Arista DANZ Monitoring Fabric (DMF) is a next-generation network packet broker (NPB)
architected for pervasive, organization-wide visibility. It’s a platform designed to solve the
fundamental challenge of infrastructure visibility, solves getting the right data to the right tools at
the right time, without compromising network performance.

### **What Is the Arista DANZ Monitoring Fabric?**

At its core, Arista DMF is a network packet broker solution that sits between your production
network and your monitoring and security tools. Essentially, it as an intelligent traffic director for
your network visibility infrastructure.

The platform aggregates traffic from across your physical, virtual, and cloud environments, then
filters, deduplicates, and optimizes that traffic before delivering it to your monitoring
tools—whether those are intrusion detection systems, application performance monitoring
platforms, forensic recorders, or any other tool that needs network data to function.

Arista DMF creates a fabric layer that separates your production network from your monitoring
infrastructure. This architectural approach means you can add, remove, or reconfigure
monitoring tools without ever touching production traffic, eliminating a major source of risk and
operational complexity.

### **The Business Case: Why Organizations Deploy Arista DMF**

The benefits of implementing a monitoring fabric extend far beyond the IT department. Here&#39;s
what organizations gain:

**Complete Visibility Across Hybrid Environments**

Modern networks span on-premises data centers, private clouds, and public cloud platforms.
Arista DMF provides a unified visibility layer across all of these environments, eliminating blind
spots that attackers exploit and troubleshooting nightmares that cost organizations millions in
downtime.

**Tool Optimization and Cost Savings**

Monitoring and security tools are expensive—often priced based on the traffic volume they process. Arista DMF dramatically reduces tool costs by deduplicating packets, filtering out
irrelevant traffic, and load-balancing across tool clusters. Organizations commonly see 40-60%
reductions in the data volume sent to tools, which translates directly to lower licensing costs and
extended tool lifespan. Instead of overprovisioning expensive tools to handle peak traffic, you
can right-size your investment.

**Improved Security Posture**

You can&#39;t protect what you can&#39;t see. Arista DMF ensures that security tools receive exactly the
traffic they need to detect threats—no more, no less. Advanced filtering capabilities mean you
can send encrypted traffic to decryption tools, application traffic to application-aware security
tools, and everything else to your general-purpose systems. This precision dramatically improves
detection rates and reduces false positives.

**Operational Agility**

Network teams spend countless hours on change requests to add monitoring capabilities. With
Arista DMF, those changes happen in the fabric layer through software configuration, not
through risky production network changes. Need to start monitoring a new application, a new
security tool? Spin up monitoring within a very short period of time and start seeing results
immediately!

**Future-Proofing Your Investment**

Technology changes, but your monitoring infrastructure shouldn&#39;t need to be ripped and replaced
every few years. Arista DMF creates an abstraction layer that makes your monitoring
architecture tool-agnostic and protocol-agnostic. This flexibility protects your investment as your
technology stack evolves.

**Compliance and Audit Support**

Regulatory frameworks increasingly require organizations to demonstrate comprehensive
monitoring capabilities. Arista DMF provides the evidence that you&#39;re seeing and analyzing the
traffic you claim to monitor, with full audit trails of what&#39;s being monitored, where traffic is
flowing, and how tools are being utilized.

**Network Time Machine for Forensics**

For forensic investigations, DMF includes Recorder Nodes that provide &quot;Network Time
Machine&quot; capabilities. Operators can record petabytes of traffic and &quot;replay&quot; past conversations
with a few clicks, accelerating root-cause analysis after a security incident and providing a clear
audit trail of historical network events.

### **Arista Integration: Arista CloudVision &amp; Arista DMF**

A critical advantage for federal operators is the seamless integration between Arista CloudVision
(CV) and Arista DMF, providing a &quot;Single Pane of Glass&quot; for both the production and
monitoring networks.

**Automated Visibility (Auto-SPAN)**

The DMF Controller communicates directly with CloudVision to retrieve the production device
inventory. DMF can automatically configure SPAN sessions or L2GRE tunnels on any Arista
EOS switch managed by CloudVision, ensuring that visibility follows the workload without
manual CLI intervention.

**Unified Observability with CloudVision UNO**

CloudVision Universal Network Observability (CV UNO) leverages DMF as a high-fidelity data
source. It creates a comprehensive application-to-network graph, allowing federal IT teams to
instantly determine if a performance lag is a network hotspot or an application-level event.

**Zero-Touch Monitoring (ZTM)**

New switches added to the visibility fabric are automatically discovered and provisioned by the
DMF Controller, enabling rapid deployment in field offices or forward-deployed environments.

### **The Bottom Line**

Arista DANZ Monitoring Fabric (DMF) transforms network visibility from a fragmented,
reactive capability into a strategic asset. Organizations gain the complete visibility needed to
secure modern networks, the efficiency to maximize tool investments, and the agility to adapt as
business needs evolve.

- Complete, end-to-end visibility
- Improved security and threat detection
- Reduced monitoring and tool costs
- Operational agility without production risk
- A scalable, future-ready visibility architecture

With the combined power of Arista DMF and Arista CloudVision, Federal organizations can
achieve full-spectrum visibility, operational consistency, and proactive control—without
compromise.

---

## **Arista Networks Delivering Media and Entertainment Solutions**

By: Ryan Morris &amp; Gerard Phillips, Systems Engineers, Arista Media &amp; Entertainment Technical Leads

The distribution of video and audio content over IP Networks has become commonplace over
the last 10 years. Led by the global-scale, live sports producers, major broadcasters have
converted from traditional SDI to SMPTE ST-2110 networked workflows, deploying networks of
every conceivable scale. While led by global sports broadcasters, the benefits are recognized
widely, and we now see the transformation across daily broadcasts, training and promotional
events, houses of worship, and video distribution of content within large corporations, and
government buildings. For years, Arista has been at the core of these media distribution
network transformations for a number of reasons.

**Software Reliability:**

Two key requirements of any SMPTE ST-2110 network are Multicast Delivery, and Precision
Time Protocol (PTP) distribution. These happen to be the exact requirements that the Low-
Latency trading industry needs, and which Arista has been servicing almost since its inception.
Arista understands the importance of media content and the ramifications of losing even a
packet of video, and thus, continues to implement testing infrastructures that reflect real-life
deployments, to ensure that these broadcast systems remain reliable at both low and high
scale. Current broadcast systems may require many tens of thousands of multicast groups and
hundreds of PTP clients on a single switch - and Arista ensures this support for content creators
and distributors is available.

**Partnerships:**

Arista has developed partnerships with all the major broadcast vendors that improve customer
workflows from not only an orchestration perspective, but a monitoring and visibility one as well.
SMPTE ST-2110 networks have been deployed for years now - the standard is mature, and
systems are extremely reliable when designed using best practices. However, what was
missing for early adopters of the standard was the knowledge of what was successful, or not
successful, from a flow routing perspective. Broadcast engineering teams were apprehensive
about the lack of insight provided by these systems, when compared to an SDI router where
tally was common. But now, with broadcast vendors integrating with our orchestration solutions
(Media Control Service, MCS), and other vendors subscribing to real-time telemetry, the
network ceases to be a black box, and a fuller understanding of the immediate events taking
place in a media distribution network are provided to the customers and users.

**Orchestration Software:**

Arista Media Control Service (MCS) is a multicast flow orchestration solution designed with the
many facets of broadcast workflow standards in mind, as well as a satisfying broadcast operator
experience. Arista MCS acts as an interface between the control panel of the broadcast
operator and the IP network. It facilitates the conversion of broadcast operations to network
operations. Arista MCS manages and monitors real-time broadcast workflows over IP networks
with a deterministic high-performance service and an easy-to-use API interface. Broadcast
controllers integrate with this API interface to provision multicast flows required to support
SMPTE ST2110, ST2022, AES67 and many other flow types.

Key advantages of MCS include:
- Faster than traditional multicast routing protocols
- Bandwidth protection, from oversubscription and larger than expected flow provisioning
- Real-time notifications that broadcast controllers and other network monitoring
tools can subscribe to - provides crucial information for system health and routing
status of the media workflow


![Image Placement][5]
[5]: img/jan26_pic1.png

**Strong PTP Stack:**

Designing a reliable Precision Time Protocol (PTP) network is an absolute requirement for any
SMPTE 2110 network. Senders and receivers must be locked to a common clock to ensure

video and audio alignment, multi-channel audio operation, as well as to ensure that switching
between video sources on a receiver is clean and does not produce a broken signal.

Possibly the most important decision to make, from a network perspective, to build a resilient
PTP network is determining what sort of clock your networking switch should be configured as:
Boundary Clock or Transparent Clock. Generally, in these types of deployments, we see
Boundary Clock as the clock of choice.

**Why Boundary Clock?**

1. Basic configuration:
Boundary Clocks do not depend on unicast or multicast routing - they lock to an
upstream GM (or upstream Boundary Clock), and distribute timing on PTP enabled
interfaces based on that upstream clock.
Both global and per interface configurations are simple, but care must be taken to
ensure that the messaging rates are consistent between connected interfaces,
especially the announce interval.
2. Flexibility:
As the image above specifies, the messaging rates in a Boundary Clock are provisioned
on a per interface basis. This is helpful as there are some devices that may require a
different announce interval than the majority of other devices connected to the network.
This can easily be achieved by simply modifying the message rate on those specific
interfaces.
3. Increased Visibility:
Boundary Clocks provide significant visibility into the accuracy of GM, which can be
extremely useful when tracking performance during events that trigger a Best Master
Clock Algorithm (BMCA) to elect a new GM. Examples of such data can be seen below.

**PTP Message Counters Per Interface**

![Image Placement][6]
[6]: img/jan26_pic2.png


**Monitoring Accuracy of Boundary Clock compared to upstream GM**

![Image Placement][7]
[7]: img/jan26_pic3.png


This type of data is streamable as well and can be made to be presented clearly in CloudVision
(CVP and CVaaS) and other third-party monitoring tools.

For example, as viewable in CVP:

![Image Placement][8]
[8]: img/jan26_pic4.png

![Image Placement][9]
[9]: img/jan26_pic5.png

![Image Placement][10]
[10]: img/jan26_pic6.png

![Image Placement][11]
[11]: img/jan26_pic7.png


PTP topology views, event-based alarms, and streaming of PTP counters allow network
operators to understand the behavior of a PTP network, and its performance, in real-time.
Additionally, given that CloudVision stores this data in a time-series database, users can
examine these events from a prior date to gain better insight into possible PTP changes that
propagated in the network.
In summary, Arista is a core partner in the media and entertainment industry&#39;s transition to IP
and SMPTE ST-2110 workflows. Its success is built on providing reliable software with robust
Multicast and PTP support, fostering key partnerships for enhanced visibility, offering the
powerful Media Control Service (MCS) orchestration software, and ensuring a strong PTP stack
with preferred Boundary Clock deployments. These solutions enable reliable, high-performance,
and transparent media distribution networks, cementing Arista&#39;s position as a leader in this
critical technological evolution.

For more information pertaining to Arista’s Media and Entertainment solutions, including
webinars, best practice documentation, white papers, and customer success stories, please visit
us at <https://www.arista.com/en/solutions/media-entertainment>. Or reach out to your account
representatives to inquire how Arista’s Media Solutions can operate in your facility.

---

## __*Upcoming Events*__  
Arista hosts various events throughout the year for you! Members of our team organize these informative events to showcase Arista's ability to not only help improve your network, but to also assist by providing a set of tools to improve your operations! Click on the boxes below to be directed to Arista's website for lists of Webinars and Events.

<div class="grid cards" markdown>

-   __Arista Network Webinars Series with Carahsoft__

    __For Channel Partners Only__

    [![Image Placement][12]][13]
    [12]: img/arista-carasoft-v2.png
    [13]: https://carahevents.carahsoft.com/Event/Details/618442-arista-networks

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
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

Just as Olympians train for precision, consistency, and peak performance, Arista is built for operational excellence. As a recognized network leader, Arista delivers best-in-class solutions across Campus, Data Center, WAN, and AI infrastructure. A consistent operating model powered by EOS, NetDL, and CloudVision helps organizations simplify operations, enhance reliability, and scale with confidence.

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
![Image Placement][6]
[6]: img/jan26_pic2.png

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

![Image Placement][7]{width=650}
[7]: img/jan26_pic3.png


**Monitoring Accuracy of Boundary Clock compared to upstream GM**

![Image Placement][8]{width=600}
[8]: img/jan26_pic4.png


This type of data is streamable as well and can be made to be presented clearly in CloudVision
(CVP and CVaaS) and other third-party monitoring tools.

For example, as viewable in CVP:

![Image Placement][9]
[9]: img/jan26_pic5.png

![Image Placement][10]
[10]: img/jan26_pic6.png

![Image Placement][11]
[11]: img/jan26_pic7.png

![Image Placement][12]
[12]: img/jan26_pic8.png


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

## __*2026 Webinar Series — Coming Soon*__

Our 2026 webinar schedule will be announced shortly, and we look forward to your participation in another year of insightful and informative sessions. In the meantime, we invite you to explore the recordings from our 2025 webinar series featuring valuable discussions, technical deep dives, and best practices across key networking topics.

2025 Webinar replays are available here: 

<https://www.carahsoft.com/content-hubs/arista-networks-resources/federal-IT-modernization-webinar-series>

Stay tuned for more details, and we hope you’ll join us for the upcoming 2026 sessions.

<https://www.carahsoft.com/content-hubs/arista-networks-resources/federal-IT-modernization-webinar-series>

<div class="grid cards" markdown>

-   __Arista Network Webinars Series with Carahsoft__

    __For Channel Partners Only__

    [![Image Placement][20]][21]
    [20]: img/arista-carasoft-v2.png
    [21]: https://carahevents.carahsoft.com/Event/Details/618442-arista-networks


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
![Image Placememt](img/software_upgrades_condensed.png)

*Stay informed on the latest software updates across all Arista products and services.*

|  Software    | Version      |  Release Date |
| :-----------: | :-----------: | :-----------: |
| __EOS__           | 4.23.10M <br> 4.34.5M <br> 4.33.7M <br> 4.35.2F | March 2nd, 2026 <br> February 25th, 2026 <br> February 24th, 2026 <br> February 17th, 2026 |
| __CVP__           | Portal 2025.3.2 <br> Appliance 7.1.0 <br> Sensor 1.3.0 | February 12th, 2026 <br> September 2nd, 2025 <br> December 5th, 2025 |
| __DMF__           | 8.9.0 | February 13th, 2026 |
| __CV-CUE__         | 21.0.0 | January 16th, 2026 |
| __Arista NDR__     | 5.3.5 | July 16th, 2025 |
| __TerminAttr__     | 1.42.1 | February 4th, 2026 |
| __VeloCloud SD-WAN__ <br>Orchestrator/Gateway/Edge | 6.4.1 | December 19th, 2025 |

[View All Latest Software Updates](https://www.arista.com/en/support/software-download){: .md-button .md-button--primary target="_blank" }




---

## __* Security Advisories and Field Notices*__

![Image Placememt](img/Security_image_2.png)

*Stay informed on the latest platform security and field notice updates.*

### **Security Advisories**
* **Hardware IPSec** — [Security Advisory 0134](https://www.arista.com/en/support/advisories-notices/security-advisory/23419-security-advisory-0134){: target="_blank" } <br> *(February 17th, 2026)*
* **ETM NGFW** — [Security Advisory 0133](https://www.arista.com/en/support/advisories-notices/security-advisory/23399-security-advisory-0133){: target="_blank" } <br> *(February 3rd, 2026)*

### **Field Notices**
* **CV-CUE: Depreciation of IAPC via Wireless Manager** — [Field Notice 0124](https://www.arista.com/en/support/advisories-notices/field-notice/23398-field-notice-0124){: target="_blank" } <br> *(February 3rd, 2026)*
* **CV-CUE: Depreciation of Probed SSID** — [Field Notice 0123](https://www.arista.com/en/support/advisories-notices/field-notice/23397-field-notice-0123){: target="_blank" } <br> *(February 3rd, 2026)*

<br>

[View All Latest Advisories & Notices](https://www.arista.com/en/support/advisories-notices){: .md-button .md-button--primary target="_blank" }

---




## __* Product Updates*__

![Image Placememt](img/Product_image.png)


*Stay up to date on all new Arista Product Releases, as well as End of Sale/End of Support Notices.*



### **New Product Releases** 
* **Q1 2026** — [Ask AVA - CloudVision as a Service (beta feature)](https://www.arista.io/help/articles/overview-core-tools-ask-ava){: target="_blank" }


###  **End of Sale / End of Software Support**
* **February 18th, 2026** — [DMF Node DCA-DM-AN450](https://www.arista.com/en/support/advisories-notices/end-of-sale/23436-end-of-sale-end-of-life-for-arista-analytics-node-appliance-dca-dm-an450){: target="_blank" } 
* **February 18th, 2026** — [DMF Node DCA-DM-C450](https://www.arista.com/en/support/advisories-notices/end-of-sale/23435-end-of-sale-end-of-life-for-arista-dmf-controller-appliance-dca-dm-c450){: target="_blank" } 
* **February 2nd, 2026** — [CloudVision Portal 2024.2](https://www.arista.com/en/support/advisories-notices/end-of-support/23396-end-of-software-support-for-cloudvision-portal-2024-2-release-train){: target="_blank" } 

<br>

[View All Latest End of Sale & Support Notices](https://www.arista.com/en/support/advisories-notices/endofsale){: .md-button .md-button--primary target="_blank" }

---
# *Feel Free to Reach Out To Us For Your Network Needs* 
<figure markdown>
![Image Placement](img/pictureOfNetworks.jpeg){: style="height:300px;width:800px"}  
    <figcaption></figcaption>
</figure>
We thank you for taking the time to read out newsletter today. Feel free to reach out to your SE or ASE for more information or questions regardsing your network operations. Until next month, have a good one! 
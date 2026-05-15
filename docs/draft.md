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

# Welcome to the May 2026 Edition of the Arista Federal Newsletter!

May is a month of meaningful celebration and remembrance. We recognize and appreciate all mothers for the tremendous impact they have on our families, communities, and future generations. As Memorial Day approaches, we also pause to honor and remember the brave men and women who made the ultimate sacrifice in service to our nation.
In this edition, we continue highlighting the technologies, customer successes, and strategic initiatives helping Federal agencies and System Integrators modernize infrastructure for the future through automation, AI networking, operational simplicity, and secure, resilient architectures.

“A hero is someone who has given his or her life to something bigger than oneself.” — Joseph Campbell (1904–1987) - American writer.

In this month’s newsletter, you’ll find:

- **Arista TAC Continues to Set the Standard for Customer Success**

    Arista Federal Client Director Kevin Carey highlights why Arista TAC continues to stand apart and the operational value it delivers to Federal customers supporting classified, AI/HPC, data center, campus, and WAN environments.

    Exceptional technology is only part of the equation; world-class customer support truly defines long-term success.

- **Arista and the Department of War: Sharing Innovation for the Mission!**

    Arista Systems Engineer Michael Alvarez explores how modern networking technologies support next-generation mission requirements across the Department of Defense.

    As Federal agencies continue modernizing infrastructure to support AI, HPC, and advanced analytics, this article highlights why Arista is uniquely positioned to help customers accelerate innovation while reducing operational complexity.



This newsletter is for you and we welcome your feedback, ideas, and requests at <fed@aristafederal.com>.

Thank you for reading the Arista Federal Newsletter — your go-to source for the latest innovations, industry insights, and mission-focused networking solutions for Federal Agencies and System Integrators.

---

## **Arista Blog**

[![Image Placement][3]][4]
[3]: img/blog.png
[4]: https://blogs.arista.com/blog

---
## **Arista TAC Continues to Set the Standard for Customer Success**

By Kevin Carey – Arista Federal Client Director

Arista Networks continues to demonstrate why its Technical Assistance Center (TAC) is
recognized as one of the industry’s premier support organizations. In 2026, Arista TAC
improved upon its already exceptional previous NPS score of 87, achieving an industry-
leading Net Promoter Score (NPS) of 89, with 94% of customers reporting a strongly
positive experience.

These results reflect Arista’s relentless focus on customer success, operational
excellence, and technical expertise. For many customers, Arista TAC is one of the
company’s strongest differentiators and a key reason why organizations choose and
remain with Arista.

Unlike traditional support organizations that rely on multiple escalation tiers and scripted
workflows, Arista TAC is built around a highly technical, engineering-driven support
model focused on accelerating problem resolution and enhancing the “customer
experience”. Customers work directly with experienced network engineers who possess
deep expertise in Arista EOS and modern network architecture.

**Why Arista TAC Stands Apart**

Arista TAC provides:

- 24x7 global technical support
- Direct access to highly skilled network engineers
- Hardware and software troubleshooting
- EOS software support and upgrade guidance
- Configuration assistance and operational best practices
- RMA coordination and proactive operational guidance

A key differentiator is the close alignment between TAC and Arista’s EOS engineering
teams, enabling faster root-cause analysis, rapid issue resolution, and tighter feedback
loops between customers and development.

**Operational Value for Federal Customers**

For Federal organizations, where mission continuity, operational simplicity, and rapid
issue resolution are critical, the value of a world-class support organization cannot be
overstated.

Because Arista operates a single EOS operating system across campus, data center,
WAN, and AI environments, TAC engineers develop deep platform expertise across the
entire portfolio. This consistency enables:

- Faster troubleshooting and reduced escalation delays
- Shorter Mean Time to Resolution (MTTR)
- Lower operational overhead
- More accurate operational guidance
- Reduced lifecycle complexity

Arista’s software quality and architectural consistency also contribute to fewer critical
issues, lower CVE exposure, and fewer emergency maintenance events. As a result,
many TAC engagements are consultative and operationally focused rather than crisis
driven.

**A Trusted Operational Partner**

Customers often view Arista TAC as an extension of their own operational teams.
Beyond troubleshooting, TAC regularly assists customers with:

- Design guidance
- Automation workflows
- EOS upgrades and migrations
- Best practices and feature adoption
- Operational optimization

This partnership-oriented approach helps Federal customers confidently deploy and
operate next-generation networking technologies across mission-critical, classified,
AI/HPC, campus, and data center environments.

The 2026 NPS results further reinforce Arista’s commitment to delivering not only
innovative technology, but also an exceptional “customer experience”.

---
## **Arista and the Department of War: Sharing Innovation for the Mission!**

By Michael Alvarez - Systems Engineer, US Federal

**Mission Critical**

When we think of the Department of War (DoW), we think of phrases such as “mission critical”, “supporting warfighter efforts” and “saving lives”.  These are the calls that invigorate and motivate the workforce within the DoD with purpose and initiative to innovate. Recently, it has been determined that the status quo of the mission was not keeping pace with our adversaries around the world and there was fear that The United States was falling behind in that initiative and innovation.

**The Need for Speed**

In 2024, an effort within Congress to bolster defense innovation was made by creating the House Defense Modernization Caucus.  The purpose?  To shift the paradigm by working to streamline and accelerate the DoW’s Authority to Operate (ATO) process, providing attractive offerings to increase the hiring speed of industry talent and increase classified space access for private sector companies to come in and innovate.  Most importantly, they wanted the Department of War to lean on more modern software-centric and commercial-of-the-shelf (COTS) solutions.  They wanted to leverage this in a way where the wheel could stop being re-invented and to repurpose foundational solutions across multiple environments.  This would be the key to identifying challenges, streamlining innovation and reducing time and waste.

**RDMA in Play**

Recently, Arista Federal has seen many of its customers more commonly adopt mission based software applications that lean heavily into the use of Remote Direct Memory Access (RDMA) over converged ethernet (RoCE) protocol.  This is used to allow software applications to bypass the host CPU’s TCP/IP stack to achieve faster data transfers.  In essence, faster data analysis and processing, faster early warning systems, faster response in the battle space.  Think back to those phrases mentioned earlier. 

**RDMA…Cutting Edge?**

No, not really. RDMA has existed as far back as 2003 with the inception of the RDMA consortium. It was developed to approach more efficient ways to move data between endpoints across a network with high throughput and low latency to support high performance machine learning (M/L). However, to really achieve this goal, a network needed to be able to support RDMA. 

**The Birth of RDMA over Converged Ethernet (RoCEv1)**

In 2010, the Infiniband Trade Association released an initial version of RoCEv1 to support RDMA applications across an ethernet environment. This effectively enabled RDMA to work over Ethernet, operating at the Ethernet link layer (Layer 2). There were many benefits to the RoCEv1 protocol. It allowed for ethernet compatibility, efficient data transfer while reducing latency and CPU utilization. This created a unique opportunity to create small local network environments supported over an Infiniband fiber based switch fabric. Works great in small clustering, but scaling the solution is very limited and expensive. Additional detractors include RoCEv1’s lack of IP routing (L3) support makes it obsolete for large data network deployments. Because of its need for lossless ethernet, it was also extremely complex to configure and manage when performing that limited scaling.

**Round two with RoCEv2**

Eventually, a need arose for a more flexible ethernet based environment that was truly high scale. There was a growing demand for an efficient and cost effective network ecosystem for RDMA based applications.  In 2014, Infiniband specification version 1.3 was introduced to support IP routing, known as RoCEv2. RoCEv2, unlike RoCEv1,  uses UDP/IP to be routable across different subnets, allowing for larger network scales and a more budget-friendly alternative to traditional InfiniBand L2 environments while still meeting similar performance metrics. In addition, lessons learned over a decade afforded speed increases, enhanced security and new congestion control frameworks. RoCEv2 encapsulation in the form of UDP/IP packets for RDMA can and does provide an inherently lossy data transfer, but not without help.  It’s important to remember that building a lossless environment, in and of itself, can be a complex challenge.  To be able to have the scalability and provide packet transfers in transfer order requires careful tuning.  This is where Arista offers a strong competitive advantage in helping to reduce the complexity for our customers.

**Alphabet Soup**

There are many protocols to help with creating a lossless environment for reliable packet transfer. Explicit Congestion Notification (ECN) marks packets for endpoint notification of network congestion before buffers overflow. Priority-based Flow Control (PFC) is a link-level flow control mechanism that pauses traffic on specific priority queues rather than stopping all traffic on a link. Data Center Quantized Congestion Notification (DCQCN) is an end-to-end congestion control algorithm combining ECN and PFC functions for RoCEv2. Dynamic and Cluster Load Balancing (DLB and CLB) are also introduced for congestion management. DLB uses egress interface utilization as part of load-balancing calculation and makes flow polarization and overlap much less likely. CLB is an Arista specific solution, which expands congestion control by allowing leaf and spine switches to look at hardware tables for RoCE flow identification. This allows for flow tracking used in ECMP load-balancing to prevent polarization. Packet trimming is also used to trim packets vs dropping them to speed up notification to endpoints to retransmit the packets. All this built-in intelligence to traffic management provides a solution matched for every use case. 

**DoW and the Arista Advantage**

We know all of this sounds very complex and overwhelming, but Arista is ready to support Federal solutions and innovations with support for open standards, best practices documentation and world class Engineering support. Arista is already known for its industry leading quality in hardware and software with its single binary operating system, Extensible Operating System (EOS).  This is the core across our platform ecosystem that makes it all work.  Arista’s Engineering excellence over the years with the growth of AI/ML datacenter networking is now being leveraged within the DoW today. Arista has products with high radix port offerings and up to 800G speeds across our 7800/2780R-Series and 7060X-Series. Our switches are purpose built for premium lossless, high bandwidth and low latency networking for RDMA based solutions.  This, along with EOS, ease of acclimation to our products, support of traffic management solutions, adjustable buffer allocation schemes for RoCE deployments serve the DoW across most solutions.  Trust that Arista Federal is ready to meet your challenges at every step of the way. 

---

## __Webinars and Events__  

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
| __EOS__           | 4.36.0F <br> 4.35.3.1F <br> 4.35.3F <br> 4.23.10M | April 9th, 2026 <br> April 8th, 2026 <br> March 20th, 2026 <br> March 2nd, 2026 |
| __CVP__           | Portal 2026.1.0 <br> Appliance 7.1.0 <br> Sensor 1.3.0 | March 30th, 2026 <br> September 2nd, 2025 <br> December 5th, 2025 |
| __DMF__           | 8.6.3 | March 18th, 2026 |
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
* **runC** — [Security Advisory 0135](https://www.arista.com/en/support/advisories-notices/security-advisory/23784-security-advisory-0135){: target="_blank" } <br> *(April 7th, 2026)*

### **Field Notices**
* **CV-CUE Release Process** — [Field Notice 0125](https://www.arista.com/en/support/advisories-notices/field-notice/23698-field-notice-0125){: target="_blank" } <br> *(March 11th, 2026)*

<br>

[View All Latest Advisories & Notices](https://www.arista.com/en/support/advisories-notices){: .md-button .md-button--primary target="_blank" }

---




## __* Product Updates*__

![Image Placememt](img/Product_image.png)

*Stay up to date on all new Arista Product Releases, as well as End of Sale/End of Support Notices.*

### **New Product Releases** * **Q1 2026** — [Ask AVA - CloudVision as a Service (beta feature)](https://www.arista.io/help/articles/overview-core-tools-ask-ava){: target="_blank" }

###  **End of Sale / End of Software Support**
* **April 10th, 2026** — [CloudVision Portal 2024.3 Release Train](https://www.arista.com/en/support/advisories-notices/end-of-support/23791-end-of-software-support-for-cloudvision-portal-2024-3-release-train){: target="_blank" } 
* **April 10th, 2026** — [DCS-7280CR3K-36S Series Switches](https://www.arista.com/en/support/advisories-notices/end-of-sale/23790-end-of-sale-of-the-arista-dcs-7280cr3k-36s-series){: target="_blank" } 
* **April 10th, 2026** — [DCS-7280CR3K-48YC8 Series Switches](https://www.arista.com/en/support/advisories-notices/end-of-sale/23789-end-of-sale-of-the-arista-dcs-7280sr3k-48yc8-series){: target="_blank" } 
* **April 10th, 2026** — [DCS-7280CR3K-32P4, DCS-7280CR3K-32D4, DCS-7280CR3MK-32P4 Series Switches](https://www.arista.com/en/support/advisories-notices/end-of-sale/23788-end-of-sale-of-the-arista-dcs-7280cr3k-32p4-dcs-7280cr3k-32d4-and-dcs-7280cr3mk-32p4-series){: target="_blank" }
* **March 13th, 2026** — [EOS-4.30 Release Train](https://www.arista.com/en/support/advisories-notices/end-of-support/23728-end-of-software-support-for-eos-4-30){: target="_blank" } 

<br>

[View All Latest End of Sale & Support Notices](https://www.arista.com/en/support/advisories-notices/endofsale){: .md-button .md-button--primary target="_blank" }





---

## Don't Forget! 
Arista has revamped their certifications! The new **Arista Certified Engineer (ACE)** program is now organized by specific tracks like Cloud Data Center, Campus, and Automation to better align with your job role.

![Image Placememt](img/ACE.png)

[Start your ACE journey now](https://www.training.arista.com/){ .md-button .md-button--primary target="_blank" }

---


---
# *Feel Free to Reach Out To Us For Your Network Needs* 
<figure markdown>
![Image Placement](img/pictureOfNetworks.jpeg){: style="height:300px;width:800px"}  
    <figcaption></figcaption>
</figure>
We thank you for taking the time to read out newsletter today. Feel free to reach out to your SE or ASE for more information or questions regardsing your network operations. Until next month, have a good one! 
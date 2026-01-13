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


# Welcome to the January 2025 Edition of the Arista Federal Newsletter!
Hard to believe it's the beginning of 2026.  Seems like just a year ago it was the start of 2025! 

As we begin the new year, the Arista Federal team would like to wish you a Happy, Healthy, and Prosperous New Year. We appreciate the trust and partnership of our Federal customers and look forward to supporting your priorities in the year ahead.

Arista is a recognized network leader, uniquely positioned to deliver best-in-class solutions across Campus, Data Center, WAN, and AI infrastructure. With a consistent operating model built on EOS, NetDL, and CloudVision, we help organizations simplify operations, improve reliability, and scale with confidence.

We’re excited to continue working alongside you to address the challenges and opportunities ahead and to support your mission with proven, cloud-scale networking solutions.

In this month’s newsletter, you’ll find:

- **Network Ops New Year’s Resolutions (That We Actually Intend to Keep)**
 -- Arista Federal Client Director Kevin Carey takes a thoughtful and lighthearted look at some of the top New Year’s resolutions for Network Operations teams and how they can be realistically achieved in the year ahead.

- **Arista: Building the Network Backbone for Next-Generation AI Training**
 -- Arista Technical Solutions Engineer Elumalai Neelamegam explores how Arista’s Ethernet-based AI infrastructure delivers scalable, proven results for organizations deploying Intel Habana Gaudi for AI training and why the network is central to performance, efficiency, and cost control.

This newsletter is for you and we welcome your feedback, ideas, and requests at fed@aristafederal.com

---

## **Arista Blog**

[![Image Placement][3]][4]
[3]: img/blog.png
[4]: https://blogs.arista.com/blog


---
## **Network Ops New Year’s Resolutions (That We Actually Intend to Keep)**
By Kevin Carey, Arista Federal Client Director

Happy New Year! This is the time of year when we all make New Year’s resolutions — some realistic, some optimistic, and a few that quietly assume everything will finally behave the way it’s supposed to. While not every resolution is easy, even the stretch goals are achievable with enough focus, discipline, and ideally, fewer surprises.

With that in mind, here’s a tongue-in-cheek look at a set of New Year’s resolutions inspired by Network Operations teams. These goals are absolutely attainable, especially with a little help from Arista.

As for our own resolution, it’s simple: continue demonstrating to our Federal customers how Arista delivers exceptional value through a consistent network operating system (EOS), consistent state management (NetDL), and consistent operations with CloudVision. If we meet our resolution, achieving yours should become a whole lot easier.

**Network Ops New Year’s Resolutions**

**(That We Actually Intend to Keep)**

**Resolution #1: “Not Everything Will Be an Emergency”**

**What We Want**

- Fewer last-minute changes

- More predictable operations

**Reality**

- If your fingers are on the CLI at 2 a.m., something has already gone wrong.

**How Arista Helps**

- State-based automation

- Validated changes with easy rollback

- ***Fewer keystrokes. Fewer regrets.***

**Resolution #2: “We’ll Know About Problems Before Leadership Does”**

**What We Want**

- Real-time awareness

- Fewer uncomfortable meetings

**Reality**

- Users should never be your alerting system.

**How Arista Helps**

- Real-time streaming telemetry

- Proactive alerts before users notice

- Network-wide visibility instead of device-by-device guessing

- ***For once, the network tells you first.***

**Resolution #3: “We’ll Stop Asking ‘Who Changed This?’”**

**What We Want**

- Clear audit trails

- Faster root-cause analysis

**Reality**

- Nothing says “fun” like diffing configs during an outage.
How Arista Helps

- Full configuration and state history in CloudVision

- Time-travel troubleshooting (yes, really)

- Instant visibility into who changed what and when

- ***Blame-free root cause analysis (mostly).***

**Resolution #4: “We Will Stop Copy-Pasting Configs from Old Projects”**

**Reality**

- That config from 2017 probably still works… probably.

**How Arista Helps**

- Arista Validated Designs (AVD) for standardized deployments

- Infrastructure-as-code with Git-based workflows

- Repeatable, testable network builds

- ***Consistency beats tribal knowledge.***

**Resolution #5: “We Will Make the Network… Boring (In a Good Way)”**

**What We Want**

- Fewer incidents

- More mission focus

**Reality**

- A boring network is a happy network.

**How Arista Helps**

- Single EOS across Campus, Data Center, WAN/Branch/Edge, Internet and Core, and Public Cloud

- Non-disruptive upgrades

- Deterministic, predictable behavior at scale

- ***When the network is boring, Ops gets to sleep.***

**Bonus Resolution: “We Will Go Home on Time”**

**Reality**

- Networks with high CVE exposure and unnecessary complexity require constant hands-on attention often at nights and on weekends.

**How Arista Helps**

- Automation reduces firefighting

- Fewer outages, faster fixes

- A network that behaves the same way every time

- ***Because “always-on” shouldn’t mean “always-on-call.”***

**Bottom Line**

Arista helps Federal and DoD network teams spend less time fighting the network and more time supporting the mission. By simplifying operations, improving visibility, and enabling automation at scale, Arista helps Network Ops teams actually keep their New Year’s resolutions without the drama.

**Arista Federal wishes you a Happy, Healthy, and Prosperous New Year!**

---
## **Arista - Building the Network Backbone for Next-Generation AI Training**
By Elumalai Neelamegam - Arista Technical Solutions Engineer

The AI revolution isn't just about processors and storage—it's about the network that connects them. As organizations scale their AI training infrastructure with Intel Habana Gaudi processors, the network becomes the critical enabler of performance, efficiency, and cost-effectiveness.

**The AI Training Challenge:**

Today's AI teams face mounting pressure. According to IDC research, 74% of organizations run 5-10 iterations to train a single model, with 50% rebuilding models weekly or more frequently. This explosion in training workloads demands infrastructure that can scale efficiently without breaking the budget.

The answer lies in a fully integrated approach and the network is where it all comes together.

**Why Ethernet Wins for AI at Scale:**

Intel's Habana Gaudi processors broke new ground by integrating ten 100GbE RDMA over Converged Ethernet (RoCE) ports directly on-chip. This isn't just a technical detail, it's a fundamental shift that makes standard Ethernet the ideal fabric for AI training.

**The benefits are clear:**

Avoid vendor lock-in: Standard Ethernet eliminates proprietary networking constraints
Scale with flexibility: Use the same technology within servers and across racks
Lower total cost: Leverage commodity switches instead of specialized interconnects
Future-proof investments: Build on proven, evolving standards

**The Arista Advantage in AI Infrastructure:**

At Arista, we have designed our switching portfolio specifically for the demands of modern AI training. Our solutions power the reference architectures validated with DDN and Supermicro, delivering three distinct network layers:

**1. Gaudi Communication Network Switches**

Arista DCS-7060DX4-32: Purpose-built for processor-to-processor communication

32 ports of 400GbE connectivity in 1U
25.6 Tb/s non-blocking bandwidth
Sub-700ns latency for rapid gradient synchronization
Direct Gaudi-to-Gaudi communication that bypasses CPU overhead

**2. Storage & Cluster Management Network Switches**

Arista 7170-32C: Optimized for high-speed data transfer

32 ports of 100GbE connectivity in 1U
6.4 Tb/s non-blocking bandwidth
Sub-800ns latency
Multi-path redundancy for continuous data availability

**3. Management Network Switches**

Arista 7010T: Reliable infrastructure management

48 x 1GbE ports plus 4 x 10G SFP+ uplinks
Layer 3 capabilities for robust traffic management
Dedicated monitoring and control plane

**Real-World Performance:**

The validated reference architectures demonstrate impressive results. With just one AI400X2 storage appliance and four Supermicro X12 Gaudi AI servers connected through Arista switches, organizations achieve:

Over 90 GBps throughput per storage appliance
Linear scaling as compute nodes are added
Balanced, even performance distribution across all servers
Full network saturation on every link

This architecture scales seamlessly. Deployments with 32 servers and 5 storage appliances have achieved 450 GB/s read and 325 GB/s write throughput—and the architecture has been validated with up to 560 AI accelerator servers.

**The Economics of Standard Ethernet:**

Here's what many organizations miss: the network represents a significant portion of AI infrastructure costs. By embracing standard Ethernet with Gaudi processors, our customers typically see:

40% better price-performance compared to traditional AI compute solutions
Reduced power consumption through integrated networking
Lower ongoing operational costs with familiar management tools
Flexibility to scale incrementally as training demands grow

**Designing for Success:**

A well-architected AI training network follows these principles:

Non-blocking topology: Every path operates at full bandwidth without contention

Redundant connections: Multiple paths ensure continuous operation even during failures

Optimized placement: Strategic port connections minimize latency and maximize throughput

Simplified management: Unified network operations across all tiers

The reference architectures we have validated with DDN and Supermicro embody these principles, giving organizations a proven blueprint for deployment.

**Looking Ahead:**

As AI models grow more complex and training iterations accelerate, the network will become even more critical. The combination of standard Ethernet, purpose-built Arista switches, and Gaudi's integrated networking creates an infrastructure that's ready for tomorrow's challenges today.

**Organizations no longer need to choose between performance, scalability, and cost. With the right network foundation, they can have all three.**

Reference : https://www.ddn.com/resources/legacy/supermicro-x12-gaudi-ai-servers/

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
**Exposure of Network and Compute information to Support Edge Computing Applications**

- Meeting minutes: https://docs.google.com/document/d/1kJz6uNg3WtJo83cK8_29TyUkFJgehiBEdce7yVXw7Bs/edit?usp=sharing 
- IETF Side meeting wiki: https://wiki.ietf.org/en/meeting/119/sidemeetings#meeting-tuesday
- Topic: “Exposure of Communication and Compute information to Support Edge Computing Applications”
- When: Tuesday March 19, 17:00 -18:30 (Brisbane, Australia time) 
- Videoconference (in case you are not in Australia): https://ietf.webex.com/meet/ietfsidemeeting2
- Where: P6-7

​**Problem motivation.** As the industry has reached peak computational centralization, compute needs communication to scale through distributed computing. There is a need to have a forum to discuss how the two sides of the same coin (compute and communication) can be exposed to the application to make efficient service placement and selection decisions. This information exposure is to support several application lifecycle operations including compute and communication resource discovery, service deployment, service selection, and assurance. This is especially important at the edge of the network, where services such as distributed AI, XR/VR, vehicle networks (V2X), etc. need this compute and communication information to meet stringent performance requirements. Exposed information should also account for the application footprint reaching out to cellular networks and for trust capabilities.

**Agenda: (This agenda is still being developed)**

The agenda for this meeting will include talks and discussions covering the following topics:

- [10 minutes] "Joint Exposure of Network and Compute Information for Infrastructure-Aware Service Deployment".
    - Abstract: Service providers are starting to deploy computing capabilities across the network for hosting applications such as distributed AI workloads, AR/VR, vehicle networks, and IoT, among others. In this network-compute environment, knowing information about the underlying communication and compute resources is necessary to properly deploy and operate these applications. 
    - Speaker: S. Randriamasy <sabine.randriamasy@nokia-bell-labs.com>, L. M. Contreras <luismiguel.contrerasmurillo@telefonica.com>,  Jordi Ros-Giralt<jros@qti.qualcomm.com>, Roland Schott <Roland.Schott@telekom.de>.
- [10 minutes] "Computing in the Network Needs Network/Compute Information Exposure".
    - Abstract: Computing in the network adds a new dimension to edge computing as compute and network resources become increasingly intertwined. Hence, exposing information on compute and network capacities and capabilities becomes crucial for a holistic system orchestration as we will sketch in this presentation..
    - Speaker: Ike Kunze <ike.kunze@comsys.rwth-aachen.de>
- [10 minutes] "Selection of Services and related Metrics".
    - Abstract: The presentation will highlight the need to consider different levels of granularity & abstraction that can be used to select the decision metrics. It will also propose a modular approach to combine and adapt metrics to jointly select egress routers and edge servers (or their LB) depending on context.
    - Speaker: Sabine Randriamasy <sabine.randriamasy@nokia-bell-labs.com>
- [10 minutes] "xxx".
    - Abstract: xxx.
    - Speaker: Nitinder Mohan <mohan@in.tum.de>
- [10 minutes] "Mangrove: A Unified Framework for Internet Topology, Routing Abstraction, and Modeling".
    - Abstract: xxx.
    - Speaker: Y. R. Yang, B. L. Lewis, D. M. Mertus, A. S. Shi, J. Z. Zhang, Richard Yang <yry@cs.yale.edu>
- [10 minutes] "MoWIE for Network Aware Application".
    - Abstract: xxx.
    - Speaker: Daniel Mertus <daniel.mertus@yale.edu>, Sabine Randriamasy <sabine.randriamasy@nokia-bell-labs.com>, Richard Yang <yry@cs.yale.edu>
    
- [20 mins] Discussion. Questions that we want to address in this side meeting (to be added soon):
    - Q1. For this effort/group, what mechanisms of exposure are in scope?
        - On-path vs off-path
        - Leveraging existing IETF solutions vs developing APIs
    - Q2. Right trade-off between transparency, security, optimal performance.
    - Q3. Next steps:
        - Does this work fit in a existing WG?
        - New WG?
        - New RG?
    - Q4. xxx

**Related work:**

- Exposure of network and compute capabilities for service placement and selection.
    - https://datatracker.ietf.org/doc/draft-rcr-opsawg-operational-compute-metrics/ 
    - https://datatracker.ietf.org/doc/draft-contreras-alto-service-edge/
    - https://www.ietf.org/archive/id/draft-lcsr-alto-service-functions-02.txt   
    - https://datatracker.ietf.org/meeting/117/materials/slides-117-alto-compute-information-retrieval-and-exposure-01 
- Cellular information exposure to edge computing applications.
    - https://datatracker.ietf.org/doc/html/draft-li-alto-cellular-use-cases
- Security information exposure for trust modeling and measurement
    - https://datatracker.ietf.org/meeting/interim-2023-alto-05/session/alto
- Southbound mechanisms to obtain network Information
    - https://datatracker.ietf.org/meeting/117/materials/slides-117-alto-alto-southbound-implementation-02 

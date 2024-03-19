**Exposure of Network and Compute information to Support Edge Computing Applications**

- Meeting minutes: https://notes.ietf.org/m6f4FrwpR_iLkkudH8qioQ
- IETF Side meeting wiki: https://wiki.ietf.org/en/meeting/119/sidemeetings#meeting-tuesday
- Topic: “Exposure of Communication and Compute information to Support Edge Computing Applications”
- When: Tuesday March 19, 17:00 -18:30 (Brisbane, Australia time) 
- Videoconference (in case you are not in Australia): https://ietf.webex.com/meet/ietfsidemeeting2
- Where: P6-7

​**Problem motivation.** As the industry has reached peak computational centralization, compute needs communication to scale through distributed computing. There is a need to have a forum to discuss how the two sides of the same coin (compute and communication) can be exposed to the application to make efficient service placement and selection decisions. This information exposure is to support several application lifecycle operations including compute and communication resource discovery, service deployment, service selection, and assurance. This is especially important at the edge of the network, where services such as distributed AI, XR/VR, vehicle networks (V2X), etc. need this compute and communication information to meet stringent performance requirements. Exposed information should also account for the application footprint reaching out to cellular networks and for trust capabilities.

**Agenda:**

The agenda for this meeting will include talks and discussions covering the following topics:

- [10 minutes] "Joint Exposure of Network and Compute Information for Infrastructure-Aware Service Deployment".
    - Abstract: Service providers are starting to deploy computing capabilities across the network for hosting applications such as distributed AI workloads, AR/VR, vehicle networks, and IoT, among others. In this network-compute environment, knowing information about the underlying communication and compute resources is necessary to properly deploy and operate these applications. 
    - Speaker: S. Randriamasy <sabine.randriamasy@nokia-bell-labs.com>, L. M. Contreras <luismiguel.contrerasmurillo@telefonica.com>,  Jordi Ros-Giralt<jros@qti.qualcomm.com>, Roland Schott <Roland.Schott@telekom.de>.
- [10 minutes] "ALTO integration with Kafka and future plans".
    - Abstract: We will present Telefonica's integration of ALTO and Kafka for information exposure.
    - Speaker: L. M. Contreras <luismiguel.contrerasmurillo@telefonica.com>
- [10 minutes] "Selection of Services and relation to compute metrics".
    - Abstract: The presentation will highlight the need to consider different levels of granularity & abstraction that can be used to select the decision metrics. It will also propose a modular approach to combine and adapt metrics to jointly select egress routers and edge servers (or their LB) depending on context.
    - Speaker: Sabine Randriamasy <sabine.randriamasy@nokia-bell-labs.com>
- [10 minutes] "Computing in the Network Needs Network/Compute Information Exposure".
    - Abstract: Computing in the network adds a new dimension to edge computing as compute and network resources become increasingly intertwined. Hence, exposing information on compute and network capacities and capabilities becomes crucial for a holistic system orchestration as we will sketch in this presentation.
    - Speaker: Ike Kunze <ike.kunze@comsys.rwth-aachen.de>
- [10 minutes] "Making Orchestration Application Aware: A Case for Augmented Reality at the Edge".
    - Abstract: Distributed interactive applications, particularly Augmented Reality (AR), necessitate edge computing for their stringent latency and high data rate demands, yet orchestrating their microservices is complex due to reliance on imprecise estimations of application performance via infrastructure metrics. Our extensive experiments reveal that these estimations often fail to accurately reflect actual performance, occasionally showing an inverse relationship. In this talk, we will discuss our sidecar approach which allows applications to convey crucial internal performance metrics to the orchestrator, enabling more effective service deployment and scheduling.
    - Speaker: Giovanni Bartolomeo (giovanni.bartolomeo@tum.de), Nitinder Mohan (mohan@in.tum.de), Jörg Ott (ott@in.tum.de)
- [10 minutes] "Mangrove: A Unified Framework for Internet Topology, Routing Abstraction, and Modeling".
    - Abstract: This work describes a novel system called Mangrove for obtaining global visibility across the Internet.  It achieves this through constructing a comprehensive, unified representation of the Internet's topology and routing behavior by aggregating and indexing diverse data sources.
    - Speaker: Joseph Zhang, B. L. Lewis, D. M. Mertus, A. S. Shi, Dong Guo, Richard Yang <yry@cs.yale.edu>
- [10 minutes] "MoWIE for Network Aware Application".
    - Abstract: This work demonstrates, through realistic evaluations, that 5G mobile network information such as MCS (Modulation and Coding Scheme) can effectively expose the dynamics of the underlying network and can be made available to applications through MoWIE, so the applications can adapt key control knobs such as media codec schemes, encapsulation, and application layer processing to minimize QoE distortion.
    - Speaker: Daniel Mertus <daniel.mertus@yale.edu>, Sabine Randriamasy <sabine.randriamasy@nokia-bell-labs.com>, Richard Yang <yry@cs.yale.edu>
- [30 mins] Discussion. Questions that we want to address in this side meeting (to be added soon):
    - Q1. **Focus**. Defining the scope/bounderies of this effort:
        - E.g., on-path vs off-path
        - Leveraging existing RFCs for information exposure (e.g., ALTO) vs creating new work
    - Q2. **Existing work**. Are you aware of this topic being addressed in any other WG?
    - Q3. **Way forward**. Is there interest in moving this work forward? In which way? 
        - Mailing list.
        - Within another WG? 
        - BOF?

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
- Distributed Mobile Augmented Reality Applications at the Edge:
    - https://dl.acm.org/doi/10.1145/3624354.3630584

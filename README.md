**Agenda**

- Meeting minutes: https://docs.google.com/document/d/1wCuU6uam_Yso8jPsIgrvxWuXl_DwpbnDBip5JFpzGdo/edit?usp=sharing 
- IETF Side meeting wiki: https://wiki.ietf.org/en/meeting/118/sidemeetings#Wednesday
- Topic: “Exposure of Communication and Compute information to Support Edge Computing Applications”
- When: Wed Nov 8, 15:30 -17:00, 
- Where: Karlin 4
- If you are remote: [Click here to join the meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_ZjYxOGE0ZjYtYWRjMC00MzkxLTg1YTQtZmEyZDY1N2NlYjIx%40thread.v2/0?context=%7b%22Tid%22%3a%22a19f121d-81e1-4858-a9d8-736e267fd4c7%22%2c%22Oid%22%3a%22fca5f38d-5297-46aa-b455-d0973e7cb68a%22%7d)

**Problem motivation.** As the industry has reached peak computational centralization, compute needs communication to scale through distributed 
computing. There is a need to have a forum to discuss how the two sides of the same coin (compute and communication) can be exposed to the 
application to make efficient service placement and selection decisions. This is especially important at the edge of the network, 
where services such as distributed AI, XR/VR, vehicle networks (V2X), etc. need this compute and communication information to be 
efficiently deployed and managed. Exposed information should also account for the application footprint reaching out to cellular 
networks and for trust capabilities exposure. 

The agenda for this meeting will include talks and discussions covering the following topics:

- [25 mins] Compute information exposure for service placement and selection.
- Related considerations:
    - [5 mins] Cellular information exposure to Internet applications.
    - [15 mins] Security information exposure for trust modelling and measurement.
    - [10 mins] Southbound mechanisms to obtain network and compute information.
- [35 mins] Discussion. Questions that we want to address:
    - Q1. Is it likely/viable that the network can expose communication and compute information to the service provider and application?
    - Q2. Are there gaps in the entire service lifecycle (deployment/instantiation/selection) that are not currently being addressed in the IETF and that are relevant?
    - Q3. Would it make sense to define a common set of communication and compute metrics to support the various use cases being served in the IETF?
    - Q4. If so, where should this effort be carried out within the IETF?

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

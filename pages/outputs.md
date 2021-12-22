---
title: Outputs
description:
background: /assets/img/chuttersnap-146799-unsplash.jpg
permalink: /outputs/
---

The research outputs from PAStor will be disseminated through top scientific venues in the HPC and storage fields and released as an open-source prototype. The prototype will provide the first building block towards a novel storage architecture suited for exascale computing infrastructures. The project will include both senior researchers and students who are working on PhD and MSc thesis focused on the scope of the project.

This page will be updated during the project duration.

---
#### Publications

* Macedo R, Correia C, Dantas M, Brito C, Xu W, Tanimura Y, Haga J, Paulo J. The Case for Storage Optimization Decoupling in Deep Learning Frameworks. Workshop on Re-envisioning Extreme-Scale I/O for Emerging Hybrid HPC Workloads (REX-IO), colocated with IEEE Cluster. 2021

* Dantas M, Leitão D, Correia C, Macedo R, Xu W, Paulo J. Monarch: Hierarchical Storage Management for Deep Learning Frameworks. . Workshop on Re-envisioning Extreme-Scale I/O for Emerging Hybrid HPC Workloads (REX-IO), colocated with IEEE Cluster. 2021

* Miranda M, Esteves T, Portela B, Paulo J. S2Dedup: SGX-enabled Secure Deduplication. ACM International Systems and Storage Conference (SYSTOR). 2021

* Macedo R, Tanimura Y, Haga J, Chidambaram V, Pereira J., Paulo J. PAIO: A Software-Defined Storage Data Plane Framework. ArXiv – Computing Research Repository (CoRR), 2021. 


----
#### Thesis

* Ricardo Macedo, PhD Thesis - Towards a Dependable and Decentralized Software-Defined Storage Architecture (on-going).
* Marco Dantas, MSc Thesis - Accelerating Deep Learning Training through Transparent Storage Tiering (on-going).
* Cláudia Correia, MSc Thesis - PRISMA: A Prefetching Storage Middleware for Accelerating Deep Learning Frameworks, 2021.

----
#### Talks

* Presentation of PAStor outputs at the Webinar Series *On the Road to HPC: Major Challenges and New Opportunities*.  Title of the talk: *Is HPC ready for “Big” Data Storage?*. Video recording available [here](https://www.youtube.com/watch?v=IqDrwYyB8Oc&t=2s).

* PAStor's presentation at UT Austin Portugal Program's workshop "Better prepared: Strengthening societies through international scientific collaboration". Collocated with Encontro Ciência'21 in Lisbon, Portugal.

---
#### Prototypes

* [Monarch](https://github.com/dsrhaslab/monarch) a framework-agnostic middleware for hierarchical storage management. This solution leverages the existing storage tiers present at modern supercomputers (e.g., compute node’s local storage, PFS) to improve DL training performance and alleviate the current I/O pressure of the shared PFS

* [S2Dedup](https://github.com/mmm97/S2Dedup) leverages intel SGX to enable privacy-preserving deduplication at untrusted servers. The open-source prototype, built with SPDK, supports multiple secure schemes. Deduplication is more and more used to optimize the performance and reduce the storage costs of Big Data applications (e.g., Deep Learning frameworks) that deal with large quantities of information. Our solution enables this technique at third-party infrastructures, such as HPC centers, without compromising the privacy of users’ sensitive data.

---

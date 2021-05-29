---
layout: resume
title: Sung-Han Lin's Resume
---
# Sung-Han Lin

<div id="webaddress">
<ul>
<li><a href="mailto:sunghlin@gmail.com">sunghanl@fb.com</a></li>
<li>+1-213-810-2139</li>
<li><a href="https://sunghlin.github.io/about">sunghlin.github.io</a></li>
</ul>
</div>

## Education

`2010 – 2017`
Ph.D. in Computer Science - *University of Southern California*, Los Angeles, California, U.S.A.

- Dissertation: __Distributed Resource Management for QoS-Aware Service Provision__
- Teaching Assistant, __CSci 402: Operating Systems__, Fall 2012 - Summer 2017

`2002 – 2008`
B.S. and M.S. in Computer Science (CSIE) - *National Taiwan University*, Taipei, Taiwan

- Master Thesis: __On the Design of Vehicular P2P Scheme over Ad Hoc Network and the Internet__

## Work Experience

`January 2021 - Present`
Performance and Capacity Engineer - *Facebook*

- __Improving Inference Performance__: [*Python*, *Caffe2*, *PyTorch*]
   - Migrating the inferencing model from CPU to the accelerators

`October 2017 - January 2021`
Performance Analysis Engineer & Data Scientist - *NetApp Inc.*

- __ONTAP AI: Improving GPU Data Pipeline__: [*Python*, *TensorFlow*, *Horovod*, *Container*, *MPI*, *Kubernetes*, *S3*]
   - Designed and Deployed the ML/DL reference architecture combining NVIDIA DGX systems and NetApp storage systems for distributed TensorFlow training and inference over the RoCE connections.
   - Identified the bottleneck of the end-to-end data pipelines; improved the GPU utilization, data feeding rate, and training speed via better configuring the CPU workload and multithreading, the GPU memory usage, and network interconnections, mainly on image recognition training and inference (*ResNet*, *VGG*, *Inception*).
   - Adopted NVIDIA NGC and libraries to build our reference architecture; implemented and optimized ML/DL training models, and published joined Technical Report with NVIDIA on various verticals - autonomous vehicle (*Mask-R-CNN*), financial (*Semi-supervised GAN*, *Auto-Encoder*), and conversational AI (*BERT*).
- __Data Operation Failover__: Built the automation and investigated the executing path of failover, where the secondary cluster takes over the write operations from the primary cluster; helped reduce the I/O resumption latency via improving the logic of triggering failover and reducing the function overhead. [*C/C++*, *Python*]
- __Synchronous Replication__: Built the automation and investigated the latency of replicating write operations to the remote cluster synchronously; helped reduce the overhead of transmission via identifying the bottleneck and improving the concurrency of parallel operations. [*C/C++*, *Tcl*, *Python*]
- __Advanced Block Fetching__: Investigated the block prefetching strategies to reduce the read overhead and latency caused by the new checksum mechanism for disks; improved the read throughput by 20\%. [*C/C++*]

`June 2014 - August 2014`
Intern - *Teradata*

- __Improving SQL-MapReduce Execution Engine__:  Redesigned and implemented the data buffering and transmission mechanisms to improve the query throughput by 15% via reducing the I/O latency and function overhead between user defined functions and databases. [*C/C++*, *Hadoop*, *SQL*]

`May 2013 - August 2013`
Intern - *Fuji Xerox Palo Alto (FXPAL) Laboratory*

- __Media Wall__: Designed and Developed media wall framework that instantiates and controls virtual machines to enable diversified screen presentations that are not limited by pre-installed projectors.

`October 2009 - July 2010`
Research Assistant, Leader of NSC Projects - *National Taiwan University - Department of Computer Science and Information Engineering*

- __Implement a distributed large-scale Digital Signage system__: Developed a partial storage system for video contents and advertisements by combining Content Distribution
Network and Peer-to-Peer technologies; Designed interest measurement functions to predict and distribute preferred contents according to customer
interactions with Digital Signage clients and customer popularity.

`September 2006 - September 2007`
Research Assistant, Web Designer - *National Taiwan University - Department of Foreign Languages and Literatures*

- __Interactive Video Learning__: Designed and programmed the interactive website to help English language teachers training students in English skills. Coded a web-based video player capable of switching audio tracks and displaying synced transcripts.

## Publications

- __On the Economic Sustainability of Cloud Sharing Systems Are Dynamic Single Resource Sharing Markets Stable?__, Ranjan Pal, Aditya Ahuja, *Sung-Han Lin*, Abhishek Kumar, Leana Golubchik, Nachikethas A Jagadeesan, ACM SIGMETRICS Performance Evaluation Review, 2019
- __Are Federated Cloud Sharing Systems Sustainable?: On Dynamic Sharing Markets and Their Stability__, Ranjan Pal, Aditya Ahuja, *Sung-Han Lin*, Nachikethas Jagadeesan, Abhishek Kumar, Leana Golubchik, IEEE Transactions on Sustainable Computing, 2019
- __A Model-based Approach to Streamlining Distributed Training for Asynchronous SGD__, *Sung-Han Lin*, Marco Paolieri, Cheng-Fu Chou, Leana Golubchik, IEEE Symposium on Modelling, Analysis, and Simulation of Computer and Telecommunication Systems (MASCOTS), 2018
- __Performance Driven Resource Sharing Markets for the Small Cloud__, *Sung-Han Lin*, Ranjan Pal, Marco Paolieri, Leana Golubchik, IEEE International Conference on Distributed Computing Systems (ICDCS), 2017
- __The Cloudlet Bazaar Dynamic Markets for the Small Cloud__, Ranjan Pal, *Sung-Han Lin*, Leana Golubchik, arXiv preprint arXiv:1704.00845, 2017
- __SC-Share: Performance Driven Resource Sharing Markets for the Small Cloud__, *Sung-Han Lin*, Ranjan Pal, Marco Paolieri, Leana Golubchik, arXiv preprint arXiv:1703.10318, 2017
- __On a Market-Driven Hybrid P2P Video Streaming Approach__, *Sung-Han Lin*, Ranjan Pal, Bo-Chun Wang, Leana Golubchik, IEEE Transactions on Multimedia, 2017, Issue Date: May.2017, Volume: 19, Issue: 5, pages: 1-15
- __Sustaining Ad-Driven P2P Streaming Ecosystems A Market-Based Approach__, *Sung-Han Lin*, Ranjan Pal, Bo-Chun Wang, Leana Golubchik, IEEE/ACM International Symposium on Quality of Service (IWQoS), 2015
- __Novel Social Cluster-based P2P Framework for Integrating VANETs with the Internet__, *Sung-Han Lin*, Junn-Yen Hu, Cheng-Fu Chou, Ing-Chau Chang, Chien-Chun Hung, in IEEE Wireless Communications and Networking Conference, 2009
- __Performance Study of Optimal Routing and Channel Assignment in Wireless Mesh Networks__, Ching-Ju Lin, *Sung-Han Lin*, Cheng-Fu Chou, in GLOBECOM 2007

## Research Projects

- __Throughput Maximization for Large-scale Deep Learning__: Analyzed the traffic pattern of the Asynchronous SGD training in the parameter-server architecture, and built a queueing network model to estimate the training speed (examples processed per second) of distributed TensorFlow GPU training jobs; leveraged the estimation model to address a problem of scheduling heterogeneous distributed DNN training jobs in a shared cluster.
- __Performance Driven Resource Sharing Markets for the Small Cloud__: Approximated an exponential growth stochastic model via Transient Analysis to estimate the number of virtual machines
exchanged within the cloud federation; Developed market-based game-theoretic model that converges to efficient VM sharing decisions at market equilibrium
- __On a Market-Driven Hybrid P2P Video Streaming Approach__: Re-designed sharing mechanisms to eliminate the problem of video playback pauses by up to 80 % while providing sufficiently high quality of videos to peers; Developed market-based game-theoretic model that uses advertisements as an incentive to satisfy all the market stakeholders
- __Speed up loading large data sets to a Facebook-like system on Cassandra__: Built Cassandra clusters with small-scale OpenStack virtual machines suitable for social network systems. Designed and
Coded mechanisms equally distributing the workload to all running virtual machines 
- __Implemented a real P2P IPTV system__: Coded P2P Internet Protocol Television (IPTV) systems supporting channel browsing in Windows systems.
- __Performance Analysis for the Speed-Sensitive Channel Assignment in Cellular Networks__: Developed probability models to analyze the performance of channel assignment with rapid cell phone hand-offs.

## Patent

- __Network resource allocation system and method of the same__, Cheng-Fu Chou, Ching-Ju Lin, *Sung-Han Lin*, US Patent 8,116,324

## Talk Presentation

- __Data Pipeline and Performance Considerations for NetApp AI__, NetApp INSIGHT Digital Event, 2020
- __AI Infrastructure for Real-World Use Cases from NetApp and NVIDIA (Presented by NetApp)__, GPU Technology Conference (GTC), 2020
- __Performance Considerations for AI and ML Deployments__, NetApp INSIGHT Las Vegas, 2019

## Paper Reviewer

- IEEE Transactions on Management Information Systems (TMIS): 2020
- IEEE Transactions on Services Computing (TSC): 2016
- ACM SIGMETRICS: 2013, 2015, 2016
- IFIP Performance: 2013, 2014
- International Conference on Quantitative Evaluation of SysTems (QEST): 2014

## Skills
- Proficiency in software development in C/C++, Perl, Python, Shell Scripts, HTML/CSS, JavaScript, Tcl, JAVA
- Familiarity with TensorFlow, Horovod, Container, MPI, Kubernetes, SQL, S3, Caffe2, PyTorch, Hadoop, Sockets, Matlab, PHP, UNIX, GNU/Linux, Solaris
<!-- ### Footer Last updated: May 2013 -->

## Articles and/or books I have authored

- __NetApp ONTAP AI Reference Architecture for Healthcare: Diagnostic Imaging__

https://resources.nvidia.com/en-us-netapp/netapp-ontap-ai-ra-hc-wp?xs=204825

- __NetApp ONTAP AI with NVIDIA DGX A100 Systems and Mellanox Spectrum Ethernet Switches__

https://www.netapp.com/pdf.html?item=/media/21793-nva-1153-design.pdf

- __NetApp ONTAP AI with NVIDIA DGX A100 Systems__

https://www.netapp.com/pdf.html?item=/media/19432-nva-1151-design.pdf

- __NetApp Conversational AI Using NVIDIA Jarvis__

https://resources.nvidia.com/en-us-netapp/netapp-conv-ai-jarvis-wp?xs=204826

- __NetApp Orchestration Solution with Run:AI__

https://docs.netapp.com/us-en/netapp-solutions/pdfs/sidebar/NetApp_Orchestration_Solution_with_Run_AI.pdf

- __NetApp ONTAP AI Reference Architecture for Financial Services Workloads__

https://www.netapp.com/pdf.html?item=/media/17205-tr4807pdf.pdf


## Scholarly/Research Papers Citing My Research

- __A novel social cluster-based p2p framework for integrating vanets with the internet__: 

(https://scholar.google.com/scholar?hl=en&cites=15425869088299533834)

[1] M. Ran and X. Bai, “Vehicle cooperative network model based on hypergraph in vehicular fog computing,” Sensors, vol. 20, no. 8, p. 2269, 2020.

[2] S. F. Abbas, W. Liu, Q. Bai, A. Al-Anbuky, A. Usman, et al., “Revealing the role of structural transitivity in building the sustainable community-aware vehicular social networks,” Vehicular Social Networks, p. 59, 2017.

[3] J. Garbiso, Fair auto-adaptive clustering for hybrid vehicular networks. PhD thesis, Telecom ParisTech, 2017.

[4] J. Garbiso, A. Diaconescu, M. Coupechoux, and B. Leroy, “Dynamic cluster size optimization in hybrid cellular-vehicular networks,” in 2016 ieee 19th international conference on intelligent transportation systems (itsc), pp. 557–563, IEEE, 2016.

[5] Z. Su, Q. Xu, and Y. Hui, “Edge caching to deliver mobile content in vehicular ad hoc networks,” in International Wireless Internet Conference, pp. 263–271, Springer, 2016.

[6] N. E. Hern´andez-Atonal, M. E. Rivero-Angeles, and F. Martinez-Pinon, “On the performance of s-aloha and csma/ca random access strategies for data exchange in query-based wireless sensor networks: An interest-based approach.,” Adhoc & Sensor Wireless Networks, vol. 32, no. 11, 2016.

[7] X. Yong et al., “Non-intermittent cooperative downloading approach for vanet,” Journal on Communications, vol. 37, no. 1, p. 180, 2016.

[8] Z. Su, P. Ren, and X. Gan, “A novel algorithm to cache vehicular content with parked vehicles applications,” in 2014 IEEE International Conference on Communications (ICC), pp. 5665–5669, IEEE, 2014.

[9] J. Liu, Y. Ge, S. Li, R. Shu, and S. Ding, “A transmission scheduling method of cooperative downloading for vehicular networking,” in 2014 14th International Symposium on Communications and Information Technologies (ISCIT), pp. 35–39, IEEE, 2014.

[10] A. Moravejosharieh and H. Modares, “A proxy mipv6 handover scheme for vehicular ad-hoc networks,” Wireless personal communications, vol. 75, no. 1, pp. 609–626, 2014.

[11] W. Junjun, W. Shuqi, S. Yongjun, C. Yiqi, L. Wei, and W. Di, “An incentive mechanism for cooperative downloading method in vanet,” in Proceedings of 2013 IEEE International Conference on Vehicular Electronics and Safety, pp. 125–130, IEEE, 2013.

[12] Z. SU and P. REN, “Efficient contents distribution approaches for vehicular networks,” connections, vol. 1, p. 2.

[13] J.-H. Liu, Y.-M. Ge, J.-P. Bi, S.-B. Li, and L. Guo, “Dynamic optimization model for cooperative downloading strategy of vanet,” , vol. 14, no. 6, pp. 963–971, 2013.

[14] M. Kakkasageri and S. S. Manvi, “Multiagent driven dynamic clustering of vehicles in vanets,” Journal of Network and Computer Applications, vol. 35, no. 6, pp. 1771–1780, 2012.

[15] J. Liu, Y. Ge, J. Bi, and L. Guo, “Cooperative downloading strategy on highway scenario,” in 2012 IEEE 12th International Conference on Computer and Information Technology, pp. 828–832, IEEE, 2012.

[16] Y. Huang, H. Du, and G. Zhang, “Clustering model of p2p cdn based on the prediction of user requirements,” Journal of Networks, vol. 7, no. 3, p. 532, 2012.

[17] H.-C. Jang and L.-J. Tzeng, “Affinity propagation with file similarity based clustering for p2p file sharing in vanet,” in The 15th International Symposium on Wireless Personal Multimedia Communications, pp. 70–74, IEEE, 2012.

[18] J. Guo, C. Hu, Y. Huo, Y. Liu, and L. Zhang, “Information sharing service in vanets with enhanced two-tier p2p communications,” in The 15th International Symposium on Wireless Personal Multimedia Communications, pp. 65–69, IEEE, 2012.

[19] N. E. Hern´andez-Atonal, F. Mart´ınez-Pi˜n´on, and M. E. Rivero-Angeles, “Performance analysis of random access strategies for short message exchange in vanets: A social approach,” in 2012 Seventh International Conference on Broadband, Wireless Computing, Communication and Applications, pp. 100–107, IEEE, 2012.

[20] Y.-S. Chen, C.-S. Hsu, and W.-H. Yi, “An ip passing protocol for vehicular ad hoc networks with network fragmentation,” Computers & Mathematics with Applications, vol. 63, no. 2, pp. 407–426, 2012.

[21] Z. Su, P. Ren, and Y. Chen, “Consistency control to manage dynamic contents over vehicular communication networks,” in 2011 IEEE Global Telecommunications ConferenceGLOBECOM 2011, pp. 1–5, IEEE, 2011.

[22] Z. Su, P. Ren, and Y. Chen, “Consistency control to manage dynamic,”

[23] H. Yongsheng, D. Huamei, and Z. Genglu, “Evolving model of p2p content distribution network based on the prediction of user requirements,” in Green Communications and Networks, pp. 1457–1465, Springer, 2012.

[24] B. Ramakrishnan, R. Rajesh, and R. Shaji, “Cbvanet: A cluster based vehicular adhoc network model for simple highway communication,” International Journal of Advanced Networking and Applications, vol. 2, no. 4, pp. 755–761, 2011.

[25] Z. Su, P. Ren, R. Xu, J. Katto, and Y. Yasuda, “A novel algorithm to control contents selectively for vehicular communication networks,” in 2010 IEEE 72nd Vehicular Technology Conference-Fall, pp. 1–2, IEEE, 2010.

[26] A. N. Tsapanoglou and D. P. Iracleous, “Fuzzy tuned gossip algorithms in mobile ad hoc networks,” in 2009 17th Mediterranean Conference on Control and Automation, pp. 276–279, IEEE, 2009.

[27] B. Ramakrishnan, “Performance analysis of aodv routing protocol in vehicular ad-hoc network service discovery architecture,” network, vol. 13, no. 14, pp. 65–72, 2009.

- __A model-based approach to streamlining distributed training for asynchronous SGD__:

(https://scholar.google.com/scholar?oi=bibs&hl=en&cites=12525575793754849352)

[1] M. Harchol-Balter, “Open problems in queueing theory inspired by datacenter computing,” Queueing Systems, vol. 97, no. 1, pp. 3–37, 2021.

[2] D. Albo Mart´ınez, S. Bobde, T. Motyka, and L. Chen, “Courier: Real-time optimal batch size prediction for latency slos in bigdl,” in Proceedings of the ACM/SPEC International Conference on Performance Engineering, pp. 133–144, 2021.

[3] S. Li, R. J. Walls, and T. Guo, “Characterizing and modeling distributed training with transient cloud gpu servers,” arXiv preprint arXiv:2004.03072, 2020.

[4] B. Berg, R. Vesilo, and M. Harchol-Balter, “hesrpt: Parallel scheduling to minimize mean slowdown,” Performance Evaluation, vol. 144, p. 102147, 2020.

[5] B. Berg, R. Vesilo, and M. Harchol-Balter, “hesrpt: Parallel scheduling to minimize mean slowdown,” ACM SIGMETRICS Performance Evaluation Review, vol. 48, no. 3, pp. 35–36, 2021.

[6] W. Wang, Q. Xie, and M. Harchol-Balter, “Zero queueing for multi-server jobs,” Proceedings of the ACM on Measurement and Analysis of Computing Systems, vol. 5, no. 1, pp. 1–25, 2021.

[7] L. Tang, X. He, P. Zhao, G. Zhao, Y. Zhou, and Q. Chen, “Virtual network function migration based on dynamic resource requirements prediction,” IEEE Access, vol. 7, pp. 112348–112362, 2019.

[8] Z. Li, W. Yan, M. Paolieri, and L. Golubchik, “Throughput prediction of asynchronous sgd in tensorflow,” in Proceedings of the ACM/SPEC International Conference on Performance Engineering, pp. 76–87, 2020.

[9] B. Berg, R. Vesilo, and M. Harchol-Balter, “hesrpt: Optimal scheduling of parallel jobs with known sizes,” ACM SIGMETRICS Performance Evaluation Review, vol. 47, no. 2, pp. 18–20, 2019.

- __Performance study of optimal routing and channel assignment in wireless mesh networks__:

(https://scholar.google.com/scholar?oi=bibs&hl=en&cites=11590442465747507778)

[1] M. E. Rasekh, Enabling next generation mobile communication via millimeter-wave technology. University of California, Santa Barbara, 2020.

[2] M. Eslami Rasekh, Enabling next generation mobile communication via millimeter-wave technology. PhD thesis, UC Santa Barbara, 2020.

[3] S. M. Kala, V. Sathya, M. P. K. Reddy, B. Lala, and B. R. Tamma, “A socio-inspired calm approach to channel assignment performance prediction and wmn capacity estimation,” Journal of Network and Computer Applications, vol. 125, pp. 42–66, 2019.

[4] M. E. Rasekh, D. Guo, and U. Madhow, “Joint routing and resource allocation for millimeter wave picocellular backhaul,” IEEE Transactions on Wireless Communications, vol. 19, no. 2, pp. 783–794, 2019.

[5] G. I. M. Dzal and S. Feng, “The dynamic channel assignment for multi-radio multi-channel wireless mesh networks,” in 2013 International Conference on Communication Systems and Network Technologies, pp. 277–280, IEEE, 2013.

[6] K. C.-J. Lin, S.-T. Shen, and C.-F. Chou, “Rate-loss based channel assignment in multirate wireless mesh networks,” in 2010 IEEE 71st Vehicular Technology Conference, pp. 1–5, IEEE, 2010.

[7] Y. Liu, R. Venkatesan, and C. Li, “Channel assignment exploiting partially overlapping channels for wireless mesh networks,” in GLOBECOM 2009-2009 IEEE Global Telecommunications Conference, pp. 1–5, IEEE, 2009.

[8] B. Zhou, Z. Zhao, Q. Chen, and A. Huang, “A hyacinth-based joint routing and channel assignment algorithm for multi-channel multi-interface wireless mesh networks,” in 2009 Fourth International Conference on Communications and Networking in China, pp. 1–5, IEEE, 2009.

[9] X. Li, K. Lee, and K. Lee, “A novel channel assignment in multi-radio multi-channel mesh network based on partial block mc-cdma,” in 2009 9th International Sy

- __On market-driven hybrid-P2P video streaming__:

(https://scholar.google.com/scholar?oi=bibs&hl=en&cites=1853495769485732220)

[1] S. Fujita, “Multi-tree-based peer-to-peer video streaming with a guaranteed latency,” IEICE TRANSACTIONS on Information and Systems, vol. 102, no. 9, pp. 1707–1714, 2019.

[2] M. Sina, M. Dehghan, and A. M. Rahmani, “Car-plive: Cloud-assisted reinforcement learning based p2p live video streaming: a hybrid approach,” Multimedia Tools and Applications, vol. 78, no. 23, pp. 34095–34127, 2019.

[3] J. Artback, “Comparison of video file transmission: over dat protocol and hypertext transfer protocol,” 2019.

[4] P. J. Braun, A. Budai, J. Levendovszky, M. Sipos, P. Ekler, and F. H. Fitzek, “Mobile peer-to-peer assisted coded streaming,” IEEE Access, vol. 7, pp. 159332–159346, 2019.

[5] S. Fujita, “Cloud-assisted peer-to-peer video streaming with minimum latency,” IEICE TRANSACTIONS on Information and Systems, vol. 102, no. 2, pp. 239–246, 2019.

[6] J. Ruohonen, J. Salovaara, and V. Lepp¨anen, “Crossing cross-domain paths in the current web,” in 2018 16th Annual Conference on Privacy, Security and Trust (PST), pp. 1–5, IEEE, 2018.

[7] G. Huang, Y. Gao, L. Kong, and K. Wu, “An incentive scheme based on bitrate adaptation for cloud-assisted p2p video-on-demand streaming systems,” in 2018 IEEE 3rd International Conference on Cloud Computing and Big Data Analysis (ICCCBDA), pp. 404–408, IEEE, 2018.

[8] W. Ma, Q. Zhang, C. Mu, and M. Zhang, “Qos prediction for neighbor selection via deep transfer collaborative filtering in video streaming p2p networks,” International Journal of Digital Multimedia Broadcasting, vol. 2019, 2019.

[9] G. Huang, L. Kong, K. Wu, and Z. Chen, “A service scheduling policy for improving playback quality of mesh-based p2p vod systems,” in 2017 IEEE International Symposium on Parallel and Distributed Processing with Applications and 2017 IEEE International Conference on Ubiquitous Computing and Communications (ISPA/IUCC), pp. 1311–1318, IEEE, 2017.

- __The cloudlet bazaar dynamic markets for the small cloud__:

(https://scholar.google.com/scholar?oi=bibs&hl=en&cites=1709139287780935909)

[1] U. Paul, J. Liu, S. Troia, O. Falowo, and G. Maier, “Traffic-profile and machine learning based regional data center design and operation for 5g network,” Journal of Communications and Networks, vol. 21, no. 6, pp. 569–583, 2019.

[2] P. Udita, L. Jiamo, S. Troia, F. Olabisi, and G. A. Maier, “Traffic-profile and machine learning based regional data center design and operation for 5g network,” 2019.

[3] A. S. Prasad, M. Arumaithurai, D. Koll, and X. Fu, “Dmc: A differential marketplace for cloud resources,” in 2019 19th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing (CCGRID), pp. 198–209, IEEE, 2019.

[4] A. S. R. Prasad, Automated Provisioning of Fairly Priced Resources. PhD thesis, Nieders¨achsische Staats-und Universit¨atsbibliothek G¨ottingen, 2018.

[5] F. Slim, Design and Implementation of Resource Allocation Algorithms for a Network Operating. PhD thesis, Ecole nationale sup´erieure Mines-T´el´ecom Atlantique, 2018.

[6] F. Slim, F. Guillemin, and Y. Hadjadj-Aoul, “On virtual network functions’ placement in future distributed edge cloud,” in 2017 IEEE 6th International Conference on Cloud Networking (CloudNet), pp. 1–4, IEEE, 2017.

[7] F. Slim, Etude et impl´ementation d’algorithmes de gestion de ressources pour un syst`emed’exploitation de r´eseau. PhD thesis, Ecole nationale sup´erieure Mines-T´el´ecom Atlantique Bretagne Pays de la Loire, 2018.

- __Performance driven resource sharing markets for the small cloud__:

(https://scholar.google.com/scholar?oi=bibs&hl=en&cites=15189202755616081924)

[1] R. Pal, A. Ahuja, S.-H. Lin, A. Kumar, L. Golubchik, and N. A. Jagadeesan, “On the economic sustainability of cloud sharing systems are dynamic single resource sharing markets stable?,” ACM SIGMETRICS Performance Evaluation Review, vol. 46, no. 4, pp. 2–10, 2019.

[2] R. Pal, S.-H. Lin, A. Ahuja, N. Jagadeesan, A. Kumar, and L. Golubchik, “Are federated cloud sharing systems sustainable?: On dynamic sharing markets and their stability,” IEEE Transactions on Sustainable Computing, vol. 5, no. 4, pp. 485–500, 2019.

[3] Z. Xiong, D. Niyato, P. Wang, Z. Han, and Y. Zhang, “Dynamic pricing for revenue maximization in mobile social data market with network effects,” IEEE Transactions on Wireless Communications, vol. 19, no. 3, pp. 1722–1737, 2019.

[4] S. Z. Goher, P. Bloodsworth, R. U. Rasool, and R. McClatchey, “Cloud provider capacity augmentation through automa
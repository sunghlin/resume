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

## Selected Work Experience

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

<!-- 
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
-->
## Selected Publications

- __On the Economic Sustainability of Cloud Sharing Systems Are Dynamic Single Resource Sharing Markets Stable?__, Ranjan Pal, Aditya Ahuja, *Sung-Han Lin*, Abhishek Kumar, Leana Golubchik, Nachikethas A Jagadeesan, ACM SIGMETRICS Performance Evaluation Review, 2019
- __Are Federated Cloud Sharing Systems Sustainable?: On Dynamic Sharing Markets and Their Stability__, Ranjan Pal, Aditya Ahuja, *Sung-Han Lin*, Nachikethas Jagadeesan, Abhishek Kumar, Leana Golubchik, IEEE Transactions on Sustainable Computing, 2019
- __A Model-based Approach to Streamlining Distributed Training for Asynchronous SGD__, *Sung-Han Lin*, Marco Paolieri, Cheng-Fu Chou, Leana Golubchik, IEEE Symposium on Modelling, Analysis, and Simulation of Computer and Telecommunication Systems (MASCOTS), 2018
- __Performance Driven Resource Sharing Markets for the Small Cloud__, *Sung-Han Lin*, Ranjan Pal, Marco Paolieri, Leana Golubchik, IEEE International Conference on Distributed Computing Systems (ICDCS), 2017
<!--
- __The Cloudlet Bazaar Dynamic Markets for the Small Cloud__, Ranjan Pal, *Sung-Han Lin*, Leana Golubchik, arXiv preprint arXiv:1704.00845, 2017
- __SC-Share: Performance Driven Resource Sharing Markets for the Small Cloud__, *Sung-Han Lin*, Ranjan Pal, Marco Paolieri, Leana Golubchik, arXiv preprint arXiv:1703.10318, 2017
-->
- __On a Market-Driven Hybrid P2P Video Streaming Approach__, *Sung-Han Lin*, Ranjan Pal, Bo-Chun Wang, Leana Golubchik, IEEE Transactions on Multimedia, 2017, Issue Date: May.2017, Volume: 19, Issue: 5, pages: 1-15
- __Sustaining Ad-Driven P2P Streaming Ecosystems A Market-Based Approach__, *Sung-Han Lin*, Ranjan Pal, Bo-Chun Wang, Leana Golubchik, IEEE/ACM International Symposium on Quality of Service (IWQoS), 2015
<!--
- __Novel Social Cluster-based P2P Framework for Integrating VANETs with the Internet__, *Sung-Han Lin*, Junn-Yen Hu, Cheng-Fu Chou, Ing-Chau Chang, Chien-Chun Hung, in IEEE Wireless Communications and Networking Conference, 2009
- __Performance Study of Optimal Routing and Channel Assignment in Wireless Mesh Networks__, Ching-Ju Lin, *Sung-Han Lin*, Cheng-Fu Chou, in GLOBECOM 2007
-->
<!--
## Research Projects

- __Throughput Maximization for Large-scale Deep Learning__: Analyzed the traffic pattern of the Asynchronous SGD training in the parameter-server architecture, and built a queueing network model to estimate the training speed (examples processed per second) of distributed TensorFlow GPU training jobs; leveraged the estimation model to address a problem of scheduling heterogeneous distributed DNN training jobs in a shared cluster.
- __Performance Driven Resource Sharing Markets for the Small Cloud__: Approximated an exponential growth stochastic model via Transient Analysis to estimate the number of virtual machines
exchanged within the cloud federation; Developed market-based game-theoretic model that converges to efficient VM sharing decisions at market equilibrium
- __On a Market-Driven Hybrid P2P Video Streaming Approach__: Re-designed sharing mechanisms to eliminate the problem of video playback pauses by up to 80 % while providing sufficiently high quality of videos to peers; Developed market-based game-theoretic model that uses advertisements as an incentive to satisfy all the market stakeholders
- __Speed up loading large data sets to a Facebook-like system on Cassandra__: Built Cassandra clusters with small-scale OpenStack virtual machines suitable for social network systems. Designed and
Coded mechanisms equally distributing the workload to all running virtual machines 
- __Implemented a real P2P IPTV system__: Coded P2P Internet Protocol Television (IPTV) systems supporting channel browsing in Windows systems.
- __Performance Analysis for the Speed-Sensitive Channel Assignment in Cellular Networks__: Developed probability models to analyze the performance of channel assignment with rapid cell phone hand-offs.
-->
## Patents

- __Network resource allocation system and method of the same__, Cheng-Fu Chou, Ching-Ju Lin, *Sung-Han Lin*, US Patent 8,116,324

## Talk Presentations

- __Data Pipeline and Performance Considerations for NetApp AI__, NetApp INSIGHT Digital Event, 2020
- __AI Infrastructure for Real-World Use Cases from NetApp and NVIDIA (Presented by NetApp)__, GPU Technology Conference (GTC), 2020
- __Performance Considerations for AI and ML Deployments__, NetApp INSIGHT Las Vegas, 2019

<!--
## Paper Reviewer

- IEEE Transactions on Management Information Systems (TMIS): 2020
- IEEE Transactions on Services Computing (TSC): 2016
- ACM SIGMETRICS: 2013, 2015, 2016
- IFIP Performance: 2013, 2014
- International Conference on Quantitative Evaluation of SysTems (QEST): 2014
-->
## Skills
- Proficiency in software development in C/C++, Perl, Python, Shell Scripts, HTML/CSS, JavaScript, Tcl, JAVA
- Familiarity with TensorFlow, Horovod, Container, MPI, Kubernetes, SQL, S3, Caffe2, PyTorch, Hadoop, Sockets, Matlab, PHP, UNIX, GNU/Linux, Solaris
<!-- ### Footer Last updated: May 2013 -->
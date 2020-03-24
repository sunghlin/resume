---
layout: resume
title: Sung-Han Lin's Resume
---
# Sung-Han Lin

<div id="webaddress">
<ul>
<li><a href="mailto:sunghlin@gmail.com">sunghlin@gmail.com</a></li>
<li>+1-213-810-2139</li>
<li><a href="https://sunghlin.github.io/about">https://sunghlin.github.io/about</a></li>
</ul>
</div>

## Education

`2010 – 2017`
Ph.D. in Computer Science - *University of Southern California*, Los Angeles, California, U.S.A.

- __Dissertation__: Distributed Resource Management for QoS-Aware Service Provision
- Teaching Assistant, __CSci 402: Operating Systems__, Fall 2012 - Summer 2017

`2002 – 2008`
B.S. and M.S. in Computer Science (CSIE) - *National Taiwan University*, Taipei, Taiwan

## Selected Work Experience

`October 2017 - Present`
Performance Analysis Engineer & Data Scientist - *NetApp Inc.*

- __Improving GPU Data Pipeline__: [*Python*, *TensorFlow*, *Horovod*, *Container*, *MPI*, *Kubernetes*, *S3*]
   - Designed and Deployed the AI/ML/DL reference architecture combining NVIDIA DGX systems and NetApp storage systems for distributed TensorFlow training and inference over the RoCE connections.
   - Identified the bottleneck of the end-to-end data pipelines; improved the GPU utilization, data feeding rate, and training speed via better configuring the CPU workload and multithreading, the GPU memory usage, and network interconnections, mainly on image recognition training and inferencing (ResNet, VGG, Inception).
   - Adopted NVIDIA NGC and libraries to build our reference architecture; implemented and optimized ML/DL training models, and published joined Technical Report with NVIDIA on various verticals - autonomous vehicle (Mask-R-CNN), financial (Semi-supervised GAN, Auto-Encoder), and health care (NVIDIA Clara).
- __Data Operation Failover__: Built the automation and investigated the executing path of failover, where the secondary clusters takes over the write operations from the primary cluster; helped reduce the latency via improving the logic of triggering failover and reducing the function overhead. [*C/C++*, *Python*]
- __Synchronous Replication__: Built the automation and investigated the latency of replicating write operations to the remote cluster synchronously; helped reduce the overhead of transmission via identifying the bottleneck and improving the concurrency of parallel operations. [*C/C++*, *Tcl*, *Python*]
- __Advanced Block Fetching__: Investigated the block prefetching strategies to reduce the read overhead and latency caused by the new checksum mechanism for disks; improved the read throughput by 20\%. [*C/C++*]

`June 2014 - August 2014`
Intern - *Teradata*

- __Improving SQL-MapReduce Execution Engine__:  Redesigned and implemented the data buffering and transmission mechanisms to improve the query throughput by 15% via reducing the I/O latency and function overhead between user defined functions and databases. [*C/C++*, *Hadoop*, *SQL*]

## Selected Publications

- __A Model-based Approach to Streamlining Distributed Training for Asynchronous SGD__, by *Sung-Han Lin*, Marco Paolieri, Cheng-Fu Chou, Leana Golubchik, IEEE MASCOTS, 2018
- __Performance Driven Resource Sharing Markets for the Small Cloud__, by *Sung-Han Lin*, Ranjan Pal, Marco Paolieri, Leana Golubchik, IEEE ICDCS, 2017
- __Sustaining Ad-Driven P2P Streaming Ecosystems A Market-Based Approach__, by *Sung-Han Lin*, Ranjan Pal, Bo-Chun Wang, Leana Golubchik, IEEE/ACM IWQoS, 2015

## Selected Research Projects

- __Throughput Estimation for Large-scale Deep Learning__: Analyzed the traffic pattern of Asynchronous SGD training in the parameter-server architecture, and built a queueing network model to estimate the training speed (examples processed per second) of distributed TensorFlow GPU training jobs; leveraged the estimation model to address a problem of scheduling heterogeneous distributed DNN training jobs in a computing cluster.

## Talk

- __Performance Considerations for AI and ML Deployments__, NetApp INSIGHT Las Vegas, October 2019
<!-- ### Footer Last updated: May 2013 -->



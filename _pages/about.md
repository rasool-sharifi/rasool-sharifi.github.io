---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
------
I am a third year Ph.D. student in the Computer Science Department of University of Virginia, working with Prof. Ashish Venkat on Computer Architecture. My research interests lie broadly in Computer Architecture, Compilers, and Computer Security. My research explores novel hardware and software techniques to design secure machines while maintaining performance, energy efficiency, and high programmability. I’m also interested in applying novel machine learning techniques to detect and mitigate security threats. I have extensive experience in designing high performance, energy efficient FPGA and embedded systems for core consumer products. You can find my CV [here](http://rasool-sharifi.github.io/files/RasoolSharifiCV.pdf). 

Research Projects
------
**Processors Architecture Support for Security Assurance**\
*Advised by Prof. Ashish Venkat*

This project explores methods to safeguard hardware against the seven classes of CWEs i.e., buffer errors; permissions; privileges and access; resource
management; code injection; information leakage; hardware/system on a chip implementation errors; and numeric errors) for an x86 architecture. The solution should allow for backward compatibility with legacy software and deliver suitable performance on multicore workloads. Additionally, the x86 processor model or range of models which would be best candidates for a prototype design should be identified, and the impacts of additional cyber security safeguards are to performance, power, and area should be projected. Monolithic, multi-die, and co-processor approaches are of interest as is the strongest level of cryptographic acceleration able to be incorporated into a solution.


**Processing in Memory for Bioinformatics Applications**\
*Advised by Prof. Kevin Skadron and Prof. Ashish Venkat*

The  field  of  bioinformatics  has  enabled  significant  advances in human health through its contributions to precision medicine, disease surveillance, population genetics, and many other critical applications. The centerpiece of a bioinformatic spipeline  is  genome  sequence  comparison  and  classification, which  involves  aligning  query  sequences  against  reference sequences,  with  the  goal  of  identifying  patterns  of  structural similarity  and  divergence. This work  explores the design space  for high-performance k-mer  matching  accelerators  that  use  logic  in  DRAM  as  the basis  for  acceleration,  including  the  most  aggressive  form  of processing-in-memory(PIM), in-situ computing, with the goal of  parallel  processing  of  sequence  data  within  DRAM  row buffers. 

**Speculation-Driven Dynamic Binary Optimization**\
*Advised by Prof. Ashish Venkat and Prof. Kevin Skadron*

This project explores dynamic binary optimization techniques at the processor level to speculatively generate and execute a super-optimized instruction stream, by leveraging established speculative processor features such as branch prediction, value prediction, and loop stream detection. This project introduces two distinct flavors of speculative super-optimization: (a) a hardware implementation that leverages dynamically predicted program state to perform simple, yet powerful peephole optimizations on short instruction sequences, and (b) a firmware implementation that leverages a microcode-based dynamic re-compiler running as a helper thread to perform more sophisticated optimizations. Owing to the plethora of speculative processor features and compiler/runtime/hardware optimizations to choose from, this project explores a rich sample space of speculative super-optimization strategies, along with extensive profitability analysis to dynamically identify appropriate targets for super-optimization.


Publications
------
**CHEx86: Context-Sensitive Enforcement of Memory Safety via Microcode-Enabled Capabilities**\
*2020 ACM/IEEE 47th Annual International Symposium on Computer Architecture (ISCA)* **(Acceptance Rate: 18%)**\
[[PDF]](http://rasool-sharifi.github.io/files/2020CHEx86.pdf) [[Video]](https://fast.wistia.net/embed/iframe/xrq0ht9iic)

**Online Profiling for Cluster-Specific Variable Rate Refreshing in High-Density DRAM Systems**\
*2017 22nd IEEE European Test Symposium (ETS)*\
[[PDF]](http://rasool-sharifi.github.io/files/2017OnlineProfiling.pdf)



---
title: "CVECenter: Industry Practice of Automated Vulnerability Management for Linux Distribution Community"
collection: publications
permalink: /publication/fse24cvecenter
date: 2024-05-14
venue: 'ACM International Conference on the Foundations of Software Engineering 2024 [FSE, CCF-A]'
paperurl: '*'
doi: '*'
pubtype: 'conference'
authors: 'Jing Luo, Heyuan Shi*, Yongchao Zhang, Runzhe Wang, Yuheng Shen, Yuao Chen, Rongkai Liu, Xiaohai Shi, Chao Hu, Yu Jiang'
excerpt_separator: ""
---


Vulnerability management is a time-consuming and labor-intensive task for Linux distribution maintainers. 

It involves the continuous identification, assessment, and fixing of vulnerabilities in Linux distributions.
Due to the complexity of the vulnerability management process and the gap between community requirements and existing tools, there is little systematic study on automated vulnerability management for Linux distributions.

In this paper, in collaboration with enterprise developers from Alibaba and maintainers from the Linux distribution community of OpenAnolis, we develop an automated vulnerability management system called CVECenter.

We conduct the industry practice on the 3 versions of Linux distribution, which are responsible for many business and cloud services. 
We address the following challenges in developing and applying CVECenter to the Linux distribution: multi-source heterogeneous vulnerability record inconsistency, large-scale vulnerability retrieval response delay, manual vulnerability assessment cost, vulnerability auto-fixing tools absence, and continuous vulnerability management complexity.

By CVECenter, we have successfully managed over 8,000 CVEs related to the Linux distribution and published a total of 1,157 security advisories, which reduces the mean time to fix vulnerabilities by 70\% compared to the traditional workflow of the Linux distribution community.

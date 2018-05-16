---
layout: default
---

# CALL FOR COMPETITION
The WoSAR community created the data competition on the idea of intersecting the capabilities of prediction and machine learning with the research topics of software aging and rejuvenation, calling both researchers and students. 
In this first edition, the WoSAR 2018 data competition is an issue tracker insights extraction challenge.

### Goal
The competition task is to conceive a system that enables practitioners to reveal insights from the [Linux kernel’s official bug repository](https://bugzilla.kernel.org/), useful to the software aging and rejuvenation research. 
Examples are:
* a classification system to determine the type of a Linux kernel bug;
* a prediction system to detect an aging-prone patch;
* an NLP system to correlate the life cycle of the bug with the sentiment extracted by the report comments.

_Adding your own insights is highly recommended_

The competitor (individual or team) must prepare a 2-pages report where they explain the approach, the system design, and the results. Furthermore, they should also add a reference to download the system code and how-to notes to reproduce the results. 

A jury of experts will find out the three best competitors, who will be invited to present their work at WoSAR 2018 in a special session.

### Dataset

The provided dataset consists of a CSV file where each row represents a bug report, and each column is a bug report field (see [link](https://bugzilla.kernel.org/page.cgi?id=fields.html)). 
In addictions to these columns, the dataset is enhanced with other fields such as the bug type and subtype. 

The classification and dataset used in this competition were presented at ISSRE 2017 by Xiao et al. [1], even if the dataset was kept unavailable to the public until now. The competitors can use any data other than the structured dataset provided, by querying the Linux kernel’s official bug repository with the bug ID. Other potential sources of information are report comments, applied patch, attached logs.

### Evaluation Criteria
The evaluation committee will evaluate the competitor based on:
* originality,
* results,
* impact, and 
* reproducibility of the work. 

### Evaluation Committee 
*To Be Defined...*

### Important Dates 

Dataset release [(WoSAR 2018 Data Competition Repository)](https://github.com/akiannillo/wosar2018competition): **May 15, 2018**

Submission Deadline: **July 21, 2018**

Notification: **August 13, 2018**

Submission of Camera-Ready Copy Deadline: **August 28, 2018**

The winner will be announced at the WoSAR 2018 Competition session.

### Submission

Submissions must be e-mailed to [ak.iannillo+wosar2018competition@gmail.com](mailto:ak.iannillo+wosar2018competition@gmail.com). 

The 2-page report must be written in English and be formatted according to the [IEEE authoring guidelines](www.ieee.org/conferences_events/conferences/publishing/templates.html)

Code must be accompained with a `howto.txt` file that explains how and lists the commands to use the system.
Preferably, the code could be shared through a GitHub repository link (in this case, commits after the deadline will be ignored).

***

[1] Xiao, G., Zheng, Z., Yin, B., Trivedi, K. S., Du, X., & Cai, K. (2017, October). Experience report: Fault triggers in Linux operating system: From evolution perspective. In Software Reliability Engineering (ISSRE), 2017 IEEE 28th International Symposium on (pp. 101-111). IEEE.

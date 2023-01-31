---
title: "DeepC2: AI-Powered Covert Command and Control on OSNs"
collection: publications
permalink: /publication/DeepC2_ICICS_2022
excerpt: 'We built a covert command and control channel using AI on OSNs.'
date: 2022-09-06
venue: 'The 24th International Conference on Information and Communications Security (ICICS 2022)'
paperurl: 'https://doi.org/10.1007/978-3-031-15777-6_22'
citation: 'Wang, Z., Liu, C., Cui, X., et al. (2022). DeepC2: AI-Powered Covert Command and Control on OSNs. In: Alcaraz, C., Chen, L., Li, S., Samarati, P. (eds) Information and Communications Security. ICICS 2022. Lecture Notes in Computer Science, vol 13407. Springer, Cham.'
---

[BIB](/files/DeepC2_springer.bib) [Paper](https://doi.org/10.1007/978-3-031-15777-6_22) [Code](https://github.com/oicid/DeepC2)

__Abstract__ Command and control (C&C) is important in an attack. It transfers commands from the attacker to the malware in the compromised hosts. Currently, some attackers use online social networks (OSNs) in C&C tasks. There are two main problems in the C&C on OSNs. First, the process for the malware to find the attacker is reversible. If the malware sample is analyzed by the defender, the attacker would be exposed before publishing the commands. Second, the commands in plain or encrypted form are regarded as abnormal contents by OSNs, which would raise anomalies and trigger restrictions on the attacker. The defender can limit the attacker once it is exposed. In this work, we propose DeepC2, an AI-powered C&C on OSNs, to solve these problems. For the reversible hard-coding, the malware finds the attacker using a neural network model. The attacker’s avatars are converted into a batch of feature vectors, and the defender cannot recover the avatars in advance using the model and the feature vectors. To solve the abnormal contents on OSNs, hash collision and text data augmentation are used to embed commands into normal contents. The experiment on Twitter shows that command-embedded tweets can be generated efficiently. The malware can find the attacker covertly on OSNs. Security analysis shows it is hard to recover the attacker’s identifiers in advance.

__Keywords__ Online social networks, Command and control, Covert communication, Neural networks

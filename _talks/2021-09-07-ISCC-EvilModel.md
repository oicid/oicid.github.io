---
title: "EvilModel: Hiding Malware Inside of Neural Network Models"
collection: talks
type: "Conference proceedings talk"
permalink: /talks/2021-09-07-ISCC-EvilModel
venue: "26th IEEE Symposium on Computers and Communications (ISCC 2021)"
date: 2021-09-07
location: "Athens, Greece (Virtual)"
---

This is the presentation about the [EvilModel paper](https://doi.org/10.1109/iscc53001.2021.9631425) on [ISCC 2021](https://iscc2021.unipi.gr/). ([Slides](/files/EvilModel_presentation.pdf))

Delivering malware covertly is critical to advanced malware campaigns. In this paper, we present a new method to covertly and evasively deliver malware through a neural network model. Neural network models are poorly explainable and have a good generalization ability. By embedding malware in neurons, the malware can be delivered covertly, with minor or no impact on the performance of neural network. Meanwhile, because the structure of the neural network model remains unchanged, it can pass the security scan of anti-virus engines. Experiments show that 36.9MB of malware can be embedded in a 178MB-AlexNet model within 1% accuracy loss, and no suspicion is raised by anti-virus engines in VirusTotal, which verifies the feasibility of this method. With the widespread application of artificial intelligence, utilizing neural networks for attacks becomes a forwarding trend. We hope this work can provide a reference scenario for the defense on neural network-assisted attacks.

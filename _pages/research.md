---
permalink: /research/
title: "Researchs"
author_profile: true
redirect_from: 
  - /md/
  - /research.html
---


## Click Fraud Analysis Based on Mobile Sensor Data
* Duration: Jan – May 2020
* Institution: Jiangsu Provincial Key Laboratory of Network and Information Security
* Advisor: A.P. [Yubo Song](https://cyber.seu.edu.cn/_s303/syb1/list.psp)
* Main Tasks:
  * Developed a mobile terminal sensor data collecting system based on Vue and Node.js. Adopted Mel-Frequency Cepstrum Coefficient (MFCC) to extract frequency-domain features of the data.
  * Used feature correlation and importance selection to reduce the dimensionality of the feature set to 22% of its original size. Trained and fused several supervised learning algorithms to get the final classifier.
  * Generally, the final classifier had a 90% prediction accuracy. As to the fraudulent data stream with forging time-domain features, the final classifier also had an 89% accuracy, which was increased by 15% compared with traditional models.

## Distributed Cloud Storage System Development
* Duration: Jul – Sep 2019
* Institution: University of California, Irvine
* Advisor: Prof. [Fadi Kurdahi](https://engineering.uci.edu/users/fadi-kurdahi)
* Main Tasks:
  * Designed and developed a distributed storage system in Gin framework of Golang which supported basic file uploading and downloading, uploading in seconds, uploading in chunks, and resumable uploading.
  * Used the consistent hashing algorithm to implement the load balancing. Adopted scale-out by separating the request-transferring middle layer and data-processing bottom layers. The latter reported the heartbeat periodically to the former through RabbitMQ.
  * Adopted MySQL as the storage and Redis as the cache in data-processing bottom layers. Employed a dual-end storage method of Token based on cookie and Redis, and guaranteed the security of Token through AES symmetric-key encryption technology.

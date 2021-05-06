---
title: Cybersecurity is Everybody’s Business
subtitle: Detecting and Identifying Cyberattacks through Network Traffic Data
image: https://cdn.pixabay.com/photo/2020/02/21/17/06/security-4868165_1280.jpg
alt: Cybersecurity BDCC

caption:
  title: Cybersecurity is Everybody’s Business
  subtitle: Detecting and Identifying Cyberattacks through Network Traffic Data
  thumbnail: https://cdn.pixabay.com/photo/2020/02/21/17/06/security-4868165_1280.jpg
---
In this age of the so-called digital transformation, the need to protect the digital becomes as relevant as the need to protect the physical. We lock on our new-found skills in cloud computing and big data to solve the compelling problem of cybersecurity.

Our pursuit made use of the CSE-CIC-IDS2018 dataset which contains 79 features pertaining to network traffic information. The raw data of about 446 gigabytes of network logs were extracted, transformed, and loaded (ETL) into .csv format for easier handling. Each entry in this dataset corresponds to a traffic flow which is tagged as either benign or malicious. More specifically, malicious entries are labelled acccording to the attack type which falls under any of these six scenarios: Botnet, DDoS, DoS, Bruteforce, Infiltration, and Web Attacks.

Using a Random Forest Classifier, we had three experiments: threat detection, network traffic type classifcation, and the 2-step detection and type classification approach. We found that a direct implementation of the multiclass classification (Approach B) to be the most efficient. Additionally, precision, recall, and f1-scores were highest using this approach.

{:.list-inline}
**Co-creators:**
Ronald Dela Cruz
[Michael Dorosan](https://www.linkedin.com/in/michaeldorosan)
[Alfonso Limpo](https://www.linkedin.com/in/alfonsolimpo)

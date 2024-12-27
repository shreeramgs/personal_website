---
title: "Gesture Based Spatio-Temporal Representation Learning for Robust Fingerprint Presentation Attack Detection"
collection: publications
category: manuscripts
permalink: /publication/gestspoof
excerpt: >
  - Fingerprint spoof attacks are highly common and pose a significant threat to biometric security systems.
  <br/>
  - Existing methods primarily focus on image classification, ignoring the potential benefits of temporal learning.
  <br/>
  - The differences in the elastic properties of real versus fake fingerprints can be better detected through motion-induced gestures.
  <br/>
  - Widely used datasets lack temporal information, prompting the creation of a new dataset to explore distortion-based spoof detection.
  <br/>
  <img src='/images/gestspoof.jpg' alt='Fingerprint Spoof Illustration' href='https://ieeexplore.ieee.org/xpl/conhome/10581880/proceeding'>
date: "2024-07-01"
venue: >
  2024 IEEE 18th International Conference on Automatic Face and Gesture Recognition (FG)
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: "https://brosdocs.net/fg2024/027.pdf"
citation: >
  @inproceedings{sankaran2019representation,
    title={GestSpoof: Gesture Based Spatio-Temporal Representation Learning For Robust Fingerprint Presentation Attack Detection},
    author={Bhavin Jawade, Shreeram Subramanya, Atharv Dabhade, Srirangaraj Setlur, Venu Govindaraju},
    booktitle={2024, 18th IEEE International Conference on Automatic Face & Gesture Recognition (FG 2024)},
    year={2024},
    organization={IEEE}
  }
---
<img src='/images/gestspoof_image2.png'><br/>
Fingerprint spoof attacks represent one of the most prevalent forms of biometric presentation attacks. While significant progress has been made in framing fingerprint spoof detection as a general image classification problem, limited attention has been given to treating it as a temporal learning problem. The distinctions in the elastic properties between authentic and synthetically created counterfeit fingerprints can be more accurately captured under motion-induced gestures during acquisition. In this study, we introduce a novel method for detecting fake fingerprints by deliberately introducing distortions through sliding and twisting motions during acquisition. As widely used spoof datasets such as those from LivDet 2009 to 2021 or MSU FPAD lack the temporal information essential for this investigation, we assembled a new dataset focused on distortion-based fake and real fingerprints, encompassing various types of spoof materials and diverse distortions. This gesture-equipped dataset comprises more than 3680 videos gathered from 184 unique fingers. Additionally, we present a novel spatial-temporal multi-modal network for detecting fingerprint spoofs using intentional-distortion.

<br/>
<img src='/images/spoof_fingerprints.png'><br/>
Our proposed approach yields significantly improved results compared to traditional static classification-based methods for spoof detection, across various metrics and for both known and unknown (generalization) scenarios, thereby highlighting the substantial impact that introducing gestures can have on enhancing fingerprint spoof detection. The dataset can be downloaded from here: https://www.buffalo.edu/cubs/research/datasets/gestspoof-dataset.html
## Sickle Cell Retinopathy (SCR) Detection
![img](https://user-images.githubusercontent.com/16880159/153737914-73c3d782-09f8-41b7-8636-c0708fdebfb0.png)
:--:
*Fig: B-scans with SCR enclosed using bounding-box*
#### SCR is a condition of inner retinal thinning observed in patients with Sickle Cell Disease. Opthalmologists diagnose SCR by studying retinal images obtained 
from Optical Coherence Tomography (OCT) exam. The need for manual diagnosis and the lack of a large scale SCR dataset has been a topic of concern to anyone 
interested in studing the disease. In this research we aim to develop an effective deep learning-based system that detects and tracks the changes in retinal 
thickness due to SCR. We are collaborating with Nemours Children Hospital and renowned opthalmologist, Dr. Jing Jin, to collect and annotate high quality OCT 
scans of children with SCD. We approach the problem as an object detection task and therefore annotate the images showing SCR-related retinal thinning with a 
bounding box. For evaluation, we calculate Mean Average Precision (mAP) based on Intersection over Union (IoU) between the annotated and predicted instances. 
We prepared a dataset containing 3906 B-scans from 33 SCD patients (14 male, 21 female, mean age 12.99&pm;4.56 years) to train and evaluate a YOLOv5 model as a 
prelimenary study. The trained model could correctly identify 85% of the total SCR instances. Using this result as a baseline, we aim to develop a more 
sophisticated system capable of tracking the progression of SCR related retinal thinning over time. 
<!-- https://commons.wikimedia.org/w/index.php?curid=18776091#/media/File:Fundus_photograph_of_normal_left_eye.jpg -->

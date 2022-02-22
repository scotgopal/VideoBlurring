# BlurMe Beta v1.0
This programme takes an .mp4 video as an input. The user then selects the faces that they want to keep, then the rest of the faces in the video will be blurred. The video that is blurred will then be saved in the local directory with output.mp4.

<img width="200" src=https://github.com/scotgopal/VideoBlurring/blob/c3b317c122d90020cc57e70d9b2d7df146715e17/LanBlurred.jpg>
---
- Understand the motivation and some use-cases of this project in our presentation. I've posted a recording [here](https://www.linkedin.com/posts/scotgopal_privacy-protectyourdata-deeplearning-activity-6716183278447140864-te6K) on LinkedIn.
- Checkout the demo [here](https://www.linkedin.com/posts/scotgopal_deeplearning-machinelearning-artificialintelligenceai-activity-6724350202674868225-0H38). It's on LinkedIn as well.


---
## Steps
1. Download the whole folder.   
2. Import pom.xml as project in IntelliJ.
3. It will take some time for the dependencies to be resolved (-_- stay patient..)
4. Once the dependencies are resolved, open the Test.java file and run.
5. File chooser will pop out and choose the mp4 video you would like to edit.
6. After processing, user selection window will pop out, choose the face you would not like to blue out.(one face might appear multiple times, please pick all...)
7. Video with the title "output.mp4" will be generated in the root directory.
---

## Deep Learning Applications
1. Face Detection - Uses a pretrained model (VGG16) to obtain face embeddings.
2. VGG16, ResNet10, Clustering (DBScanner), 
3. 

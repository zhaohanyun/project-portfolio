#### Glister – A Highlight Capturer (Language: Kotlin)

*My work is on frontend (Android)

​	Mobile phones have become our daily necessities, and taking photos and videos is more than habitual to many people. But on many occasions, operating mobile camera occupies too much attention and deprives people of their chances to enjoy themselves. Moreover, the huge number of photos and videos causes heavy burden on mobile storage. Aiming on these problems, we developed an application that can automatically capture highlighted moments, while taking little operation and storage.
​	On backend side, we use python frameworks and Sqlite3 database system. Nginx was used to listen on the port and redirect the http requests, and the requests are handled mainly by Django. On algorithm side, machine learning-based object detection and image aesthetic assessment system. On frontend side, we adopt MVC as the application architecture and Kotlin as main programming language. All development and test are done on Android Studio, with a virtual Google Pixel 4 device. The final product achieves all design objectives.

UIUX design：

![image-20221105224850292](https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105224850292.png)

UIUX design interactive demo：https://www.figma.com/proto/DFv4uH82zFkSBEfEtT4ybn/Glister--UI%2FUX-DEMO?node-id=21%3A1313&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=21%3A1313&show-proto-sidebar=1

Engine design：

![image-20221105225313122](https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105225313122.png)



Final product：

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105225436540.png" alt="image-20221105225436540" style="zoom:46%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105225448201.png" alt="image-20221105225448201" style="zoom:46%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105225531931.png" alt="image-20221105225531931" style="zoom: 40%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105225543609.png" alt="image-20221105225543609" style="zoom: 40%;" />



More information including detailed design, usability test, API design and codebase at: https://github.com/zhaohanyun/Glister

Product demo video at: https://www.bilibili.com/video/BV1MB4y1k7wE/?vd_source=022c994e29b59e2222dc4483b4fbd068



#### Chord Master (Language: Python)

​	This project solves a classification for major and minor chord based on a audio data set which contains chords from two instruments, guitar and piano. Two primary tasks in this project is model selection and feature extraction. We’ve tried multiple machine learning models, including **MLP, SVM, and RF**, and two deep learning models, **AlexNet** and **ResNet18**. On each model, we spent effort tuning its hyperparameter, and obtained their best configurations. We’ve also tried multiple feature extraction methods, frequency spectrum peaks and MFCC for ML models, and frequency spectrum image for DL models. Among all models, ResNet18 achieve the highest accuracy 86.3%, while most other models are just slightly lower, namely around 80%. In terms of feature extraction, we did not find any advantage of MFCC over normal frequency spectrum peak method.

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105230649184.png" alt="image-20221105230649184" style="zoom: 80%;" />

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105230715360.png" alt="image-20221105230715360" style="zoom: 80%;" />

Final result comparing among all models:

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105230806599.png" alt="image-20221105230806599" style="zoom:67%;" />



#### Twitter Crawler Application (Language: Javascript)

An Javascript application that can perform Twitter API REST requests using the Axios library. It can perform action like find user, find id, find timeline, get tweets and so on.

Run example (get timeline by userid): 

The right half screen is testing program, left half is the result from crawler.

![20221105_233916](C:\Users\Administrator\Documents\Tencent Files\2049964601\FileRecv\MobileFile\20221105_233916.png)



#### Digital Image Processing (Language: C++)

Lots of algorithms. Some examples:

Defog by CLAHE algorithm

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105234636467.png" alt="image-20221105234636467" style="zoom:45%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105234711861.png" alt="image-20221105234711861" style="zoom: 45%;" />



Edge detection by Canny Edge detector

<img src="C:\Users\Administrator\Desktop\EE569\assignments\HW2\HW2_images\Tiger.jpg" alt="Tiger" style="zoom: 58%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105235040381.png" alt="image-20221105235040381" style="zoom:50%;" />



Color Half-toning with MVBQ-based Error Diffusion

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image--20221105235454798.png" alt="image-20221105235454798" style="zoom:55%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105235522031.png" alt="image-20221105235522031" style="zoom:48%;" />

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221105235602159.png" alt="image-20221105235602159" style="zoom: 80%;" />



Texture segmentation

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106000316947.png" alt="image-20221106000316947" style="zoom:120%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106000305367.png" alt="image-20221106000305367" style="zoom:150%;" />



Image Stitching (merge 3 pictures taken in different perspectives)

​	left&middle<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106000546074.png" alt="image-20221106000546074" style="zoom:80%;" />

​	right&middle<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106000556879.png" alt="image-20221106000556879" style="zoom:80%;" />

​	merge

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106000608249.png" alt="image-20221106000608249" style="zoom:80%;" />



#### Face recognition on edge devices (Language: C, C++ and Python)

In this project, we use facial recognition, serial communication, ultrasonic
ranging, automatic obstacle evasion, so that the vehicle can sense the real-time
external environment and user dynamics, and perform action in real time. The
functions of the vehicle include:
• Recognize human faces and move towards or backward to the recognized
person
• Detect and evade obstacle
• Move in all directions

top-level block diagram

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106001329094.png" alt="image-20221106001329094" style="zoom: 50%;" />

robot prototype![image-20221106001310237](https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106001310237.png)

Face recognition with Opencv and one-shot learning

<img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106002235602.png" alt="image-20221106002235602" style="zoom:50%;" /><img src="https://github.com/zhaohanyun/project-portfolio/blob/main/images/image--20221106002250651.png" alt="image-20221106002250651" style="zoom:50%;" />

Demo video at: https://youtu.be/e6cj6U3KOOU

Code base at: https://github.com/zhaohanyun/VE373-Embedded-System



#### Doctor HealthX Intern (Language: Python)

My main role is to process medical images (any organ potentially) and make intelligent diagnosis using deep learning. Additionally, I also take other roles based on customers' need, like integrating the deep learning model, front end, backend into a system and deploying on certain platform.

This is the recent work on gallbladder carcinoma. It's a segmentation task, solved by Unet.  First row random slices of CT images on gall bladder with tumor. Second row is mask(target) provided by doctors. Third row is our model's prediction.

![image-20221106002954511](https://github.com/zhaohanyun/project-portfolio/blob/main/images/image-20221106002954511.png)

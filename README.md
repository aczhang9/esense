# eSense exploration

## Existing works
1. [Detecting Verbal and Non-Verbal Gestures Using Earables, 2021](https://www.esense.io/earcomp2021/EarComp-PreACM.pdf)  
- Classification of scripted nodding, speaking, eating, standing still, and head shaking from 10 participants using accelerometer and gyroscope data from IMU sensors with 0.82 F1 score

2. [Towards a Characterisation of Emotional Intent During Scripted Scenes Using In-ear Movement Sensors, 2020](https://dl.acm.org/doi/10.1145/3410531.3414292)  
- Found that people are more energetic and more in-sync when using positive versus negative intentions over a three participant study using scripted scenes from a play

3. [Head Motion Tracking Through in-Ear Wearables, 2019](https://dl.acm.org/doi/abs/10.1145/3345615.3361131)
- Primary goal was to understand the accuracy achievable by eSense, which solely relies on accelerometer and gyroscope to track user’s head movements
- Achieved estimations with an average error that ranges from 5.4 degrees for short movements in the least challenging situation, to 18.7 degrees for longer movements, in noisier circumstances. 

4. [KAIROS: Talking Heads and Moving Bodies for Successful Meetings, 2021](https://dl.acm.org/doi/pdf/10.1145/3446382.3448361)
- Developed “Kairos," a system for multi-modal monitoring of virtual meetings that captures subtle body cues and built a model to predict a meeting’s self-reported success, achieving an AUC as high as 79%
- System consists of a mobile application to collect accelerometer and gyroscope data, a smart watch to collect accelerometer, gyroscope, and heart rate data, and eSense to collect accelerometer and gyroscope data, and web server which collects audio recording of meeting
- Designed six metrics to capture body language cues - vibrancy, multi-tasking, heart rate, head movement, postures, and hand movement 
- Built a random forest model that achieved an area under curve metric as high as 79%. Head and hand movements were identified as most predictive features for meeting success.  

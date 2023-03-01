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

5. [Cross-Modal Approach for Conversational Well-being Monitoring with Multi-Sensory Earables, 2018](https://akhilmathurs.github.io/papers/min_wellcomp18.pdf)
- BLE model that scans for nearby devices to discover a potential conversation group and participation
- Motion model using eSense IMU's to determine if user is peaking or not
- Stress (binary class) and emotion (anger, fear, neural, sadness, happiness classes) detection model using eSense's microphone to record and label conversational speech
- Evaluated across 5 participants in 4 scenarios (speaking, sitting, watching TV, person speaking nearby) with 88% accuracy

6. [Deep sensing of breathing signal during conversational speech, 2019](https://repository.ubn.ru.nl/bitstream/handle/2066/214126/1/214126.pdf)
- Developed CNNs and RNNs to predict the breathing activity of a speaker from their speech signals
- Collected data with microhpone and two respiratory elastic transducer belts over the ribcage and abdomen to measure changes in cross-sectional area of ribcage and abdomen
- Data collected from health subjects conducting the following activities: general conversation, reading a script, normal breathing, prolonged vowel sound, reading a script after exercise
- Obtained sensitivity of 91.2% for breath event detection and a mean absolute error of 1.018 breaths per minute ofr breathing rate estimation

General notes:
Non-verbal communication sensing for social skills training (job interview, public speaking, language learning, clinical settings)
Input data is mainly video (tracking eye movements, facial expressions) and audio but can also be physiological signals and other sensors [1](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6798633), [2](https://dl.acm.org/doi/pdf/10.1145/3134679)

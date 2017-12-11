# Dance for Parkinson's

## Summary

Directed by Matthew Woolhouse, this interdiscplinary project has three main goals:

- Create technology-based dance systems for people with Parkinson's Disease (PD) in collaboration with [Hamilton City Bellet's](http://www.hamiltoncityballet.com/) (HCB) [Dance for Parkinson's Program](http://hcbdanceforparkinsons.com/) (D4P)
- Assess how multimedia systems mediate the experience of people with PD, and investigate the benefits of arts-based activities and digital technologies for aging or health-impaired populations
- Use our technology-based dance systems as tools with which to carry out longitudinal studies examining the effects of music and dance on people with PD

Music and dance have positive therapeutic effects for people with PD - the use of music with a clear rhythm has been shown to improve gait and timed actions, allowing complex movements to be completed more easily. For example, a [recent study](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0032600) in which people walked for short durations listening only to a rhythmical pulse demonstrated improvements to both gait speed and stride length. The benefits of music and dance extend beyond movement - non-motor symptoms of Parkinson’s such as anxiety, depression, and negative moods, [can also be improved](https://www.researchgate.net/publication/12473726_Active_Music_Therapy_in_Parkinson%27s_Disease_An_Integrative_Method_for_Motor_and_Emotional_Rehabilitation). As a therapy, dance incorporates the benefits of music while also introducing specific movement-coordination tasks. Dancing with others is (usually) enjoyable, and fosters a sense of community. It is hoped that the introduction of technology-based activities closely linked to the Dance for Parkinson’s program will enhance the benefits seen in similar programs.



## Demonstration Video

[Dance for Parkinson's Demonstration](https://youtu.be/7UYGoMrvozQ)



## Collaboration

![alt text](http://digitalmusiclab.org/wp-content/uploads/2015/07/Hamilton-City-Ballet-Logo.png) Coordinated by program manager Jody Van De Klippe `[B.A.Sc. (Hon.), CLSt. (Dip)]`, HCB’s D4P classes are among a growing number of therapeutic dance-intervention programs within Canada. The founders and Artistic Directors of HCB, Melania Pawliw and Max Ratevosian, provide expert choreography and instruction for the classes; both are classically trained, and have enjoyed international ballet careers. In addition, an accredited music therapist, [Rachael Finnerty (MTA MMT MA)](https://www.linkedin.com/pub/rachael-finnerty-accredited-music-therapist/21/875/173), is advising the McMaster team on the use of music with respect to patient psychology, motivation, emotion and wellbeing.
Typically, fall, spring, and summer semesters consist of six classes, occurring every other week. Classes take place in a spacious community hall, and demand for the program is growing. Biweekly classes create two problems. Firstly, the classes’ 14-day separation affects the social benefits of the program. The ability of people to build supportive communities depends critically on the time interval between their social interactions—too long and the formation of empathetic relationships is reduced. Second, the program’s biweekly structure disrupts the positive feedback created through regular dance practice. Both of these issues can be aided with the dance technology we are developing, thereby supporting the PD community and the broader aims of the program.
In fall 2016, a pilot study will be undertaken investigating clinical and neurophysiological effects of music and dance on Parkinson's. To assist with this study, we are pleased to be partnering with Dr. Rick Paulseth, Director of the Movement Disorders Clinic at St. Peter’s Hospital, and Dr. Mike Noseworthy, Director of Imaging Physics and Engineering, Imaging Research Centre, St. Joseph’s Healthcare. Six PD patients will undergo magnetic resonance imaging (MRI) and clinical assessments prior to and following six weeks of music and dance intervention using our technology. MRI will investigate neurological attributes associated with PD such as brain-iron content, microvascular perfusion, and cortical thinning. Using the Unified Parkinson’s Disease Rating Scale, clinical assessments will investigate the effects of the intervention on mentation, daily living, and motor abilities.



## Technology

Our technology-based activities are designed for everyday home use, thereby bridging the gap between HCB’s D4P classes. The system uses a low-cost motion-sensing camera, [Microsoft’s Kinect<sup>TM</sup>](https://en.wikipedia.org/wiki/Kinect), which is linked to a computer and monitor, displaying a dance avatar. Users’ movements are input into the computer via the camera. Each activity is based on a dance from the main D4P program; the aim is to complement the instruction participants receive in class. Choreography is designed to provide a wide variety of movements, such as joint rotation, quick and smooth movements, and rhythmic clapping.
Version #1 of the system (developed summer 2014) superimposed user-movement data onto videos of the dancer; the aim was for a user to match their hand movements to those of the dancer. The system was field tested in the homes of people with PD in late summer 2014. Potential issues were identified, including lack of interactivity; user feedback was used to guide subsequent development. 
![alt text](http://digitalmusiclab.org/wp-content/uploads/2015/07/D4P-logo-screenshot-1024x576.jpg) Version #2 (September 2014 to present) uses high-quality motion-capture data, recorded in the [LIVELab](http://livelab.mcmaster.ca/) of the [McMaster Institute for Music and the Mind](https://mimm.mcmaster.ca/), to create an interactive avatar-based system. Currently, we are using the Unity game engine to develop a professional-quality application, in which a dance avatar responds to the user’s mobility—the avatars make real-time movement modifications in reaction to the user’s abilities. This application is being field-tested in the homes of people with PD, and feedback used to guide further development.

The project’s technical methodologies include:
- Realistic Avatars: Scanning of the dancer using a Microsoft Kinect<sup>TM</sup> camera to create a realistic game model (Body Snap and Mixamo)
- Motion-Capture Animation: Infrared cameras generate a 3D representation of a marked dancer using Qualysis Track Manager. The 3D biological-movement data is linked to the avatar using MotionBuilder
- Real-time Body Tracking: Microsoft Kinect<sup>TM</sup> v2 camera will be used to track users’ body positions in real-time. This allows for gesture-controlled interactivity within the system
- Gesture Recognition: Machine-learning software (Visual Gesture Builder) used to generate a body-gesture database, which, in turn, will determine users’ performance
- Dynamic Game Engine: Unity game engine will create a dynamic system capable of adapting to a user. The game engine will support multiple platform release to Windows and the Xbox One console
![alt text](http://digitalmusiclab.org/wp-content/uploads/2015/07/Image7.jpg) 


## Ethics

Ethics approval has been granted for the project (HiREB Project #: 14-419-S), which enables us to work with people with PD, enrolled HCB’s D4P program. In line with this protocol, we use online surveys, face-to-face interviews and focus groups to examine how multimedia systems influence PD sufferers’ experiences, and assess the difficulties of introducing technological-cultural activities—such as our avatar-based dance system—to aging and health-impaired people. Safety features, such as emergency caregiver text-messaging, are being tested and assessed using online diaries in which users and caregivers can provide daily feedback.
![alt text](http://digitalmusiclab.org/wp-content/uploads/2015/07/Image8.jpg)

A long-term project goal is to undertake longitudinal studies into the effects of dance on PD through kinematic analysis of users’ movement data. In this rapidly expanding area of research, statistical tools aimed at assessing people with PD include Gait Profile Scores, Movement Analysis Profiles, Fullerton Advanced Balance Scale, the Unified Parkinson Disease Rating Scale, and the Six Minute Walk Test. We aim also to undertake psychological testing to assess cognitive functioning and mood, often negatively impacted in PD.


## Impact

According to the Government of Canada's 2014 report ["Action for Seniors"](https://www.canada.ca/en/employment-social-development/corporate/seniors/forum.html), key government policy objectives include action to help seniors:
- Remain active through paid or volunteer work
- Stay in their homes for as long as possible
- Experience wellbeing and good health

This project fits strongly with these objectives. Firstly, our dance technology will help PD sufferers to remain physically active and mobile. Secondly, our system is designed for domestic use, in keeping with the drive to help seniors remain self-sufficient within the home. Thirdly, active engagement in dance—a key feature of the project—is known to improve wellbeing, mood and motivation. Furthermore, by developing an advanced health-based system using digital media, the project closely aligns with the focus areas of [Ontario Innovation Agenda](http://docs.files.ontario.ca/documents/334/ontario-innovation-agenda.pdf). Skills gained during the project in computer programming, community engagement and PD will enable students to contribute significantly to a range of strategically important industries, including IT and Health.

Two articles relating to the project have recently been published in the International Journal of Health, Wellness & Society and the Journal of Biomusical Engineering:

[Woolhouse, M. H., Zaranek, A. (2016). Intuitive Navigation in Computer Applications for People with Parkinson’s. Journal of Biomusical Engineering. 4/1: 115-123.](http://www.omicsonline.com/open-access/intuitive-navigation-in-computer-applications-for-people-with-parkinsons-2090-2719-1000115.php?aid=72474)
[Woolhouse, M. H., Williams, S., Zheng, S. & General, A. (2015). Creating technology-based dance activities for people with Parkinson’s. International Journal of Health, Wellness and Society. 5/4: 107-121.](http://ijw.cgpublisher.com/product/pub.198/prod.216)


## Support


To support the project, two competitive internal grants have been secured (Arts Research Board and Forward with Integrity), and a grant from the Office of VP Research ($40,000 over 3 years). This funding has enabled students to be trained, and to develop the system to the point where we are undertaking field trials. Further funding opportunities are being sought. Anyone wishing to enquire about how they can support our research are kindly requested to [contact the lab's director](http://digitalmusiclab.org/?page_id=498), Dr. Matthew Woolhouse.


# Proposal

## Project Objective 

The aim of this project is to create a cross-platform opensource application for panic mitigation with cognitive behavioural tasks (CBT) that are clinically effective. Due to recent circumstances, the target audience for this application are those living in isolation and do not have access to proper psychological help. 

## Introduction 

Panic treatment online has a shockingly low presence despite being shown as an effective treatment measure. The few applications that do exist all have low ratings yet still manage to be government recommended. Mental health applications that are successful primarily focus on anxiety and depression, but not on Panic. Additionally, some of these applications are expensive and some are not cross-platform. 

My goal is to develop an opensource cross-platform application for panic mitigation. 

The issue with treating panic is that most patients relapse just after 3 months post initial treatment. Some studies have shown that cognitive behavioural tasks (CBT) can be effective in the short term when dealing with acute panic, but never in long run. There is only a limited selection of activities that have an impact 6-month post treatment. Consequently, my application will be split into 2 parts where panic is targeted in the short-term, but the comorbid behaviours are focused in the long-term. 

The main question my application will be trying to answer is that when it comes to treating a panic disorder, how should comorbid conditions be treated and how can this can affect the patient’s overall success in the long run. Comorbid behaviours strongly linked to panic are anxiety and depression. Some studies have even gone as far to show that there are higher rates of suicide attempts among those that struggle with a panic disorder.  


## For Part 1: 

I would take inspiration from The National Institute for Health and Clinical Excellence’s recommended panic and phobia application “FearFighter”. Even though this application costs between 200 – 400 CAD, it has 1.5 stars on the App store and no ratings on the play store. FearFighter has been proven clinically to reduce symptoms of anxiety, depression, and panic [9] but outside the clinical setting the app is broken and non-functional. I can try to understand what the application is doing right to generate these positive results and by focusing on user experience, I can mitigate the downsides associated with this very low rating. 

I will also take inspiration on the recommended applications by the Anxiety and Depression Society of America. They recommend Mindshift and Panic Relief which generally target anxiety but also panic by using journaling functions and breathing exercises. Although, these applications have not been shown clinically to have an impact on overall patient success in panic mitigation, have been criticized by psychologists for not being useful in dealing with acute attacks, and have a lot of issues associated with them. For example, Panic Relief requires the user to input a pin before they can access the breathing exercises which is near impossible when you are undergoing an attack. Moodshift’s journaling options limit the user to fully express how they are feeling. 

Finally, I can incorporate CBT activities with associated long-term improvement for panic treatment (such as interoceptive exposure).

## For Part 2: 

Cambridge found some examples of computerized therapy for depression and anxiety in 2018 that led to greater satisfaction with treatment long afterwards. They ran their study on the efficacy with the web application “Beating the Blues” which is an interactive CBT package. The general way for how the program works can be found on their website as well as many papers published showing the efficacy of this online treatment. Additionally, McGill recommends a selection of IOS and Android applications for targeting depression or anxiety. Although, it must be noted that McGill’s recommended applications all have in app purchases starting at 40 CAD up to 90 CAD annually and Beating the Blues is 100 euros (153 CAD). They have recently discounted the application since Covid-19 to be 20 euros (31 CAD). 

I can investigate the overlap that “Beating the Blues” has with the McGill recommended applications in order to create something with the best possible user experience while also ensuring that the choices of tasks for the application have been proven to be clinically effective. 

## Tasks

1. Build a frame of the project. What are the main screens? What is the focus? How will this be different from other existing applications?
2. Develop a Database design for the project.
3. Develop the frontend skeleton for the project.
4. Add necessary modules / exercises for the user to run through. 

## Schedule 

*Week 1: May 11 – May 15:* 
Preliminary research and emailing another expert in the field about this idea. 

*Week 2: May 18 – May 22:* 
Downloading every recommended application for panic, depression, and anxiety and comparing their similarities, strengths, and downsides while ensuring all the tasks that are being used are clinically significant. As well, I need to investigate other tasks that are proven successful which are not apparent in any of these applications. 

*Week 3: May 25 – May 29:*
Coding can start. Make a skeleton for the application in react native by initializing the home screen and navigation. Generally, format the different views such that they can be easily extended in the future.

*Week 4: June 1 – June 5:* 
Initialize the backend. For this I will be using React Native Firebase. Template what the CBT modules will be for the database schema as well as in the frontend. 

*Week 6: June 8 – June 12:*
Add some CBT Module examples. 2-3 in total. 

*Week 7: June 15 – June 19:*
Template what the Journal will be for the database schema as well as in the frontend. 

*Week 8: June 22 – June 26:*
Test Journal functionality and continue developing it.  

*Week 9: June 29 – July 3:* 
I move out this week to some unknown location. I will be delayed this week with the schedule. 

*Week 10: July 6 – July 10:*
Research more CBT options and make modules for them. 

*Week 13: July 13 – July 17:*
Start final report. 

*Week 14: July 20 – July 24:* 
Develop motivating screen if time. 

*Week 15: July 27 – August 1:*
Develop motivating screen if time and final report. 

*Week 16: August 3 – August 7:*
Motivating screen additions and final report.  

*Week 17: August 10 – August 14:*
The summer semester examination period is this week. Submit code and final report?  


## Research tools 

JSTOR and Google Scholar are my best friends right now. As well as all the reviews on the App and Play store. I am in the process of trying to find someone who is knowledgeable in this area of research. 


## Future Work

Just because the tasks I am using are clinically significant does not mean it makes a difference. I would need to test this with many users to see where the application is lacking in a standardized way. 





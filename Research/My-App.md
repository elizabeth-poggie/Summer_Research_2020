# App Skeleton

## Account? 

There will be no account associated with the user. One reason is that having to log in account information during a panic attack is impossible. During an attack, users struggle to even do basic movements and so having to enter a pin / username is too much. Another reason is that users want to feel their data is anonymous and would prefer to have the data stored locally on their device. Only when pairing internet CBT with psychiatric care is there any benefit to having an account associated with the user so the therapist can use this data to guide patient treatment. For the purposes of my application, I do not need to worry about this.

For this section, an account can automatically be created by tracking their device id and username (which will be automatically generated upon opening the application). This will allow the user to export their data if they need. 

## Main Screen
- Most of these panic applications require too many steps to reach an exercise meant to calm someone down during a panic attack. This is not good design users who are experiencing an attack need the minimum number of taps possible to access a breathing exercise since movement during one of these attacks is difficult. I only want 2 taps to access the sequence, one to open the app and another to start the sequence. At the top of the home screen there will be a large button that states �I am having an attack�. This will run through a simulation of breathing (with an animation, voice over, and text) with the option to pause and start the exercise at any point. At the end of the exercise there will be options to further complete a grounding exercise, body awareness exercise, focusing task, or to repeat the breathing exercise. Studies have shown that a calming voice has the best impact on the user experience, but it is also important to have text in case users want to be discrete and do not have headphones. (the specifics of how these tasks are designed require further reading, but I have a general idea of the implementation). The p5.js library will come in handy for making animations here. 
- At the bottom of the home screen there will be the option to �track your daily mood� and write an entry associated with this mood. Entry form will have a ranking of panic, anxiety, and depression the user might have endured, the scale of the impact, a section to write an entry of any length, and associated symptoms. I am tracking not just panic since anxiety and depression are comorbid to panic. For example, a user might have panic without depression and depression without panic one day even if they experience both. The entry will automatically save as a draft if the user gets distracted and the user will have the option to go back and edit journal entries if they happen to think of something else later that day. 

## Journal Screen
- Default screen will be a chart tracking the overall mood of the patient over time with the options to filter by mood or symptom specific categories associated with their journals. If you drag up on the bottom of the screen it will show you all journal entries leading up to the current date. In this case, I can use ant design�s functionality. 

- For each entry, the user will have the option to add a journal for a day (from this it will pop up a month selector to choose any day up to and including today) and a time. You can select a mood that reflects how u are feeling from a list of 5 that also allows you to edit these moods at the bottom of the screen. 
- This then opens a different screen. This screen comes in 3 parts. 1 part for symptoms that allows you to select different sections that apply to you. For example, a panic section, a depression section, an anxiety section. A �what you did today� party where there are different health and wellness sections. A final part dedicated to writing a journal entry. 

## CBT Homework Screen
- Studies have found the providing a large arsenal of CBT homework options increased patient success by the end of the trial. Options will include breathing exercises, relaxation training, focusing tasks, cognitive restructuring, mindfulness, and exposure options. 
- These should be easy to release, almost like a new Jekyll page. The template for this should be standardized so as I find more examples of good CBT homework, making a new exercise should be just as easy as injecting the data. 
- Rough template: text, animation, voice over. 

## Navigation Bar
- Options to access the home screen, journal screen, CBT homework screen, [optional] motivating screen, and an about page / contact screen for submitting feedback to the developer. 
- Navigation can occur by tapping on the icons or swiping the screen. when the user is on a page, that section of the navigation bar is highlighted. 

## Motivating Screen [optional, but worth putting more thought into]
- A study that focused on the efficacy of digital CBT found that applications required a lot of user motivation to complete the CBT tasks as �facing your fear� is difficult when you are alone doing it. Consequently, the application should have a �playability factor� but this should not obscure the goals and rules which are part of the treatment. 
- This study also warns to not use �points� as the motivating factor as this will attribute user success with how many points they have obtained. As such, my idea is to follow many routes �study applications take�. For example, you have a small creature whose crib you get to deck out as you study more. In my case, as the user takes care of themselves with CBT exercises, it is reflected here. A key thing to note here is to not make the starting screen any more fancy then a user who has done many exercises (so that success is not attributed by the state of the room), but rather to give the user more options for things to swap in and out of that room. So as the user completes more journal entries, they can choose to swap out flowers that might be in a pot. Different flowers will attract different cat visitors. If a user completes a focusing task this gives the creature in the room a cookie to crunch on or something. Users will be able to tap the visiting cats to pet them. It is a simple design that is not the focus of the application but is there to act as a playable / motivating force without any specific point measures. 
- On my end I will make a variety of simple 3 � 4 frame animations which are easy to do. (one for smelling a flower, one for eating a cookie, one for rolling in grass, one for eating a flower leaf).

## Code Aspect 
- Frontend: React Native, JS
- Backend: React Native Firebase, MySQL

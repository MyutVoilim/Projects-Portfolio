# Projects Portfolio
# Table of Contents
- [AI Digit Recognizer](#ai-digit-recognizer)
- [Maproom](#maproom-campus-navigation-app)
- [ATV Repair Shop Database](#ms-access-atv-repair-shop-database)
- [Java Dodge Game](#java-dodge-game)
- [Unity AI Survival Agent](#unity-ai-survival-agent)
# AI Digit Recognizer
<b>Overview</b>

This project is a built from scratch Feed-Forward Neural Network (FNN) that uses backpropigation to progressivly train a neural network from training data of drawn number 0 - 9. Following Object-oriented Programming (OOP) princables this project is meant to be the highlight of years of both academic and personal projects that takes a challenging concept and on goes through the software devlopment life cycle (SDLC) to plan, design, implement, test, and deploy a complex system. This application allows the user to create custome neural networks that they can train with a adjustable variables such as learning rate and epoch count. I was focused on not just creating a neural netowrk but a application that interactive, informative, and fun to use. 

<b>Technologies:</b>C# | WPF | .Net Framework | Visual Studio

<b>Features</b>
- Interactive digit recognition where the user can draw digits and see the AI's confidence values in real-time.
- Customizable neural network with the ability to create custom neural networks by defining hidden layer sizes and node counts.
- Control over training parameters such as ajusting learning rates and epoch counts to influence training route.
- User-friendly interface that includes dynamic visuals, progress bars, accuracy tracking, and confidence value displays.
- Ability to save and load models as well as change training data

<b>Challenges:</b>
Due to the complex nature of neural networks, planning out the structure of the network itself as well as how the rest to the system would interact with it prooved more difficult than any other project I've made. It was imparative that I created a robust foundation to reduce bugs and improve testability for each section to check for excepted behavior. This process included implementing single responsability principles and dependency injection to allow for Unit testing expected funtionality. 

<b>Reflection</b>
This project was important for applying my knowledge to a difficult task and learning where I can improve, nothing is learned by taking it easy. I learned a lot about what makes code robustness, testability, and maintainability.


This is one of my most complex but satisfying projects into terms of both size and complexity. I found it very difficult to properly determine what strucutre I would need since i've never made a neural network this complex. Since i've never made a neural network this compelex I found myself a little unsure how excatly I should strucutre some the internal architecture of the network. Unlike most projects i've made before, nature of how many stages must be compeleted before any tangiable results from the network can be seen gave my many unique challenges from finding bugs and determineing the structure . The journey from data from a text file to the output and training of the neural network is a long and complex journey with a million things to go wrong it goes from (Data in Text file) > (coverted into proper format for neural netowork) > (netowrk weights and baised initalized) > (data normalized using sigmoid) > (Forward pass through network) > (output of the network) > (proccessing through backpropigation) > (finally outputed to the UI). Within this whole process a million things can go wrong from the text file being read wrong to very subtle bugs the mess with the training of the AI.
  
# Maproom Campus Navigation App
Overview
This project named Maproom is a collaboration between myself and two other students to create a Campus navigation app for our CS capstone project. The main focus was to create an app that would allow for mainly Freshman students comming into campus to more easily and less nervreckingly find their classes in time in unframiliar surrounding. The app shows various important building on the campus location alond with the ability for the user to searach for the class code such as CYBR 233, and find the building it is in and highlight the room location. Their was heavy important in the SDLC in all phases from planning out our requirments from what skills we had to surveys asked of new studnets to find what was most important to them in fidning their classes. Using technologies such as Github, Discord, and tools to create Gnatt charts were all used to collbtrativly to create this project.
Technologies Used

- Javascript
- CSS
- Node.js
- MongoDB
- Visual Studio Code

  Challenges
  Because this project is a collaberation between three people it was important that we as a group determine what we wanted to create and the process we would use to achieve that. It was also important that we had a tangiable timeline the we ahchieved with a gnatt chart to assign tasks and keep us in line with are targets. using technolgoies like github to centralize and upload progress, Discord for communication when we couldn't not get together, and close collabration that utalized each of are backgrounds from busienss to computer science. Their were times when we could not get together because of scheduels but assigning ahead of time what each needed to to along with updates on where we were at allowed us to iterativly improve or application until the eventual creation. 
# MS Access ATV Repair Shop Database
Overview
This project is a highlight for the process of working closely with a client to plan, design, and create a geunially impactful database to manage record keeping for a ATV Repair shop. This relational database allows the client to log various important forms from customer information, vehicle services, Reprir costs and descriptions and many others that can be seen below. It was important that I understand what the clients needed and made sure focus was on their needs.

Technologies Used
- MS Access

Challeges
Unlike most projects i've made, this one had real impact on someones life and how they operated their business. Their is something speicial about working with real issues and devloping software to make peoples lives easier. It was paramount that focused on the clients needs rather than to just create something I thought they wanted. I needed to make sure that I properly planned for what the client needed and continuously update them and adjust as needed based on those needs. Working for the client brings special challenges but is it one of the most rewards aspects about software devlopment
# Java Dodge Game
overview
This project focuses on using Java and OOP to create a fun game where the user is meant to dodge the red balls and collect the green balls. With various modes including easy, medium, hard, and insane, This challangeing game progressivly gets harder as more green balls are collected. Each mode chages how quickly new hazard red balls are created, their speed, and their size. This application keeps track of the users current score and the highest scores they've achieved on each mode.

Technologies used
- Java
- Eclipse

Challenges
The main focus of this project was to create a properly structured application that followed OOP princables and see it to completion.

# Unity AI Survival Agent
This project uses C# and Unity to create an AI agent that generationally improves its survivability using a basic feedforward neutral network in conjunction with a genetic algorithm. Each agent has several stats the determine variables like speed, visions range, vision cone count, and stamina that all affect the agents ability to find and compete for food in it's environment. Several agents would be pitted against each other where the agent that lived the longest would have it genetics passed on to the next with varience to futher hone a competetive agent.

- C#
- Unity
- Visual Studio

Challenges
Like anything related to AI it was difficult finding how I should strucutre the AI between was elements should be relavent such as speed or vision to what rewards I should use to determine the success of a agents generation. This was also the first time I ever used Unity so their were challenges in learning the platform in order to achieve what I sought to do.


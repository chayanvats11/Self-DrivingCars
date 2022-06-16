# Self-DrivingCars
Here we have used the Deep Learning Algorithm  
To understand the workings of self-driving cars, we need to examine the four main parts:  
• Perception  
• Localization  
• Prediction  
• Decision Making  

Perception - To achieve such a high level of perception, our self-driving is using Radars  
Localization - Localization algorithms in self-driving cars calculate the position and orientation of the vehicle as it navigates  
Prediction - The sensors in self-driving cars enable them to perform tasks like image classification, object detection, segmentation, and localization. With various forms of data representation, the car canmake predictions of the object around it  
Decision Making - When it comes to making decisions, we use deep reinforcement learning (DRL). More specifically, a decision-making algorithm called the Markov decision process (MDP) lies at the heart of DRL  

In order to tackle the problem of finding the best move for itself, the deep learning model is optimized with Bayesian optimization    

The function eval_genomes will provide us a fitness score for each car which will tell us how long the car stayed alive on the track   
Eventually the Cars will improve their Fitness values that is the time duration of the Cars staying on the tracks will improve  

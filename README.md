# Data-Analysis-Project-Understanding-Humans-Motor-system

Project in cooperation with The Cognitive Development Lab at the Haifa University. 
The research investigates the impact of low specialization in sensory perception in autism spectrum disorder(ASD) on sensorimotor control.

The scope of our project was the data set collected during the experiment, which contained the experiment results, participant data, experiment surrounding 
characteristics and results and score of aq questionnaire. We processed the data and focused on main variables, removed outliers and insufficient observations. 

Our main hypothesis:
1. Action-effect improves accuracy, hence learning proccess occurs.
2. There is a relation between accuracy to the speed of movement.

The graph below shows the observation and how they are distributed:
![image](https://user-images.githubusercontent.com/84041532/157410932-b8228cb4-de30-446e-8ea1-e9bd29971d35.png)

It can be seen that participant’s accuracy mean in the long lag (W) differs from the short lag (N). 
The outliers represent some participants overscoring or underscoring during the experiment.

We performed a t-test for paired samples to test if this difference can conclude any improvement in participant’s learning process (if accuracy improves with the action-effect).
The null hypotheses suggests that no improvement is made and our Statistical significance is defined at the level of 0.05. 
The results suggested declining the H0 hypothesis, which means that there is an improvement on participant’s motor reaction in response to an immediate effect.

We then tested the if the speed of movement is related to accuracy, using linear regression model. 
According to the result of the p-value in the linear regression test there is a significant negative relation between the accuracy and the speed of movement, once participant 
improves his accuracy, his speed of movement will be reduced. The R-squared result shows that the connection is weak, and there might be other variables that might affect the trial.

This research sets a ground for further experiments and hypothesis, such as the effect on ASD population, the relation between the context of the affect and motor 
learning processes etc.

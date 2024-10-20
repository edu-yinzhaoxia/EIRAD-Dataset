The dataset EIRAD is divided into two categories: targeted attack data and untargeted attack data. Each category contains 500 pairs of image and text information. Targeted attack data simulates scenarios where the attacker has a specific goal, aiming to test the system’s defense and confrontation capabilities in such situations. On the other hand, untargeted attack data does not constrain the output to a specific target and is intended to make the system generate content that is inconsistent with expectations, or produce random or meaningless outputs.

The process of creating EIRAD is as follows:

![image](https://github.com/Dilemma111/EIRAD-Embodied-LLM/blob/master/dataset_create.png)

The figure displays the 10 most frequently occurring verbs in prompts and target instructions, along with all the noun objects associated with these verbs in the targeted attack data. This illustrates the richness and completeness of the dataset, better simulating the various behaviors and actions an attacker might attempt when the robot faces different attack scenarios.

![image](https://github.com/Dilemma111/EIRAD-Embodied-LLM/blob/master/dataset_statistic.png)


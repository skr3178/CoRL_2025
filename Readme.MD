## Notes
CoRL Day 1
Interesting talks/Food for thought. 

## Keynote speaker: Sangbae Kim

- mimicing biology is hard and bad. Should stay away.
- MIT actuator sold on Alibaba. Developed at MIT. Used in all modern robotics companies such as Unitree, etc. 
- Reference follow up was the actuator design and modeling: 
1. Proprioceptive Actuator Design in the MIT Cheetah
2. Design of a High Torque Density Modular Actuator for Dynamic Robots by Alexander Hattori
3. A Low Cost Modular Actuator for Dynamic Robots by Benjamin G. Katz


## Talk by Samsung Head of Robotics

- Flashback of early stage robotics competitions such as DARPA challenge. COntrolled using specific joint controls instead of modern day reinforcement learning. Won but a lot of the motion was teleoperated. Other sensors used were computer vision. 
-  Growing uncertainity of the future of humanoids, direction focus, application areas, Uniformity. Called for some kind of standardisation
- Noted observation, compared to past, the advent of LLM have brought about a new renewed focus on humanoids as it also learns faster and performs functions better. 
- Need some sort of generalized world models 


Reviewed Papers

- Sound of simulation: Using sound as a modality the robots are able to better learn tasks, such a pouring water in a dark room. Vision language action sound model. Used clip with spectrogram. 

Link: https://multigen-audio.github.io/  CODE available as well

-






CoRL Day 2

Presentation: ImMimic

Hand data --> Youtube videos -->skeleton or extraction of the hand pose
Retargeted to a particular hand
Motion is transferred. However, there are some limitations, the motion transfer process is not very accurate. Linear interpolation is used to retarget the data mismatch. say between 5 fingers captured to 3 fingers. 




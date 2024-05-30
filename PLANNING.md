# Soft Robotic End Effector
## Chao - Robot Arm Planning Document, Engineering 3 2023/24
### Abstract and Design Goal
The future of robotics lies in soft grippers inspired by nature. This shift to "soft robotics" allows for a more seamless integration of robots into everyday human activites. Soft robots use flexibile materials that are less dangerous in human-robot interactions compared to the "hard robotics" of the past. This design was inspired by the rise in soft robotics and several bioinspired robot grippers. 

The natural world has evolved over billons of years to create the most effective and veratile ways to grip objects. Natural grippers use three techinques in unison to seamlessly grasp a variety of objects: friction, mechanical interlocking, and adhesion. Friction is fairly intuitive; It is the resistence to motion when two surfaces are in contact. This force increases as the pressure of contact increases. For example, when a human hand grasps a pen, friction between the surface of the pen and the fingers keep the pen from slipping out of the hand. As the hand applies more pressure, the normal force between the hand and pen increases, and thus the friction increases as normal force and friction are directly proportional (F = μs × N). Friction and mechanical interlocking work in tandem. Mechanical interlocking occurs when the physical shapes and structures of appendages interlock with the irregularities of the objects' surface. Mechanical interlocking increases the friction between the two surfaces, because the surface area of contact increases as these structures interlock. Finally, adhesion is the molecular attraction between surfaces, usually by means of Van der Waals forces (temporary dipoles with slight charges between the molecules of the interacting surfaces). Animals that exhibit this gripping mechanism usually do so by an adhesive secretion. For instance, tree frogs release a muscus from their toe pads that form capillary adhesion with the surface they are grasping to. Animals with effective grasping techniques use the three gripping mechanisms (friction, mechanical interlocking, and adhesion) in coherence in order to grip effectively. However, most bioinspired robots focus on soley one gripping mechanism or fail to integrate all three effectively. The goal for this project is to use all three of the gripping mechanisms in unison to create an effective bioinspired end effector.

### Scope
After thourough research on soft robotics and natural elements that can be integrated into the design, three functions have been selected. The gripper will be able to hold, sense and adjust, and reorient objects. As this design is focused on producing an well designed end effector, the robots ability to pick and place objects is assumed and will be applied in future studies. The Sense and Adjust function is inspired by the venus flytrap. The venus flytrap has sensory hairs within its leafs that trigger the flytrap's closing motion with the slightest touch. In order to conserve energy, two of these micro-force-touch hairs must be triggered within twenty seconds in order for the closing motion to begin. This soft gripper will use a similar sensory-closing mechanism to autonomously shut while conserving power. The Reorient function will employ yaw rotation with a specific end position. It is assumed that the robot arm will provide pitch and roll. The rotation mechanism was inspired by both the Lazy Susan and Army turrets. Both use bearings or spheres between two rings, one static and one moving, in order to support a high axial load  with distributed force. The inital focus in creating this soft gripper will be the Hold function: to be able to grasp objects of any shape or material that are within 8 cubic inches. The secondary stage of complexoty for the Hold function is to be able to grasp objects that are wet using a variety of liquids with different viscosities. After the Hold function is operating effectively, the focus will shift to the Reorient function. Primarily, to simply rotate an object with consistent speed, and secondly to rotate with a purposeful end position determined by an input. The final design focus is the Sense and Adjust function. 


### Schedule
Week 1 (Febrary 26-March 1)------------: Research on alternative robort claw designs and real-world applications. 

Week 2-7 (March 4-April 15)-----------: Research soft robotics, natural grippers to implement into design, determine design functions and brainstorm several solutions, and finish planning.

Week 8 (April 22-26)----------: Adjust/finish prototype CAD design accordingly, write psuedocode.

Week 9 (April 29-May 3)----------: Block out code, begin assembly for prototype.

Week 10 (May 6-10)----------: Finish code and prototype assembly, test variety of elastics. 

Week 11 (May 13-17)----------: Troubleshoot prototype, apply solutions to V2 if necessary.

Week 12 (May 20-24)----------: Begin documentation, finish V2. 

Week 13 (May 27-31)----------: Finish documentation.

### Sketches
Initial Elastic Sketches
![IMG_3887](https://github.com/cchao2869/Rotational-Elastic-Claw/assets/91699474/5cc6f164-006c-476e-8b7a-b315c3204697)

Gear Ratio and RPM
![IMG_3889](https://github.com/cchao2869/Rotational-Elastic-Claw/assets/91699474/61344db8-e900-4f53-9e34-002c4e5a8a66)

Gear Center Distance and Section Calculations
![IMG_3888](https://github.com/cchao2869/Rotational-Elastic-Claw/assets/91699474/4f053107-9a00-4792-bd1f-df41e984cee6)

![IMG_3886](https://github.com/cchao2869/Rotational-Elastic-Claw/assets/91699474/a0cf66ff-9972-4464-9a6a-dc748dea4574)


### Previous Design Considerations
The inital inspiration for this soft gripper came from a thesis on elastic grippers used in furniture assembly by Romanishin. I was intruiged by the use of elastics, and its potential to grip delicate objects of different shapes. Further research into gripping delicate objects led me to the world of soft robotics. While I designed a gripper similar to Romanishin's in CAD, my soft robotics research opened my eyes to possibilites that would extend the application of this soft gripper beyond rotation. While this design remains focused on the reorientation of objects that is frequently disregarded and not addressed in soft robotics today, other thesises led to the addition of other functions. 


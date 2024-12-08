# IMGD5100 - Tangible And Embodied Interaction
Kaiyu Bao

Project Proposal: Integrating Mobile IOS with Unreal Engine Character Skills

A brief description of the concept
This project aims to integrate Mobile IOS with Unreal Engine to control and influence character skills in a real-time 3D game environment. By leveraging the sensors and inputs of Mobile IOS, we will create an immersive, interactive experience where real-world actions directly affect the virtual game. This project will show how IoT devices can bridge the gap between physical and virtual interactions. Goal Create a seamless connection between Mobile and Unreal Engine. Enhance the gaming experience by linking physical inputs (such as tilting, shaking, or pressing buttons) to in-game actions.


Project Documentation (Production Screenshots)
![image](https://github.com/user-attachments/assets/c057555b-6e07-49b7-a99a-9c6c4b561e41)

Practical operation video 
https://youtu.be/axfegV-wQuk

Description of the assessment and its findings
Unreal Engine's Niagara VFX system provides a sophisticated framework for creating and controlling visual effects, making it a powerful tool for enhancing character skills on iOS mobile platforms. The integration focuses on leveraging iOS-specific input methods (e.g., touch gestures, sensors) to trigger dynamic visual effects associated with character skills. This process requires optimizing visual complexity.

Evaluation Description
Visual effects (e.g., fireballs, energy explosions) were designed in Unreal Engine using the Niagara Editor. Effects were parameterized to be controlled via iOS input. VFX complexity was reduced for mobile platforms to maintain performance.
User Evaluation: A group of testers evaluated visual effects, ease of skill execution, and overall game satisfaction.

Evaluation Results: After optimization, Niagara effects maintained acceptable quality on mobile devices. Some advanced effects (e.g., dense particle systems) required significant simplification, resulting in a slight reduction in visual fidelity.
GPU utilization peaked at 70% during high-complexity effects.
90% of users found the VFX to be visually appealing and well-matched to character skills.
Memory usage for VFX is manageable, but further optimization is needed on devices with less than 4GB of RAM.
The integration works on a wide range of iOS devices, with better performance on newer models.
The Niagara system provides a dynamic and versatile framework for implementing visually compelling character skills.
Real-time response to iOS input creates a compelling gaming experience. Balancing visual fidelity and performance on mobile platforms is a key challenge, especially on older hardware.
Complex VFX designs require iterative optimization to avoid bottlenecks.
Expand the system to support multiplayer environments and larger skill sets. Explore GPU particle simulation for better performance on newer devices. Introduce a caching mechanism for commonly used effects to reduce runtime calculations.

Evaluation shows that integrating iOS input with Unreal Engine's Niagara VFX system is feasible and enhances the visual appeal of character skills. While there are challenges in optimizing performance on older devices, the approach has great potential for delivering high-quality interactive experiences on mobile platforms.

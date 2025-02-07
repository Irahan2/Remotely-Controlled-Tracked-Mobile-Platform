# Remotly Controlled Tracked Mobile Platform - Project Charter

## Project description

The proposed project focuses on developing a remotely controlled tracked mobile platform using a Python application. The platform will leverage Wi-Fi connectivity for human-robot interaction, relying on a Raspberry Pi or similar single-board computer to control the hardware. Equipped with motorized tracked wheels, sensors, and a camera (optional), the mobile platform will enable users to navigate and perform tasks in challenging environments, making it suitable for applications ranging from agriculture to warehouse automation. The project will incorporate ROS (Robot Operating System) for seamless integration of hardware components, simplifying the development of robotics software.

## Reasons for undertaking the project

1.	Rising Demand in Robotics: The demand for autonomous robotic systems in various sectors, such as logistics, surveillance, and remote inspection, is steadily increasing. By spearheading this project, we aim to contribute to this field and provide an accessible solution for various applications.

2.	Educational Value: This project presents an opportunity to apply theoretical knowledge gained from various disciplines including programming, robotics, and systems engineering in a practical context. It also serves as a suitable platform for enthusiasts and students to learn about robotics, coding, and hardware integrations.

3.	Customization and Scalability: Robotic platforms are highly customizable, allowing users to add various sensors and modules based on specific needs. This flexibility makes it an exciting project as it can be adapted for different functions and scales based on user requirements.

4.	Community Contribution: By documenting the development process and sharing insights, we aim to contribute to the open-source robotics community. This will provide valuable resources for hobbyists, learners, and professionals engaged in similar fields.

## Objectives of the project


1.	Software Development: To develop an intuitive Python application that facilitates real-time control of the mobile platform over Wi-Fi, providing a robust and responsive user interface.

2.	ROS and Zephyr Integration: To use those programms for managing hardware drivers, ensuring smooth communication between software components and the hardware.
   
3.	Testing and Optimization: To conduct rigorous testing of the platform’s physical hardware and software components and optimize performance to ensure reliability, stability, and ease of use in various environments.

## Constraints of the project


1.	Technical Complexity: The integration of different hardware components, particularly with ROS and Wi-Fi connectivity, can introduce technical challenges that may require significant debugging and iterative refinement.

2.	Time Constraints: Limited time may affect project milestones, particularly when developing the software application and conducting thorough testing before moving into production.

3.	Safety Considerations: Ensuring the safety of both users and bystanders while operating the platform will require strict adherence to safety guidelines and standards, which may constrain design flexibility or functionality.

4.	Environmental Factors: Operating the mobile platform in unstructured environments may present challenges, such as sensor inaccuracies due to lighting conditions, obstacles, or other unpredictable elements that affect navigation and performance

Through addressing these criteria, the project aspires to engineer a robust and versatile mobile platform that not only showcases technological innovation but also embodies the principles of learning, collaboration, and investment in the future of robotics.


## Directions concerning the solution

1.Requirements Analysis and Planning: Define the specific requirements of the mobile platform, including size, weight capacity, speed, and operational capabilities. Determine the hardware components (motors, sensors, battery) and software technologies (Python, ROS, Zephyr) that best match the objectives.

2.Mathematical implementation: Understanding and proper use of inverse kinematics algorithms to define movement on our mobile platform.

3.Software Development: Develop the Python application that will serve as the control interface for the mobile platform. This application will enable remote control through Wi-Fi, incorporating real-time feedback from the platform's sensors. Integrate ROS to facilitate hardware management, allowing for efficient communication between different components.

4.ROS and Zephyr Configuration and Testing: Set up ROS for handling sensor data, motor controls, and navigation algorithms. Utilize ROS nodes to implement object detection, mapping, and path planning capabilities. Conduct preliminary testing in a controlled environment to identify and address integration issues. We will incorporate Zephyr into our project to interact with other components of the robotic system. This connection is crucial for developing smaller, more efficient, and responsive robots.

5.Testing and Iteration: Perform extensive testing on the integrated system to evaluate its performance in different conditions, such as varying terrain and obstacles. Address issues related to hardware reliability, connectivity, and software robustness through iterative improvement.

6.Documentation and Community Engagement: Document the development process thoroughly, including hardware schematics, software code, and user manuals. Open-source the project to engage the robotics community, inviting contributions, feedback, and collaboration for future improvements.


## Main stakeholders and responsibilities

Batın Topbaşoğlu 276718: responsible for Assembling and Soldering 

Caner Olcay 276715: responsible for Hardware part of the project 

Piotr Kędzia 275540: responsible for Software part of the project


## Risks identified early on

Project Overview: Remotely Controlled Tracked Mobile Platform
This project involves the development of a remotely controlled tracked mobile platform utilizing a Python app, potentially engaging Wi-Fi connectivity and Robot Operating System (ROS) for hardware management. This initiative aims to create a versatile and user-friendly platform suitable for a variety of applications, from robotics education to exploration in challenging terrains. As with any innovative project, understanding risks early on and identifying the project benefits is crucial for success.

1.	Technical Risks:
•	Connectivity Issues: Wi-Fi communications may have limitations in range and may be susceptible to interference, potentially leading to disconnection during operations.
•	Software Malfunctions: Bugs or errors in the Python app could lead to unexpected behavior of the mobile platform, including critical failures.
•	Compatibility Mismatches: Different hardware components (sensors, motors) may face integration issues with ROS, resulting in delays or additional development time.

2.	Operational Risks:
•	Inexperienced Team Members: Team members may lack experience in robotic systems or Python programming, leading to slower development and potential mistakes during integration.
•	Navigation Challenges: Depending on the operational environment, obstacles may not be detected accurately, posing risks in navigation and operational safety.

3.	Regulatory Risks:
•	Compliance with Safety Regulations: Depending on the application domain, the mobile platform might need to comply with various safety and operational regulations, which could complicate development.

4.	Market Risks:
•	Changing User Needs: Shifts in market requirements could require significant changes to the initial design, delaying the launch and requiring extra resources.



## Target project benefits

1.	Enhanced Learning Tool:
•	The tracked mobile platform can be used as a practical learning tool for students and enthusiasts in robotics and programming, offering hands-on experience in real-world applications.

2.	Versatility in Applications:
•	This mobile platform can be adapted for multiple applications, such as agricultural monitoring, automated surveying, and scientific research gathering data from difficult-to-reach locations.

3.	Emerging Technology Exposure:
•	Engagement with the latest technologies, including ROS and Wi-Fi integration, prepares the development team for industry trends and enhances their skill sets.

4.	Platform for Innovation:
•	Developing this platform can serve as a foundation for future projects, allowing for the incorporation of advanced features like AI-driven navigation and remote telemetry.

5.	Community Collaboration:
•	Open-sourcing the development of the platform can foster a community of developers and enthusiasts who can contribute improvements, share findings, and expand the capabilities of the mobile platform collaboratively.


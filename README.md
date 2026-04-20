# Jichen Chai | Electrical Engineering @ Georgia Tech
**Specializing in Robotics, Autonomous Systems & Signal Processing**

---

## Summary
I am an Electrical Engineering undergraduate at **Georgia Tech** with a focus on robotics and physical AI. I bridge the gap between high-level autonomous navigation and low-level embedded systems. Currently, I am conducting research on a **quadrupedal navigation** project, aiming to optimize how machines perceive and traverse complex environments.

---

## About Me
My journey in engineering is driven by the persistent challenge of making machines "see" and "think" in real-time. I am fascinated by the intersection of high-level perception and low-level execution, aiming to bridge the gap between abstract algorithms and tangible robotic movement. To me, a robot is not just a collection of parts; it is a complex organism that requires seamless integration of vision, logic, and physical response to navigate the unpredictability of the real world.

My technical narrative is defined by versatility and a willingness to dive into every layer of the stack. I have managed the precision required to control optical systems and developed high-fidelity UAV simulations using ROS 2 and Gazebo. These virtual environments serve as the perfect sandbox for testing autonomous behaviors before they hit the tarmac. However, I am most at home during the "hands-on" phase of development. Whether I am meticulously debugging a custom PCB, optimizing sensor fusion pipelines, or fine-tuning a PID controller to ensure a quadruped maintains its balance on uneven terrain, I thrive on the iterative process of trial and error. I believe that true innovation in robotics stems from this holistic approach—understanding the silicon as deeply as the software.

Now I'm interested in embodied AI, physical AI, and the integration of robotic control, AI and physical world. 

**Technical Toolkit:** * **Languages:** C/C++, Python, Java, MATLAB.
* **Tools:** ROS 2, Gazebo, PX4, Altium Designer, Unity, Git.
* **Languages:** English, Chinese, Japanese.

---

## Project Showcase: Testing and Triggering Failures in Quadrupedal robots

### 1. Project Idea:
Quadrupedal robots represent a frontier in mobile robotics because of their ability to traverse terrain. Unlike wheels, which require continuous flat surfaces, legged systems can step over obstacles, climb stairs, and navigate rubble.
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/d9a0d389-3785-4829-b022-aca5942727ee" />

#### Why Failure Testing?
* **Defining the Operational Envelope:** Knowing exactly what slope or step height causes a system to fail.
* **Safety and Reliability:** Identifying software or balance triggers that could lead to catastrophic hardware damage.
* **Robustness Improvement:** Providing data-driven insights to improve control algorithms.

## 2. Project Progress:

1.  **System Integration:** I began by configuring a native Ubuntu 22.04 environment on my laptop to ensure compatibility with high-performance robotics middleware.
2.  **Environment Setup:** I successfully set up the simulation environment (Gazebo/RVIZ).
3.  **Framework Deployment:** I identified, downloaded, and installed a robust open-source quadrupedal project to serve as the foundation for my testing.
4.  **ROS 2 Mastery:** I learned to develop within the **Robot Operating System 2 (ROS 2)** ecosystem, mastering the nodes and communication protocols used to control the robot.
5.  **Systematic Failure Testing:** After observing that the robot struggled with non-flat terrain, I conducted systematic tests on ramps and stairs to collect data on exactly when and why the robot would break.

https://github.com/user-attachments/assets/f269bd02-b803-415c-9bdf-4f8ccd388116

## 3. Project Successes and Failures

The primary output of my testing is a data-driven plot showing the **Relationship of Ramp vs. Failure Rate**.
<img width="376" height="226" alt="image" src="https://github.com/user-attachments/assets/1bdd31ce-3c28-47d0-b232-699863dc7e6c" />


## 4. ECE Skills Gained

* **Programming:** Gained hands-on experience in **ROS 2** development and architecture.
* **Simulation Tools:** Learned how to utilize industry-standard simulation software to model physical environments.
* **Robot Operations:** Developed the skills to operate complex robotic systems and interface with specialized **APIs** to command motion and poll joint-state data.
* **Data Analysis:** Learned to collect and interpret telemetry data to improve system performance.

## 5. Final Thoughts

Completing this project has been an invaluable experience. It has deeply reinforced my interest in my chosen thread, providing a practical perspective on the challenges of autonomous locomotion.

I am eager to continue this project further. I believe the next step is to use the data I’ve collected to refine the control laws, with the goal of decreasing the failure rate on the very ramps and stairs I tested this semester.


---

## Resume
Click the link below to view or download my latest ECE Career Fair resume.

[**Download Resume (PDF)**](./Chai_Resume.pdf)

---

## Career Goals
My "ECE Roadmap" is focused on the intersection of **Autonomous Driving and Embedded AI.**

1.  **Short-term:** Secure a 2026 Summer Internship in embodied AI, world model or physical AI to apply my research in robotics to industry-scale problems.
2.  **Mid-term:** Complete my B.S. at Georgia Tech (May 2027).
3.  **Long-term:** Become a Lead Systems Architect for autonomous vehicle platforms, developing the hardware-software stacks that will define the future of mobility. 

---

## 🛠 Technical Projects

### Featured: Optical Light-sheet Microscope | Imaging System Control
**Overview:**
This project explores the control of electrical-optical components such as galvo mirror, electrical tunable lens (ETL), and digital mirror device(DMD) for millisecond-level synchronization and adaptive stability of 4D (3D+t) volumetric imaging for zebarfish cardiact study. My work focuses on developing a robust model to analyze system-level nonlinear autonomy behaviors, and designing a vision-based feedback optimization framework (PID controller).

* **Key Results:** Synchronized the detection and illumination arm by controlling electrical components and achieved near-perfct imaging quality.
* **Technical Detail:** Utilizing C/C++/Python to program hardware-software integration software.
* **Introduction Video:** [Video Link](https://www.youtube.com/watch?v=a0U61sElaWA)
* **Poster:** [Poster](./Poster.jpg)
![Poster](https://github.com/user-attachments/assets/ded28cda-2d4c-4d1a-af41-4eff4e6aaf49)

### Quadrupedal Navigation Research
**Overview:**
This project explores autonomous navigation for quadrupedal robots in unstructured environments. My work focuses on integrating sensor fusion data to improve path-planning efficiency.

* **Key Results:** Successfully implemented a real-time obstacle avoidance layer that reduced navigation latency by 15%.
* **Technical Detail:** Utilizing ROS 2 for inter-process communication and Gazebo for high-fidelity physics simulations.


### UAV Simulation Model
Developed a simulation model for an unmanned aerial vehicle (UAV) using the PX4 flight control platform. 
* **Goal:** Test autonomous flight algorithms in a risk-free virtual environment.
* **Tools:** ROS 2, Gazebo, PX4.

### VR Cardiac Cell Visualization
Engineered a 3D data visualization suite using Unity and C# to help researchers visualize complex biological data in a virtual space.

---

## Contact
* **LinkedIn:** [linkedin.com/in/jichenchai](https://www.linkedin.com/in/jichen-chai-582171287)
* **Email:** [jchai49@gatech.edu]
* **Location:** Atlanta, GA

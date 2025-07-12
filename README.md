# Arm_Mechanical_Simulation
Our Matlab Arm simulation
Steps;
1) Download and configure MATLAB 2025 with Simulink Multibody
2) Open Arm_URDF_2025.slx
3) Open the MATLAB Files Explorer to the Arm_Simulation folder where Arm_URDF_2025.slx is contained

<img width="2376" height="1510" alt="image" src="https://github.com/user-attachments/assets/613fc6c3-9e93-46b8-871b-b0ed06115979" />

5) The MATLAB model will open automatically
6) Set the length of the Simulation under: Simulation -> Stop time
   
<img width="2558" height="580" alt="image" src="https://github.com/user-attachments/assets/ee3fc527-6024-4e03-b54c-9c4248f76183" />

7) To change scenario, double click the signal block corresponding to each joint
<img width="764" height="528" alt="image" src="https://github.com/user-attachments/assets/69ccb46c-60e5-42d0-b3b7-116b841523a3" />

8) Open the Signal Editor
   
<img width="1928" height="1257" alt="image" src="https://github.com/user-attachments/assets/c9d789d3-77af-4b3f-9605-7066eb6f7d5f" />

9) Enter the data points to create the displacement graph that the joint will follow. Values entered at each time will correspond to the angular displacement in radians that the joint will follow at each point in time. (Note: The 1st and 2nd derivatives of such a graph are angular velocity and angular acceleration, so the steeper the graph, the faster the motion)
10) Ensure the plot covers a time range that is at least as long as the simulation Stop time
11) Save the plot and exit Signal Plotter
12) Click Apply and exit Signal block configuration

13) Double-click on the Scope to open the Joint Torque graphers.

<img width="514" height="633" alt="image" src="https://github.com/user-attachments/assets/2b4402b8-57b1-4b33-bae0-9d205387885b" />

<img width="2559" height="1479" alt="image" src="https://github.com/user-attachments/assets/0eec42e9-9117-45f6-8f70-82a6dda79131" />

13) The graphs show Torque (N*m) vs time (s) for each noted joint

14) Click Run under: Simulation -> Simulate -> Run to start simulation

<img width="2558" height="580" alt="image" src="https://github.com/user-attachments/assets/61f39bb7-6a6f-4e73-89dc-76f1cdcc8724" />

15) To edit the masses of individual linkages or joints go to: Modeling -> Design -> Model Workspace and edit each variable.

<img width="2560" height="428" alt="image" src="https://github.com/user-attachments/assets/3cce919b-d12c-4ea6-ad16-ab4683757c6a" />
    
<img width="2059" height="1068" alt="image" src="https://github.com/user-attachments/assets/632d2342-495d-4449-b6f4-539a615a3dc2" />




Virtual Intelligent Machine – Object Sorting System

This document describes the **Virtual Intelligent Machine (VIM) project, a smart, automated system designed to sort objects into five different boxes using intelligent decision-making, vision processing, and programmable logic control. The system simulates a real-world industrial environment by integrating vision, communication, and control technologies to automate object classification and sorting.


Project Description

The Virtual Intelligent Machine (VIM) is a digital simulation of an intelligent automation system that performs real-time sorting of objects. It is built to replicate how smart factories function using interconnected systems. The VIM uses a vision system to recognize objects, CODESYS Sequential Function Chart (SFC) to control decision-making logic, and OPC UA protocol to enable communication between different parts of the system.

The goal is to simulate how a machine can make informed decisions without being explicitly programmed for every scenario, demonstrating the concept of intelligent, adaptable automation.


System Workflow

1. An object is introduced into the system.
2. The Python-based vision system detects and classifies the object based on predefined characteristics (e.g., color, shape, or size), the objects are car, scissors, apples, screwdriver and cup
3. This information is sent to the CODESYS control logic via OPC UA.
4. CODESYS uses SFC logic to determine which of the five boxes the object should be placed into.
5. The object is sorted virtually into the corresponding box.
6. A feedback mechanism allows the system or user to record errors and improve the sorting process over time.



Technologies Used

1. Python: Used for the vision system script that detects and classifies objects.
2. OpenCV: For image processing and object recognition in the vision system.
3. CODESYS: A platform for PLC programming, used here for writing and executing the SFC logic controlling the sorting process.
4. OPC UA: A communication protocol that allows data exchange between the Python vision system and the CODESYS logic.
5. Digital Twin Simulation: Representing the real-world process in a virtual environment, helping visualize sorting actions.



Key Features

1. Real-time object recognition and classification
2. Automatic sorting into five virtual boxes
3. Communication between independent system components using OPC UA
4. Intelligent decision-making through control logic
5. Potential to learn from feedback and improve over time



Future Improvements

1. Integrating machine learning models for more advanced object classification.
2. Adding a physical hardware component to move from virtual to real-world application.
3. Enhancing the learning system to incorporate historical data and feedback loops.
4. Creating a full-scale dashboard or interface to monitor sorting performance in real time.


Author

Ibukunoluwa Theresa Ajibare Asuni
MSc Intelligent Automation
University of Skövde, Sweden


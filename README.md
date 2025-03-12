# FPGA-Based-Real-Time-Heart-Rate-Monitoring-System
The project aims to develop an FPGA-based real-time heart rate monitoring system. It processes PPG/ECG sensor signals, filters noise, calculates BPM, and displays results on a 7-segment display or LED. Implemented using Vivado and VHDL, it ensures fast, efficient heart rate detection using DSP techniques.




________________________________________
🔷 Page 1: Introduction

This project is about designing a system using an FPGA (a type of programmable chip) to measure and display heart rate in real-time. It takes input from a heart rate sensor, removes unnecessary noise, calculates beats per minute (BPM), and shows the result on LEDs or a 7-segment display. The system is built using Vivado software and programmed using VHDL (a coding language for hardware).

Imagine a fitness smartwatch that monitors your heart rate, but instead of using a small processor inside, this project builds the system on a high-speed programmable chip (FPGA). This means the heart rate is calculated instantly and displayed without delays, making it highly efficient for medical applications.
________________________________________
🔷 Page 2: Equipment Used

•	The project requires hardware like an FPGA board (Nexys A7-100T), a heart rate sensor, and a display unit (LEDs or 7-segment display).
•	Software tools like Vivado are used to design and program the FPGA, and VHDL is the coding language used to create the logic inside the FPGA.

Think of the FPGA board as the brain, the heart rate sensor as the eyes, and the display (LEDs) as the mouth that tells us the heart rate. The Vivado software is like a notebook where we write instructions (VHDL code) to tell the FPGA how to work.
________________________________________
🔷 Page 3-4: Step-by-Step Procedure
1.	Setting Up Vivado & FPGA:
o	Install the required software and set up the FPGA board to communicate with the computer.
2.	Creating the Digital Heart Rate Monitor in FPGA:
o	Writing code to read signals from the sensor, clean the signal, detect heartbeats, and display BPM.
3.	Configuring Constraints File:
o	This file is like a map that tells the FPGA which pin is connected to which sensor or LED.
4.	Synthesizing & Implementing the Design:
o	This process translates the code into real hardware logic inside the FPGA, making it ready to process signals.
5.	Programming the FPGA & Testing Output:
o	The final step where we send our design into the FPGA, and it starts working as a real-time heart rate monitor.

Imagine teaching a new employee how to take a patient’s heart rate.
1.	Give them a training manual (Vivado setup).
2.	Teach them to listen carefully to the heartbeat (signal processing).
3.	Show them where to write the readings (mapping inputs & outputs).
4.	Give them a test run (synthesis & implementation).
5.	Finally, let them start checking real patients (programming FPGA & testing).
________________________________________
🔷 Page 5: Results

•	The FPGA correctly measured real-time heart rate and displayed it on the 7-segment display/LEDs.
•	The system accurately detected beats per minute (BPM) and removed unwanted noise from the signals.
•	The FPGA implementation was fast, efficient, and reliable compared to regular software-based processing.

The heart rate monitor worked as expected, showing accurate readings instantly, like a fitness watch that never lags. It removed unnecessary signals (like body movements) to ensure the heart rate was displayed correctly.
________________________________________
🔷 Page 6: Conclusion & Future Improvements

•	The FPGA heart rate monitor was successfully implemented with real-time processing.
•	It performed better than software-based solutions because it is hardware-accelerated.
•	Future upgrades could include:
    Better noise filtering for even more accurate readings.
    Wireless connectivity (Bluetooth/Wi-Fi) to send data to mobile apps.
    Graphical display (LCD screen) for a better user experience.

The project successfully built a fast and accurate heart rate monitor using FPGA. In the future, it can be improved with wireless technology (like smartwatches) and a more detailed display (like hospital monitors).
________________________________________
Final Thoughts:
This project is a real-world application of technology in healthcare. 
✔ Market Potential: FPGA-based monitors can be faster and more reliable than software-based ones.
✔ Innovation Scope: Adding wireless features can help doctors monitor patients remotely.
✔ Cost Efficiency: FPGA solutions can be optimized for low-cost production in healthcare tech.



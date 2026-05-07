# Saveetha-School-of-Engineering-Laboratory-Experiments-for-High-performance-computing
Laboratory Experiments for ECA60 High performance computing

The High Performance Computing Laboratory course provides practical exposure to FPGA-based digital system design using RTL, Vivado IP Integrator, and Vivado HLS methodologies. The laboratory focuses on developing efficient digital circuits for signal processing, image processing, and AI-related applications using Verilog HDL and Xilinx Vivado tools.

This course helps students understand the complete FPGA design flow including coding, simulation,  and verification of digital systems. The experiments cover clock generation, counters, filters, image thresholding, image intensity inversion, waveform generation, and AI-oriented RTL modules such as convolution and pooling layers.

The laboratory also introduces students to different FPGA design approaches including RTL-based design, IP-based design, and High-Level Synthesis (HLS). Through these experiments, students gain hands-on experience in hardware-oriented computing techniques widely used in embedded systems, digital signal processing, image processing, and artificial intelligence applications.

Software used:

1. Xilinx Vivado (RTL design, Vivado HLS, IP based design)
2. Jupyter notebook

RTL Based Design
1. Design of Clock Divider Circuit using RTL

Implementation of a Verilog-based clock divider circuit to generate lower-frequency clock signals from a high-frequency input clock using RTL design methodology. Simulation and timing verification are performed using Xilinx Vivado.

2. Testbench for I/O File Transfer

Development of a Verilog testbench for file input/output operations, demonstrating reading stimulus data from files and writing simulation outputs for verification purposes.

3. Design of Moving Average Filter using Verilog

Implementation of a digital moving average filter in Verilog HDL for smoothing noisy input signals. The design demonstrates sequential logic, accumulation, and averaging operations.

4. Design of Peak Detection on ECG Signal using Xilinx Vivado

Development of an RTL-based peak detection system for ECG signal analysis using Xilinx Vivado. The project identifies R-peaks for basic cardiac signal processing applications.

5. Design of Image Thresholding using Xilinx Vivado (Gray to Binary Image Conversion)

Implementation of grayscale to binary image conversion using thresholding techniques in Verilog HDL. The design processes image pixels and converts them into binary images based on a predefined threshold value.

6. Design of Image Intensity Inversion Circuit using Xilinx Vivado

RTL implementation of image intensity inversion for grayscale images using Verilog HDL. The design converts dark pixels to bright pixels and vice versa using pixel intensity transformation.

Vivado IP Based Design
7. Generation of Sine/Cosine Wave using DDS Compiler IP

Design and simulation of sine and cosine waveform generation using the DDS Compiler IP available in Xilinx Vivado IP Catalog.

8. Design of Block RAM IP using Xilinx Vivado

Implementation and configuration of Block RAM (BRAM) IP in Vivado for efficient on-chip memory storage and retrieval applications.

9. Addition of Two Signals using Vivado IP Catalog Based Design

Design of a signal addition system using Vivado IP Integrator and IP Catalog components for arithmetic signal processing applications.

10. Design of Counter Circuit using Vivado IP

Implementation of a configurable counter using Vivado IP-based design methodology with simulation and waveform verification.

11. Generation of Clock Signal using Clocking Wizard IP

Design of multiple clock frequencies using the Clocking Wizard IP in Xilinx Vivado for FPGA clock management applications.

Vivado HLS Based Design
12. Addition of Two Sine Waves using Vivado HLS

High-Level Synthesis (HLS) implementation of sine wave addition using C/C++ design flow and conversion into synthesizable hardware using Vivado HLS.

13. Design of Counter with Increment of N using Vivado HLS

Implementation of a parameterized counter with customizable increment values using Vivado HLS and C/C++ based hardware design methodology.

14. Design of Image Thresholding using Vivado HLS (Gray to Binary Image Conversion)

HLS-based image thresholding implementation for grayscale to binary image conversion using C/C++ and synthesis through Xilinx Vivado HLS.

15. Design of Image Intensity Inversion Circuit using Vivado HLS

Implementation of image intensity inversion using High-Level Synthesis techniques for FPGA-based image processing acceleration.

AI Based Design
16. Design of Convolutional Layer using RTL

RTL implementation of a convolutional neural network (CNN) convolution layer using Verilog HDL for basic AI hardware acceleration applications.

17. Design of Max Pooling, Min Pooling, and Average Pooling Layer using RTL

Implementation of different pooling operations used in CNN architectures using RTL design techniques in Verilog HDL.

18. Design of Fully Connected Network using RTL

Development of a fully connected neural network layer using Verilog HDL for FPGA-based artificial intelligence accelerator design.

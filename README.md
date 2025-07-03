# FPGA-project-1
FPGA-Accelerated Mandelbrot Set Visualizer
This project demonstrates an FPGA-based implementation of the Mandelbrot Set calculation, designed for visualizing this famous fractal. As an FPGA beginner, I leveraged online tutorials to learn how to translate a mathematical algorithm into RTL-level Verilog for hardware acceleration.

The core of the project involves an FPGA calculating Mandelbrot iterations using fixed-point arithmetic. A Python script on the PC facilitates communication via UART, sending C values to the FPGA and receiving the computed iteration counts. This setup showcases basic hardware acceleration for computationally intensive tasks.

Key Features:

FPGA-based fixed-point arithmetic for Mandelbrot iteration.

UART communication for PC-FPGA data exchange.

Modular Verilog design practices.

A practical example of algorithm implementation on FPGA for beginners.

Tools Used:

Hardware Description Language: Verilog

FPGA Platform: (Xilinx, Arty S7-50)

FPGA Toolchain: Vivado

Software: Python

# Design-of-a-Simple-General-Purpose-Processor

## Overview

This project involves the design and implementation of a **general-purpose processor** using **VHDL** and an **FPGA**. The processor was developed by integrating multiple digital logic components, including registers, an arithmetic logic unit (ALU), a finite state machine (FSM), and a decoder.

The project demonstrates how individual digital components can be combined to create a functional processor capable of performing arithmetic and logical operations.

## Features

* Designed and implemented an **8-bit processor architecture** using VHDL.
* Developed an **8-bit Arithmetic Logic Unit (ALU)** for arithmetic and logical operations.
* Implemented registers for storing and transferring data.
* Used an FSM to control processor operations.
* Implemented a **4-to-16 decoder** for operation selection and control logic.
* Connected processor components using multi-bit buses.
* Displayed processor results using **7-segment displays**.
* Simulated and verified processor functionality using Quartus.
* Implemented the completed processor on FPGA hardware.

## Processor Components

The processor was developed by integrating several digital components.

### Arithmetic Logic Unit (ALU)

The 8-bit ALU performs arithmetic and logical operations on input data. The ALU receives data from processor registers and produces the corresponding output based on the selected operation.

### Registers

Registers are used to temporarily store 8-bit data within the processor. They allow data to be transferred between different components during processor operations.

### Finite State Machine

An FSM was implemented to control the sequence of processor operations. The state machine determines which operations are performed and controls the movement of data through the processor.

### 4-to-16 Decoder

The decoder converts control inputs into individual output signals used to select specific processor operations and control the ALU.

### 7-Segment Display

The processor output is connected to two 7-segment displays, allowing the 8-bit result to be displayed in hexadecimal format.

## Technologies Used

* **VHDL**
* **Intel Quartus**
* **FPGA hardware**
* Digital logic design
* Finite State Machines
* Registers
* Arithmetic Logic Units
* Decoders
* 7-segment displays


## Design Process

The processor was developed by building and testing individual components before integrating them into the complete system.

### 1. Component Development

Individual VHDL modules were created for the processor's registers, ALU, decoder, and control logic.

### 2. Control Logic

An FSM was developed to control the sequence of operations and determine how data moves through the processor.

### 3. Module Integration

The individual components were connected using 8-bit buses and clock-controlled signals to form the complete processor architecture.

### 4. Simulation and Verification

The processor was simulated in **Quartus** to verify that the individual components and overall system operated as expected.

### 5. FPGA Implementation

After verification, the processor was implemented on FPGA hardware and the resulting values were displayed using 7-segment displays.

## Skills Demonstrated

This project demonstrates experience with:

* VHDL programming
* FPGA development
* Digital logic design
* Processor architecture
* ALU design
* Finite state machines
* Register design
* Decoder implementation
* Hardware simulation and verification
* Modular system design
* Digital circuit integration
* 7-segment display interfacing

## Purpose

The purpose of this project was to gain practical experience designing a processor from individual digital logic components. The project demonstrates how hardware modules can be designed, tested, and integrated using **VHDL and FPGA technology** to create a functional computing system.


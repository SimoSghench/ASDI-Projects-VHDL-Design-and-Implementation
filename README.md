# ASDI Projects – VHDL Design and Implementation

This repository contains two major projects developed during the ASDI course at *Università degli Studi di Napoli Federico II* in 2022. These projects demonstrate various digital design techniques using VHDL, covering topics ranging from handshake protocols and interconnection networks to processor microprogramming and arithmetic units.

## Overview

The projects are divided into two main documents:

- **Esame.pdf**  
  This document presents the exam project "Esame ASDI" by Simone D’Orta. It focuses on designing a VHDL system where one unit (A) sends N pairs of bytes to another unit (B) for addition. The design incorporates:
  - Decomposition into operational and control units.
  - A bit-by-bit handshake protocol using signals such as `data_ready` and `accepted`.
  - Detailed VHDL code, simulation results, and testbench implementations.

- **Progetto ASDI.pdf**  
  This comprehensive project covers a wide range of digital system design exercises. It includes chapters on:
  - **Multiplexer and Interconnection Networks:** Design and implementation of multiplexers (e.g., 16:1) and demultiplexers using both structural and behavioral approaches.
  - **BCD Encoder and Display Systems:** Implementation of a Binary-Coded Decimal encoder, including synthesis on board with LED and 7-segment displays.
  - **Sequence Recognizer:** Design of a finite state machine to detect a specific bit sequence.
  - **Shift Registers and Chronometers:** Development of shift registers (both behavioral and structural) and a chronometer with FPGA synthesis details.
  - **Automatic Testing and Handshaking:** Projects on automated testing of combinatorial circuits and communication systems employing handshaking protocols.
  - **Processor and UART Systems:** Analysis and modification of a simple IJVM processor along with UART-based communication designs.
  - **Additional Topics:** Multistage switching, arithmetic machines (e.g., the Robertson multiplier), and a free exercise integrating multiple communication nodes.

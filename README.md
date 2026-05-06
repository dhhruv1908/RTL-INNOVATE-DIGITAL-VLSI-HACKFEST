# Peak Detector for Streaming Data

A Verilog-based digital system designed to detect peaks (local maximum values) in a continuous streaming data sequence. The project compares sequential input values and identifies a peak when the current value is greater than its immediate neighbors.

## Features

* Sequential data processing
* Peak detection using comparator-based logic
* Handles continuous streaming inputs
* Reset functionality for initialization
* Testbench for simulation and verification
* Waveform analysis support using GTKWave/ModelSim

## Peak Detection Condition

A peak is detected when:

```text
prev < curr > next
```

## Technologies Used

* Verilog HDL
* Testbench Simulation
* Digital Logic Design
* FPGA/EDA Tools (ModelSim, Vivado, etc.)

## Applications

* Signal Processing
* Sensor Data Monitoring
* Real-Time Data Analysis
* Embedded Systems

## Project Objective

To design and verify a hardware-based peak detector capable of identifying local maxima in streaming data efficiently and accurately.

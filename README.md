# Configurable Active Filter Bank for Analog Signal Processing

## Overview

This project presents the design and simulation of a configurable active filter bank using operational amplifiers in LTspice. The objective is to study and compare the behavior of different second-order active filters commonly used in analog signal processing applications.

The project implements and analyzes the following filter responses:

- Low-Pass Filter (LPF)
- High-Pass Filter (HPF)
- Band-Pass Filter (BPF)
- Notch (Band-Stop) Filter

Each filter was designed to meet specific frequency characteristics and evaluated using multiple LTspice simulation techniques.

---

## Objectives

- Design second-order active filters using operational amplifiers.
- Analyze frequency response and cutoff frequencies.
- Compare different filter responses for analog signal processing.
- Study the effect of resistor and capacitor values on filter performance.
- Validate filter characteristics using LTspice simulations.

---

## Filter Configurations

### Low-Pass Filter
- Passes frequencies below the cutoff frequency.
- Attenuates higher-frequency components.
- Suitable for removing high-frequency noise.

### High-Pass Filter
- Passes frequencies above the cutoff frequency.
- Removes DC offset and low-frequency interference.

### Band-Pass Filter
- Allows only a selected range of frequencies to pass.
- Rejects frequencies outside the desired bandwidth.

### Notch Filter
- Rejects a narrow frequency band around the center frequency.
- Commonly used for suppressing 50 Hz or 60 Hz power-line interference.

---

## Circuit Design

Each filter is implemented using second-order active filter topology with operational amplifiers and RC networks.

The design process includes:

- Selection of cutoff frequency
- Calculation of resistor values
- Capacitor selection
- Gain verification
- Frequency response validation

---

## Simulations Performed

### AC Sweep (Bode Plot)

Used to evaluate:

- Magnitude response
- Phase response
- Cutoff frequency
- Roll-off characteristics

---

### Transient Analysis

Performed to observe:

- Time-domain response
- Output waveform
- Filter behavior with sinusoidal inputs

---

### FFT Analysis

Used to examine:

- Frequency spectrum
- Harmonic components
- Signal attenuation after filtering

---

### Parameter Sweep

Performed by varying resistor and capacitor values to observe changes in:

- Cutoff frequency
- Bandwidth
- Filter response

---

## Results

The simulations demonstrate the expected behavior of each filter type.

| Filter | Primary Function |
|---------|------------------|
| Low-Pass | Removes high-frequency noise |
| High-Pass | Removes DC and low-frequency components |
| Band-Pass | Selects a desired frequency band |
| Notch | Rejects narrow-band interference (e.g., 50 Hz) |

Simulation results include:

- Frequency response plots
- Time-domain waveforms
- FFT plots
- Component parameter comparison

---

## Software Used

- LTspice XVII
- Analog Devices LTspice Simulator

---


## Key Concepts

- Active Filters
- Operational Amplifiers
- Frequency Response
- Bode Plot
- Cutoff Frequency
- Roll-off Rate
- Bandwidth
- Quality Factor (Q)
- Analog Signal Processing

---

## Future Improvements

Possible extensions include:

- Adjustable cutoff frequency
- Higher-order filter implementation
- Comparison of different active filter topologies
- Filter optimization for audio applications
- PCB implementation and hardware validation


**Your Name**

Analog Circuit Design | LTspice | Active Filters

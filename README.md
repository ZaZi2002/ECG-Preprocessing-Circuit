# ECG Signal Preprocessing Simulation in LTSpice

## Overview

This project involves simulating the preprocessing of ECG signals using LTSpice. The simulation includes a pre-amplifier, a bandpass filter, a notch filter, and a post-amplifier. The goal is to process the raw ECG signal to improve its quality and remove noise.

## Components

1. **Pre-Amplifier**: Boosts the amplitude of the ECG signal before filtering.
2. **Bandpass Filter**: Removes frequencies outside the range of interest for ECG signals (typically 0.5 Hz to 100 Hz).
3. **Notch Filter**: Removes specific unwanted frequencies, such as the power line interference at 50/60 Hz.
4. **Post-Amplifier**: Further amplifies the filtered signal to a suitable level for analysis or recording.

## Requirements

- **LTSpice**: A circuit simulation software for designing and analyzing electronic circuits.

## Results

After simulating each component, output signals are shown as jpegs. As seen ECG signal is appropriately amplified and filtered.

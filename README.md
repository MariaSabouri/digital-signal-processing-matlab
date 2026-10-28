# Digital Signal Processing with MATLAB

MATLAB implementations of digital signal processing techniques, including signal quantization, fixed-point representation, and FIR/IIR filtering for sinusoidal noise removal.

## Project Overview

This project was completed as part of the Digital Signal Processing (DSP) course at Shahid Beheshti University during the first semester of the 2025–2026 academic year.

The project focuses on two main topics: quantization of digital signals and removal of sinusoidal noise from audio signals using digital filters.

## Tasks

### 1. Signal Quantization and Fixed-Point Representation

A two-tone sinusoidal signal was generated and quantized using different quantization levels and fixed-point representations.

The main tasks included:

- Generating a two-tone signal with frequencies of 440 Hz and 1200 Hz.
- Using a sampling frequency of 8 kHz and a signal duration of 0.1 seconds.
- Implementing midrise quantization with 4, 8, and 16 quantization levels.
- Calculating quantization errors and comparing the original and quantized signals.
- Investigating fixed-point representations with word lengths of 8 and 16 bits.
- Examining the effects of fractional length, rounding methods, and overflow handling.

### 2. Sinusoidal Noise Removal Using FIR and IIR Filters

An audio signal contaminated by a 600 Hz sinusoidal noise component was analyzed and processed using digital filters.

The main tasks included:

- Designing FIR and IIR filters to suppress the 600 Hz noise.
- Analyzing the pole-zero locations and frequency responses of the designed filters.
- Comparing the filtering performance of FIR and IIR approaches.
- Investigating noise-frequency estimation using time-domain waveforms and frequency spectra.

## Tools and Technologies

- MATLAB
- Digital Signal Processing
- Signal Quantization
- Fixed-Point Arithmetic
- FIR and IIR Digital Filters
- Frequency-Domain Analysis
- Pole-Zero Analysis

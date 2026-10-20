# Fourier Analysis and Sound-Triggered Recording

A student research project presented for the 2025 Student Scientific Communications Session at the Faculty of Electronics, Telecommunications and Information Technology, POLITEHNICA Bucharest.

**Original paper:** Transformata Fourier: Un instrument esential in analiza sunetelor

## Overview

The research explores Fourier analysis as a tool for understanding audio signals. It also describes a sound-triggered audio-video recording system combining Arduino-based sound detection with Python on a computer.

## System workflow

1. Arduino monitors the sound level.
2. When the measured level exceeds a threshold, Arduino sends a message over serial.
3. A Python program receives the message and starts audio-video recording.
4. Recording stops after a silence event or a maximum recording interval.
5. The program saves the output and clears temporary files.

## Topics

- Fourier series and Fourier transform
- Time-domain and frequency-domain audio analysis
- Sound detection and threshold-based triggering
- Arduino-to-Python serial communication
- Event-driven recording

## Research context

The paper was written by a four-student team under the supervision of Prof. Antonela Toma. It discusses both signal-processing theory and a practical audio-video monitoring workflow.

## Materials

An English overview, selected figures and reviewed implementation files will be added here. The original report is not yet uploaded to avoid publishing personal information without review.

## Status

Research summary available - implementation materials in preparation.

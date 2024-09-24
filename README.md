# Analog Function Generator

## Overview
This repository contains the design and implementation details of an Analog Function Generator capable of producing multiple waveforms. This device offers adjustable parameters such as frequency, amplitude, and DC shift, suitable for a wide range of applications in electronics testing and research.

## Key Features
- **Waveforms**: Generates sine, triangle, saw-tooth, square, and PWM waves.
- **Frequency Range**: Adjustable from 20 Hz to 20 kHz.
- **Amplitude Control**: 0 to 10 V peak-to-peak with fine resolution adjustments.
- **DC Shift and Duty Cycle**: Adjustable DC shift and variable duty cycle from 2% to 98% for PWM waves.
- **Energy Efficiency**: Optimized for low power consumption while maintaining high-quality output.

## Specifications
- **Frequency Accuracy**: ±0.1%.
- **Amplitude Resolution**: 0.1V.
- **Output Characteristics**: Capable of driving a 50-ohm load, with minimal harmonic distortion (less than 0.5% for sine waves).

## Hardware Design
### Circuit Components
- **Operational Amplifiers**: AD711JN, TL072CP, AD712JN for precise waveform generation.
- **Transistors**: TIP31C and TIP32C in a class-AB push-pull configuration for enhanced current driving capabilities.

### PCB and Enclosure
- **PCB**: Designed with Altium as a two-layer board, focusing on efficient current handling and signal integrity.
- **Enclosure**: Robust design using SolidWorks, ensuring durability for lab environments.

## Control Panel
- **Wave Selection**: Toggle between different waveforms.
- **Frequency and Amplitude Adjustments**: Dedicated knobs for setting the waveform frequency and amplitude.
- **Duty Cycle Control**: Separate controls for adjusting the duty cycle of PWM and saw-tooth waveforms.

## Testing and Performance
Extensive testing on breadboards followed by final PCB implementation confirms that the function generator meets all specified performance criteria, with precise control over waveform characteristics.

## Acknowledgements
Grateful acknowledgment to Mr. Pankajan for mentorship, and thanks to the project team for their dedicated efforts:
- [Alahakoon U.M.Y.B.](https://github.com/YasiruAlahakoon)
- [Dulnath W.H.R.]()
- [Hansindu K.A.A.](https://github.com/AchiraHansindu)
- [Shamika K.A.M.]()

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/AchiraHansindu/Analog-Function-Generator/blob/main/LICENSE) file for details.

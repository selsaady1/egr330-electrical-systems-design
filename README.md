# Design of Electrical Systems

> Analog peak detector network plus a semester of electrical systems labs

![MultiSim](https://img.shields.io/badge/MultiSim-0a7?style=flat-square) ![Analog Discovery board](https://img.shields.io/badge/Analog_Discovery_board-0a7?style=flat-square) ![Breadboard prototyping](https://img.shields.io/badge/Breadboard_prototyping-0a7?style=flat-square) ![Op-amps, diodes, capacitors (analog discrete circuits)](https://img.shields.io/badge/Op--amps%2C_diodes%2C_capacitors_%28analog_discrete_circuits%29-0a7?style=flat-square) ![Excel (efficiency plotting)](https://img.shields.io/badge/Excel_%28efficiency_plotting%29-0a7?style=flat-square) 

### 🌐 Live project page → **https://selsaady1.github.io/egr330-electrical-systems-design/**

## Overview
Coursework from ASU EGR 330: Design of Electrical Systems (Spring 2023), centered on a five-person team final design project to build and validate a peak detector network. The repository pairs the full team report and final presentation with a sequence of weekly hands-on labs covering optocouplers, BJT amplifiers, logic gates, and switched-mode power supplies. Saif led the real-world applications research and authored and edited the final report.

## Key Achievements
- Designed, prototyped, and tested an analog peak detector network that captures the extreme (positive and negative) voltage of an input signal, evaluated two candidate designs before selecting a final build.
- Validated input testing on the Analog Discovery board, recording peak detection across test signals (measured 1.98, 2.98, and 4.98 on three input cases).
- Iterated the design by building a second circuit board with a switch and a capacitor-recharge path so the network could reset for new data, plus output buffering.
- Completed weekly labs spanning optocoupler active-high/low and sinewave networks, a VDB Class A amplifier (measured Bdc = 183), an AND gate via cutoff/hard-saturation, and an LT1370-based SMPS boost converter with efficiency plotting.
- Used MultiSim for circuit modeling and the Analog Discovery board for waveform generation and scope measurement.

## Approach
The team followed an engineering design process: defining a problem statement, engineering goals, specifications and constraints (four-week timeline, limited provided budget), then evaluating multiple candidate designs against attributes and drawbacks. Circuits were modeled in MultiSim and breadboarded, then characterized with the Analog Discovery board for waveform input and oscilloscope output. Testing covered battery internal resistance and multi-signal input verification, with documented design changes justified by accuracy and reset requirements.

## Tools & Technologies
- MultiSim
- Analog Discovery board
- Breadboard prototyping
- Op-amps, diodes, capacitors (analog discrete circuits)
- Excel (efficiency plotting)

## Repository Structure
```
.gitignore
LICENSE
README.md
docs/2023-02-07_15-32-1.pdf
docs/2023-03-12_15-15.pdf
docs/EGR330_FINAL_PRESENTATION.pptx
docs/EGR330_Report.pdf
docs/EGR_330_Final_Design_Project_Idea.pdf
docs/Laboratory_1.17_Week_1.docx
docs/Laboratory_2.17_Week_3.docx_1_.pdf
docs/Laboratory_4.17_Week_7.docx.pdf
images/preview.png
```

## Results
The peak detector network was deemed successful: it evaluated battery internal resistance and displayed peak detection data via the Analog Discovery board across multiple input signals. Full methodology, testing data, and recommendations are in the team report (docs/EGR330_Report.pdf) and final presentation.

## Deliverable
See [`docs/EGR330_Report.pdf`](docs/EGR330_Report.pdf).

## License
MIT — see [`LICENSE`](LICENSE).

---
_Part of [Saif Elsaady's engineering portfolio](https://selsaady1.github.io/portfolio/). Deliverables only — routine homework/quizzes/exams excluded._
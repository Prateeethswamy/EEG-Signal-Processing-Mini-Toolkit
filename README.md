EEG-Signal-Processing-Mini-Toolkit
**EEG Signal Processing Mini Toolkit **
A lightweight Python toolkit for performing basic EEG signal processing and analysis using scientific computing libraries.
This project demonstrates core signal processing techniques applied to EEG data including filtering, spectral analysis, and brainwave band extraction.

**Project Overview**
This toolkit provides:
- EEG signal loading (sample data support)
- Bandpass filtering
- Fast Fourier Transform (FFT)
- Power Spectral Density (PSD) analysis
- Alpha, Beta, Theta band power extraction
- Signal visualization
It is designed for educational purposes, research prototyping, and hackathon-ready neuroscience applications.

## EEG Bands Covered
| Band   | Frequency Range | Associated State |
|--------|-----------------|-----------------|
| Delta  | 0.5 – 4 Hz     | Deep sleep      |
| Theta  | 4 – 8 Hz       | Relaxed focus   |
| Alpha  | 8 – 13 Hz      | Calm awareness  |
| Beta   | 13 – 30 Hz     | Active thinking |
| Gamma  | 30+ Hz         | High cognition  |

## Tech Stack
- Python 3.10/3.13.09
- MNE-Python
- NumPy
- SciPy
- Matplotlib


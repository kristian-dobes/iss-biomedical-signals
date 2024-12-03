# Signal Processing and Heartbeat Detection Project

This repository contains the implementation of a school project focused on processing ECG signal using various techniques. The objective was to analyze the signal, implement heartbeat (QRS complex) detection, and visualize the results. Completed as part of the ISS (Signal Processing) course at FIT VUT.

## Project Features

- **Signal Analysis**:
  - Processed and visualized ECG signal in both time and frequency domains.
  - Identified and explained artifacts such as powerline interference.

- **Resampling and Filtering**:
  - Resampled signal to a uniform sampling rate.
  - Designed and applied low-pass and band-pass filters for noise reduction and feature isolation.

- **Heartbeat Detection**:
  - Implemented QRS complex detection using threshold-based methods and autocorrelation.
  - Highlighted detected QRS complexes in signal visualizations.

## Tools Used

- **Python**: For all computations and visualizations.
- **NumPy**: For numerical computations.
- **Matplotlib**: For plotting and visualizing the signal.
- **SciPy**: For signal processing (filtering, resampling, and transformations).

## Project Structure

- `xdobes22.ipynb`: Jupyter Notebook containing all code for signal analysis, filtering, and QRS detection.
- `xdobes22.pdf`: A comprehensive project output detailing the methods and results. Steps taken during signal processing. Visualization of ECG signals before and after filtering.
Results of QRS detection and analysis.
- `xdobes22.wav`: Original ECG signal for analysis and processing.

### Prerequisites

Install the required Python libraries using pip:

```bash
pip install numpy matplotlib scipy soundfile

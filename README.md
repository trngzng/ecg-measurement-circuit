# ECG MEASUREMENT CIRCUIT

*This project is a part of Project I course in curriculum.*

The target of this project is deal with biosignal include reading from sensors, filtering and digitalizing it. 

## About ECG

Electrocardiogram (ECG) signals represent the electrical activity of the human hearts and consist of several waveforms (P, QRS, and T). The duration and shape of each waveform and the distances between different peaks are used to diagnose heart diseases.

<p align="center">
  <img src="./img/ecg_waveform.png" alt="ECG Waveform" width="300" height="auto">
</p>

## Feature

This circuit is used as a ECG sensor with AD74115 chip (SPI interface). It's comfortable for analyzing the ECG signal.

## How to use

<p align="center">
  <img src="./img/3_lead_ecg_placement.png" alt="ECG Electrodes Placement" width="300" height="auto">
</p>

## Result

<p align="center">
  The ECC signal at the input of AD74115.

  <img src="./img/ecg_waveform_result.png" alt="ECG signal in oscilloscope" width="600" height="auto">
</p>

<p align="center">
  The ECC signal after converting and plotting on GUI.

  <img src="./img/ecg_waveform_gui.png" alt="ECG signal in GUI" width="600" height="auto">
</p>s
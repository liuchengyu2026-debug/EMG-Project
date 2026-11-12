# Surface EMG Signal Acquisition and Processing System

This repository is a project showcase for our Analog Circuit course project. The objective was to design, fabricate, and validate a surface Electromyography (EMG) system to capture weak bioelectrical signals from the biceps.

> **Note:** The original design files have been archived. This repository contains the schematic overview, hardware photos, and MATLAB analysis results.

## 🛠️ System Overview
- **Analog Front-End:** INA128U Instrumentation Amplifier, OP07CP Op-Amps.
- **Filtering:** 2nd-order High-pass (50 Hz) & Low-pass (800 Hz) Sallen-Key filters, Twin-T Notch (50 Hz).
- **Hardware:** Custom PCB designed via JLC-EDA and fabricated by JLCPCB.
- **Data Processing:** MATLAB (Band-pass filtering, 49-50 Hz notch filtering).

## 📁 Repository Contents
- `Images/`: PCB layout, physical board photos, breadboard tests, and MATLAB signal plots.
- `Video Links`: https://www.bilibili.com/video/BV1qFWS6fEYB/?spm_id_from=333.1387.homepage.video_card.click

## 📊 Key Results
- Successfully acquired real-time muscle signals.
- Achieved clear waveform separation before and after MATLAB digital filtering.

## ⚠️ Disclaimer
This project is for **educational and research purposes only**. It is not a certified medical device. Do not use this design on human subjects without proper safety protocols. The circuit topology references standard literature; no original figures from external papers are claimed as our own.

## 🧑‍💻 Authors
- Chengyu Liu, Yuqian Du

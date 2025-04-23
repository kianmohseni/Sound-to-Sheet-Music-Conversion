# Project Overview

## 🎵 Sound to Sheet Music
A Python-based project to convert recorded piano melodies into sheet music by analyzing audio frequencies and durations.

## 🧠 Overview
- Goal: Automate transcription of simple piano melodies into musical notes.

- Method: Use FFT to extract dominant frequencies and map them to standard notes.

- Input: Audio recorded via Arduino or professional microphone.

- Output: A time-stamped sequence of notes representing sheet music.

## 🛠 Tools & Methods
- Python

- FFT (Fast Fourier Transform)

- Arduino + Microphone

- Thresholding & note segmentation

## ✅ Key Features
- Frequency-to-note conversion

- Duration estimation using time indices

- Real-time playback and note output

## 🔍 Results
- Accurate transcription with professional mic at 60–120 BPM

- Arduino mic showed saturation/distortion issues

- Complex rhythms and fast tempos reduced accuracy

## 🚀 Future Work
- Improve segmentation logic

- Expand to polyphonic instruments

- Add real-time visualization and MIDI output


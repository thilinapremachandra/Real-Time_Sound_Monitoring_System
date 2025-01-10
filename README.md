# Real-Time Sound Quality Monitor

## Introduction

In today's modern world, we are surrounded by an increasing amount of sound pollution, both in urban and rural areas. Vehicles, honking horns, loudspeakers, booming music, and various industrial noises are commonplace. While these sounds may seem like a normal part of daily life, prolonged exposure to high sound levels can have significant adverse effects on our health.

From causing **hearing loss**, **tinnitus**, and **sleep disturbances**, to contributing to **stress**, **cardiovascular diseases**, and **reduced cognitive function**, sound pollution is a growing concern. Monitoring and controlling noise exposure is essential to maintaining our health and well-being, especially in environments with high sound levels.

## Project Overview

This mini project is a **Real-Time Sound Quality Monitor**, designed to continuously track the sound levels in your environment, providing insights into noise exposure and offering warnings when harmful levels are detected. By calculating the **decibel (dB)** levels in real-time, the system categorizes the noise into three safety thresholds:

- **Safe**: Below 70 dB (acceptable for prolonged exposure)
- **Moderate**: Between 70–85 dB (caution advised)
- **Dangerous**: Above 85 dB (risk of health issues from prolonged exposure)

The goal is to offer a tool that helps individuals and organizations monitor noise levels and make adjustments to avoid long-term health issues caused by excessive noise.

## Features

- **Real-Time Monitoring**: Continuously captures audio from the microphone to calculate sound levels.
- **Decibel Calculation**: Calculates **Root Mean Square (RMS)** to determine the decibel levels of the environment.
- **Threshold Alerts**: Alerts the user when noise levels cross predefined safety thresholds (Safe, Moderate, Dangerous).
- **Health & Safety Recommendations**: Provides real-time feedback and advice based on the detected noise levels.
- **Logging and Reporting**: Optional feature to log sound levels over time and generate reports (could be added in future versions).

## Requirements

- Python 3.x
- Libraries: 
    - `numpy`
    - `sounddevice`
    - `queue`

You can install the necessary dependencies using the following command:

```bash
pip install numpy sounddevice

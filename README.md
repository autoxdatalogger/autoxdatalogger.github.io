# Autox Data Logger

Data logger for collecting and analyzing run data for autocross on iOS. Map the course, record your runs, then analyze your performance! Streamlined app flow to quickly analyze data between runs to find time during the event.

## Features

- Map the course, including the cones!
- Record your runs
- Analyze your runs with GPS traces, video, speed vs distance plots, time deltas, and g-force plots
- Automatically start and stop recording for hands free data logging
- Export your data
- Import runs from others

## Overview Video

An overview of the app can be seen in this video on YouTube: <https://youtu.be/1R-xmKB7NuA?si=xT87czbXcRUtSAsg>

## Data Collection

The data collection is based on GPS/GNSS data and is compatible with various devices, including any GPS device which directly pairs to an iPhone.

### Recommended Hardware

- [RaceBox Mini](https://www.racebox.pro/products/racebox-mini)
- [RaceBox Mini S](https://www.racebox.pro/products/racebox-mini-s)
- [RaceBox Micro](https://www.racebox.pro/products/racebox-micro)
- [Opensource DIY GPS module (under $50!)](https://github.com/FlorianMuellerklein/OpensourceGPSDevice4AutoXDatalogger)
- [Opensource DIY GPS + IMU](https://github.com/anchit92/ESP32-RaceBox-mini-Emulator/)

### Internal Phone GPS

The internal phone GPS will only transmit data at a rate of 1Hz. To work around this, the app includes a sensor fusion algorithm to interpolate between the slow 1Hz GPS readings using the phone's IMU data.

## Links

- Community: [Discord](https://discord.gg/AQCWMdjD) · Instagram

---

© 2025

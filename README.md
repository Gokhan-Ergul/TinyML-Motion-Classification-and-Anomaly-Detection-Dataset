# TinyML Motion Classification and Anomaly Detection Dataset

This repository contains a dataset collected using onboard **accelerometer and gyroscope sensors**, designed for TinyML applications such as motion classification and anomaly detection.

## Dataset Description

The dataset includes time-series sensor data from:

- 📈 **Accelerometer (ACC)**: Measures linear acceleration along X, Y, Z axes.
- 🌀 **Gyroscope (GYR)**: Measures angular velocity along X, Y, Z axes.

Data was collected using Nicla Vision and uploaded via the [Edge Impulse](https://www.edgeimpulse.com/) ingestion tools.

### Labelled Classes

The dataset includes the following labeled motion classes:

- `idle`: No movement (resting state)
- `Terrestrial `: Y axis
- `Maritime `: X, Y and Z axis
- 'Lift': Z axis

Each class includes **multiple samples** of fixed window size (10000 ms) collected at a consistent sampling frequency.

### Anomaly Detection

In addition to classification, this dataset can be used to train **unsupervised or semi-supervised models** to detect anomalies based on motion patterns.

## Use Case

This dataset is suitable for:

- Real-time gesture or event detection on microcontrollers
- TinyML-based anomaly detection in industrial or smart home settings
- Experimentation with signal preprocessing and sensor fusion

## How to Use

To explore the dataset and train models:

🔗 [Edge Impulse Project Dashboard](https://studio.edgeimpulse.com/studio/692152)

On Edge Impulse Studio, you can:
- Visualize sensor signals
- Train ML models (e.g., NN classifier, autoencoder)
- Perform real-time testing
- Deploy to edge devices like **Arduino Nicla Sense ME** or **Raspberry Pi**

## License

This dataset is released for educational and research purposes. Contributions and attributions are welcome.

---

📌 Created by [Gökhan Ergül](https://github.com/Gokhan-Ergul)

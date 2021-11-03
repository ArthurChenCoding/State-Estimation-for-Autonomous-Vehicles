# State Estimation and Localization for Self-Driving Cars

State estimation is a vital part of any self-driving car software stack, which relies on the sensor measurements consists of an IMU, a GNSS receiver, and a LiDAR to provide an accurate state estimation. However, since all of sensors provide measurements of varying reliability and at different rates and reference frame, spacial and temporal multisensor calibration is required.

This project applied the Error-State Extended Kalman Filter (ES-EKF) on state estimation pipeline to enhence the accuracy and reliability of the motion model.

![flow chart](flow_chart.png)

## Installation

Install numpy through numpy

```bash
pip install numpy
```

## Compilation & Run


```python
python Main.py
```

# Reference
[State Estimation and Localization for Self-Driving Cars by University of Toronto](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/home/info)\
[Vinohith](https://github.com/Vinohith/Self_Driving_Car_specialization)\
[daniel](https://github.com/daniel-s-ingram/self_driving_cars_specialization)\
[deepanshut041](https://github.com/deepanshut041/self-driving-car-specialization)\
[qiaoxu123](https://github.com/qiaoxu123/Self-Driving-Cars)

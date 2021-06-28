# Simulating Airfoil Self-Noise using Neural Networks

Source - https://archive.ics.uci.edu/ml/datasets/Airfoil+Self-Noise

## Dataset Description
* Built using the results of a series of aerodynamic and acoustic tests on sections of aerodynamic blades performed in an anechoic wind tunnel
* Features - 
  * Number of instances - 1503
  * Number of attributes - 6
  * Dataset characteristics - Multivariate
  * Attribute characteristics - Real
* Attributes - 
  * `Frequency` - Frequency in Hertz(Hz)
  * `AngleAttack` - Angle of Attack in degrees
  * `ChordLength` - Chord Length in meters
  * `FSVelox` - Free stream velocity in metres per second
  * `SSDT` - Suction side displacement thickness in meters
  * `SSP` - Scaled sound pressure level in decibels(target)

## Goal
* Compare Linear Regression model and Neural Network Model for prediction of scaled sound pressure level(SSP)
* Metric of comparison - Mean Squared Error

## Result
| Model | Mean Squared Error|
| ---- | --- |
| Linear Regression (sklearn) | 0.0158 |
| MLPRegressor(sklearn) | 0.00317 |

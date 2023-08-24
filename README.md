# Nightwatch: Non-Invasive Blood Glucose Monitoring System

## Problem Description

### Primary Area of Development: Healthcare Improvement

#### Other Supporting Areas:
- Digital Health and Telemedicine
- Data Analytics and Research
- Home Healthcare
- Pharmacies and Medical Suppliers

### The Problem

Hypoglycemia, or low blood sugar, poses a significant health risk to individuals, particularly those with diabetes. When blood glucose levels drop below a certain threshold, it can lead to various complications, including confusion, dizziness, seizures, and, in severe cases, unconsciousness or even death. This danger is further exacerbated when individuals are asleep, as they may not be aware of the symptoms or able to respond promptly.

Currently, there is a critical need for a reliable and effective alert system that can accurately and timely notify individuals, particularly during sleep, when their blood glucose levels are dangerously low. The objective of the project is to develop a solution that actively monitors blood glucose levels non-invasively and provides real-time alerts, empowering individuals to take immediate action to prevent and manage hypoglycemic episodes, even during sleep, thus minimizing the potentially life-threatening consequences associated with nocturnal hypoglycemia.

## Arriving at Solution

To address this problem, the team decided to focus on non-invasive techniques to measure glucose levels. Existing invasive methods had limitations and were not meeting user expectations. The team hypothesized that by using non-invasive methods, they could provide a satisfactory solution. They explored various non-invasive blood sugar measurement technologies, including Near-infrared Spectroscopy (NIRS), Optical Coherence Tomography (OCT), Electromagnetic Spectroscopy (EMS), Microwave Spectroscopy, and Breath Analysis.

## Proof of Concept

The team chose Near-infrared Spectroscopy (NIRS) technology to measure glucose levels non-invasively. They proposed a device consisting of several key components:

- Power Unit
- Microcontroller (MCU)
- IR Emitting Unit
- IR Receiving Unit
- Temperature and Humidity Sensor
- Haptic Actuator and Buzzer
- LED Indicators

The IR emitting unit provides a broadband source of infrared light that is passed through the skin, and the absorption spectrum is used to calculate blood glucose levels. The IR receiving unit, temperature, and humidity sensor correct for errors caused by environmental factors. The haptic actuator and buzzer warn users of glucose level deviations, while LED indicators indicate different device conditions.

## Proposed Design Concept

The proposed device incorporates a calibration process for accurate glucose level measurement. The calibration process includes steps like data acquisition, preprocessing, model selection, model modification, model evaluation, iterative refinement, independent validation, and post-market monitoring.

## Calibration Process

1. Data Acquisition: Gather a dataset of NIR spectral data along with corresponding blood glucose levels from many individuals.
2. Preprocessing: Clean and preprocess the NIR spectral data to ensure high-quality data.
3. Model Selection: Evaluate existing calibration models for non-invasive blood glucose monitoring and select the most appropriate one.
4. Model Modification: Modify the selected model to suit the device and dataset.
5. Model Evaluation: Assess the performance of the modified model through validation.
6. Iterative Refinement: Refine the model for improved accuracy.
7. Independent Validation: Validate the final modified model using an independent dataset.
8. Post-Market Monitoring: Continuously monitor the device's performance and accuracy.

## Sustainability

The project aligns with several Sustainable Development Goals (SDGs):

- SDG 3: Good Health and Well-being
- SDG 9: Industry, Innovation, and Infrastructure
- SDG 11: Sustainable Cities and Communities
- SDG 12: Responsible Consumption and Production
- SDG 17: Partnerships for the Goals

The device contributes to reducing premature mortality from non-communicable diseases and promotes mental health and well-being. It represents innovation in healthcare technology and enhances the quality of life for individuals with diabetes.

## Social and Environmental Impact

The device's development can lead to significant positive impacts:

- Improved Safety and Well-being
- Enhanced Quality of Life
- Empowerment and Independence
- Reduced Healthcare Costs
- Potential Environmental Benefits

It can save lives, alleviate burdens, and contribute to more sustainable healthcare practices by reducing emergency interventions and resource utilization.

## Conclusion

The Nightwatch team aims to develop a non-invasive blood glucose monitoring system to address the critical issue of hypoglycemia in individuals with diabetes. By using Near-infrared Spectroscopy (NIRS) technology, the team's proposed solution offers real-time alerts, empowerment, and improved quality of life. With a strong focus on sustainability and social impact, the team strives to contribute to the well-being of individuals, communities, and the environment.

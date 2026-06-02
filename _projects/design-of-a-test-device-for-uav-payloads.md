---
layout: page
title: 'Design of a test device for UAV payloads'
---

### Master of Science in Engineering Thesis

# Confidentiality Notice
This project was conducted in collaboration with Quadsat. The full thesis and certain technical details are covered by a Non-Disclosure Agreement (NDA) and therefore cannot be published.

## Abstract

Drones have become versatile tools, utilized for a wide range of applications. Most of the time they carry payloads full of technology. This project aimed to design a test device capable of simulating drone movements and oscillations in order to verify and optimize UAV payload performance, particularly for payloads with gimbal stabilization systems. This project was conducted in collaboration with Quadsat, a company that provides systems for in-flight testing and verification of RF equipment. The developed test device will serve not only as a final verification tool before flight missions, but also as a platform for testing new features.

The device was constructed using aluminum profiles and metal sheets to provide stability while reducing mass. Each axis of movement (roll, pitch, yaw) is controlled by BLDC motors, enabling high precision and full control of payload orientation. A vibration table was added to simulate oscillations experienced in-flight, with adjustable frequency to challenge payloads under different conditions. The control system supports both automated and manual operation, including remote access and a graphical user interface (GUI). Sensors were integrated to provide the necessary data for payload verification.

The system was set up and tested with specially selected Quadsat payloads, running demo configurations with known issues that required diagnosis. Manual tests were conducted first, followed by automated verification. In-flight conditions were effectively replicated, though this functionality still requires improvement. Although the roll axis was not commissioned, payloads were tested in a variety of scenarios that enabled detection of problems and prevention of future mission complications.

In conclusion, the developed test device successfully met the majority of the project’s objectives, providing a reliable and efficient tool for UAV payload verification. It enabled testing of payload stability, robustness, and pointing accuracy. However, several areas still require improvement. Automatic tuning and more advanced vibration control need to be implemented, along with greater control over drone log-following functionality. Future work should also focus on roll axis commissioning, hardware upgrades, resolving filtering issues, and automating analysis processes.

## Project Information

**SDU Supervisor:** Kjeld Jensen  
**SDU Co-Supervisor:** Jes Hundevadt Jepsen  
**Quadsat Supervisor:** Rasmus Hasle

**Industry Partner:** Quadsat  
**Institution:** University of Southern Denmark  
**Credits:** 40 ECTS  
**Duration:** September 2024 – August 2025

## Acknowledgements

Special thanks to the Quadsat Robotics Team for their invaluable support during the execution of this project.

## Videos

<iframe
  width="100%"
  height="500"
  src="https://www.youtube.com/embed/Qrd6zBH0NXo"
  title="Flight example"
  frameborder="0"
  allowfullscreen>
</iframe>

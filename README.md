# Smart City IoT System (using Cisco Packet Tracer)
## Demo Video
[Watch Demo](https://drive.google.com/file/d/1bLcNCVNMWDgK5Br0ygPMhl6_vebthOJO/view?usp=drive_link)
(https://drive.google.com/file/d/1bLcNCVNMWDgK5Br0ygPMhl6_vebthOJO/view?usp=drive_link)

## Cisco Packet Tracer File
[Download .pkt file](https://drive.google.com/file/d/1rG0yVG0ylhvlgQgSxejhYTIW0u06NIDL/view?usp=drive_link)
(https://drive.google.com/file/d/1rG0yVG0ylhvlgQgSxejhYTIW0u06NIDL/view?usp=drive_link)

## Aim
The aim of this project is to design and simulate a Smart City IoT System 
using Cisco Packet Tracer that demonstrates how Internet of Things (IoT) 
devices can automate essential city services. The project integrates 
intelligent lighting, surveillance, and environmental monitoring into a 
single IoT network connected through a Home Gateway.

The system is designed to improve public safety, enhance energy efficiency, 
and continuously monitor environmental conditions without requiring manual 
intervention.

## Problem Statement
Modern cities face several challenges related to public safety, energy 
consumption, and environmental pollution. Conventional street lighting 
systems often remain switched on even during daylight, leading to unnecessary 
power consumption. Monitoring public spaces also requires continuous human 
supervision, while environmental hazards such as smoke, carbon monoxide (CO), 
and carbon dioxide (CO₂) leaks can threaten public health.

This project addresses these challenges by implementing a Smart City IoT 
System that automates lighting, enhances surveillance through motion detection, 
and continuously monitors environmental conditions.

## Scope of the Solution
The solution implements three core smart city modules:

- **Smart Lighting** — Automatically controls lighting based on motion, improving safety while reducing energy consumption.
- **Smart Surveillance** — Combines a motion detector, smart light, webcam, and siren to detect activity and generate alerts.
- **Environmental Monitoring** — Continuously observes smoke, carbon monoxide, and carbon dioxide levels to support early hazard detection.

## Architecture of the Solution
Sensors → Home Gateway → Actuators → PC Monitor

All IoT devices are wirelessly connected to a Home Gateway, which acts as 
the central controller. The PC monitors and configures the entire system. 
Three independent modules operate in parallel over the same wireless network.

## Simulated Circuit
![Simulated Circuit](Screenshots/simulated_circuit.png)
## Required Components

**Software:**
- Cisco Packet Tracer
- GitHub

**Hardware (Simulated):**

| Component | Quantity | Purpose |
|---|---|---|
| PC | 1 | Monitoring and configuration |
| Home Gateway | 1 | Central IoT controller |
| Street Lamp | 1 | Public lighting |
| Smart Lights | 2 | Automated lighting |
| Motion Detectors | 2 | Motion sensing |
| Webcam (CCTV) | 1 | Surveillance |
| Siren | 1 | Alert generation |
| Smoke Detector | 1 | Fire detection |
| Carbon Monoxide Detector | 1 | CO monitoring |
| Carbon Dioxide Detector | 1 | CO₂ monitoring |
| Old Car | 1 | Simulated pollution source |



## Screenshots

### PC Wireless Config
![PC Wireless Config](Screenshots/pc_wireless_config.png)

### IoT Monitor
![IoT Monitor](Screenshots/iot_monitor.png)

### Environment Settings
![Environment Settings 1](Screenshots/environment_settings_1.png)
![Environment Settings 2](Screenshots/environment_settings_2.png)
![Environment Settings 3](Screenshots/environment_settings_3.png)

### IoT Devices Config
![IoT Devices Config 1](Screenshots/iot_devices_config_1.png)
![IoT Devices Config 2](Screenshots/iot_devices_config_2.png)
![IoT Devices Config 3](Screenshots/iot_devices_config_3.png)
![IoT Devices Config 4](Screenshots/iot_devices_config_4.png)
![IoT Devices Config 5](Screenshots/iot_devices_config_5.png)
![IoT Devices Config 6](Screenshots/iot_devices_config_6.png)
![IoT Devices Config 7](Screenshots/iot_devices_config_7.png)
![IoT Devices Config 8](Screenshots/iot_devices_config_8.png)

### Conditions
![Conditions 1](Screenshots/conditions_1.png)
![Conditions 2](Screenshots/conditions_2.png)
![Conditions 3](Screenshots/conditions_3.png)
![Conditions 4](Screenshots/conditions_4.png)
![Conditions 5](Screenshots/conditions_5.png)

### Demo
![Smart Lighting](Screenshots/demo_smart_lighting.png)
![Smart Surveillance](Screenshots/demo_smart_surveillance.png)
![Environmental Monitoring](Screenshots/demo_environmental_monitoring.png)





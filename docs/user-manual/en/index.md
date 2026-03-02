# Chiuchau Smart Fan Monitoring System — User Manual

## Cover


![](../../assets/images/ce13f776-26b4-4cf6-8a77-1d9748c98e4e.jpg)

### **Table of Contents**

1. Introduction - P. 02
1. Safety Instructions - P. 03
1. Product Overview - P. 04
1. Installation Guide - P. 06
1. Hardware Setup & Startup - P. 14
1. Software Operation Guide - P. 16
1. Software Troubleshooting - P. 27
1. Technical Support & Contact Information - P. 28
1. Appendix - P. 29

### 1. Introduction

Welcome to the **Chiuchau Smart Monitoring System**. This system is designed for real-time monitoring and predictive maintenance of industrial equipment, combining the latest sensing technologies with artificial intelligence analytics to provide users with a comprehensive and precise equipment health management solution. Our system supports applications across various industrial environments — from semiconductor manufacturing to traditional industries — effectively improving equipment uptime, reducing maintenance costs, preventing unexpected failures, and enabling seamless smart production management.

The system comprises two major parts: **hardware devices** and a **software platform**. On the hardware side, we provide high-precision tri-axial vibration sensors, temperature sensing modules, and power monitoring equipment, with multiple communication technologies including Wi-Fi, LoRa, and 4G LTE to ensure stable data transmission to cloud or local servers. The built-in UPS power protection module safeguards data during unexpected power outages and ensures continuous operation.

On the software side, the system supports real-time data visualization, anomaly alerts (based on **ISO 20816 vibration standards**), and AI-powered equipment health prediction models to help users accurately track equipment status. Through intelligent algorithms, the system can predict potential failures in advance and provide maintenance recommendations. Additionally, users can configure **LINE group notifications** and **email alerts** to receive immediate warnings when anomalies occur.

The system also supports a **carbon emission monitoring module** that tracks equipment energy consumption and carbon emission data, helping enterprises achieve energy-saving and carbon reduction goals in compliance with environmental regulations. All data is automatically compiled into monthly diagnostic reports that clearly present equipment operation trends and health assessments for more informed decision-making.

The **Chiuchau Smart Monitoring System** is committed to providing efficient, reliable, and flexible solutions. Whether facing demanding semiconductor cleanroom environments or standard industrial settings, we can meet your needs. Through our system, you can effectively enhance equipment reliability, reduce maintenance costs, and significantly improve production efficiency.

## 2. **Safety Instructions**

To ensure safe and effective operation of the Chiuchau Smart Monitoring System, please carefully read the following safety instructions. This system involves high-voltage electrical equipment and data transmission. Please follow all operational standards to prevent accidents or equipment damage.

---

#### 2.1 Power Supply & Installation Safety

- **Independent Power Supply**: Ensure the monitoring module uses an independent 110V/220V power source that complies with local electrical safety standards.
- **High-Voltage Wiring Warning**: High-voltage power connections to motors (380V/440V) must be performed by certified electricians. Wiring or maintenance while energized is strictly prohibited.
- **Grounding Requirements**: All equipment must be properly grounded to prevent static interference and electrical shock risks.
- **UPS Power Protection**: The system includes a built-in UPS module that automatically protects data during sudden power failures. Do not disassemble or modify the UPS module.

---

### 2.2 Equipment Operation Safety

- **Waterproof & Dustproof Requirements**: This system features IP65/IP67 protection ratings. Ensure protective seals are not damaged during installation to prevent moisture or dust from entering the equipment.
- **Explosion-Proof Restrictions**: If installation in explosion-proof areas is required, confirm that equipment meets IEC explosion-proof certification standards and strictly follow relevant installation regulations.
- **Sensor Installation**: When installing vibration sensors and current transformers (CT), confirm that all power has been disconnected and avoid exposing sensors to high temperatures or corrosive substances.

---

### 2.3 Communication & Data Security

- **Network Security Settings**: Ensure Wi-Fi, LoRa, or 4G LTE connections have encryption protocols enabled (e.g., WPA2) to prevent unauthorized data access.
- **Data Protection**: All monitoring data is encrypted and stored on cloud or local servers. Do not use unauthorized third-party software to access data.
- **Firmware Updates**: Regularly check and update system firmware to ensure security and stability. Download update files only from official sources.

---

### 2.4 Maintenance & Inspection Notes

- **Power-Off Maintenance**: Before performing any maintenance or inspection, always turn off the power and ensure the system is completely de-energized.
- **No Unauthorized Modifications**: Do not modify hardware or software without authorization, as this may cause system failures or safety hazards and may void the warranty.
- **Regular Inspections**: Periodically inspect sensors and data cables to ensure stable equipment operation.

---

### 2.5 Emergency Procedures

- **Equipment Anomalies**: If the system detects anomalies (such as excessive temperature, abnormal vibration, or current irregularities), alerts will be automatically sent to designated LINE groups or email addresses. Immediately follow system recommendations for inspection or shutdown.
- **Fire or Electrical Shock Risk**: If equipment is smoking, overheating, or emitting a burning odor, immediately cut power and evacuate the area. Do not attempt repairs — contact professional maintenance personnel.

---

### 2.6 Additional Notes

- **Training Requirements**: Only professionally trained operators should use this system to avoid safety risks from unauthorized operation.
- **Environmental Disposal**: Decommissioned or replaced equipment should be recycled in accordance with local environmental regulations.

---

Please strictly follow these safety instructions to ensure operational safety and stable equipment performance. For questions, contact Chiuchau Enterprise customer service or technical support.

## 3. Product Overview

### 3.1 System Architecture

![](../../assets/images/2d4ab7dd-334a-4ff4-9b70-751986f140d4.png)


### 3.2 Main Components of the Monitoring Module

- Component function descriptions
- 3.3 Product Specifications

## 4. Installation Guide

### 4.1 Hardware Installation

- **Power Wiring Instructions**

4.2 Sensor Installation (Position Selection & Mounting Methods)

![](../../assets/images/1c15d3ca-264c-40ef-ab27-a2a363893dd2.png)


#### 4.2.1 Installation Position Guide

The system comes standard with two high-precision tri-axial accelerometers for monitoring fan vibration conditions, installed at the following positions based on component characteristics:

1. **Motor-Side Sensor:**
1. **Fan-Wheel-Side Sensor:**

#### 4.2.2 Installation Orientation Reference (VAH Positioning)

Sensor installation must follow **VAH (Vertical V, Axial A, Horizontal H) positioning** for precise placement to ensure data accuracy and comparability.

- **V-Axis (Vertical):** Points in the vertical direction of the equipment for detecting up-down vibrations.
- **A-Axis (Axial):** Parallel to the motor shaft for monitoring axial vibrations, particularly shaft alignment conditions.
- **H-Axis (Horizontal/Transverse):** Parallel to the equipment's horizontal plane, perpendicular to the A-axis, for detecting lateral vibration anomalies.

#### 4.2.3 Mounting Methods

To ensure data accuracy and long-term stable operation, sensors must be mounted using professional methods, avoiding looseness or position shifts that could affect monitoring results.

1. **Screw Mounting (Recommended):**
1. **Strong Adhesive Mounting (Temporary monitoring):**
1. **Magnetic Base (Removable installation):**

#### 4.2.4 Installation Precautions

- Ensure equipment surfaces are clean and oil-free before installation to prevent unstable sensor mounting or data distortion.
- Avoid installing sensors on weld seams or uneven surfaces to ensure data accuracy.
- Sensor cables should not be routed parallel to high-voltage cables to minimize electromagnetic interference.
- Perform calibration tests after installation to confirm normal and stable sensor output.

---

### 4.3 Network & Communication Setup

![](../../assets/images/c105216e-8645-4302-a4bb-440832a2ab64.webp)


- 4.3.1 Basic Network Requirements
- **Hardware Configuration:**
- **Service Description:**
- **Advantages:**

#### 4.3.2 Communication Protocols & Technical Standards

- **Communication Protocols:**
- **Wireless Communication Technologies:**
- **Regulatory Certifications:**

#### 4.3.3 Installation & Setup Steps

- **Network Environment Testing:**
- **Device Connection Setup:**
- **Network Monitoring & Maintenance:**

---

This guide provides complete network and communication setup instructions to ensure stable monitoring system operation across different network environments.

### 4.4 Optional Accessory Installation

#### 4.4.1 Tri-Color Status Light

![](../../assets/images/791bc0cd-3312-47e1-b05f-05213e7cfa86.png)


The tri-color status light (red, yellow, green) provides real-time equipment operation status display, helping on-site personnel quickly assess equipment health and anomaly alerts. Proper installation positioning ensures clear light visibility for improved operational efficiency and safety.

- **Installation Position Recommendations**
- **Installation Steps**
- **Use & Maintenance**

#### 4.4.2 4G LTE Router + Network Card

Please refer to the "Network & Communication Setup" section.

#### 4.4.3 Touch Display

![](../../assets/images/d2c1961b-4ee3-429a-8b15-13d2109fe8e8.png)


The touch display provides an intuitive operation interface for on-site personnel to view real-time equipment data, alert status, and historical records, as well as perform basic system settings and controls.

- **Installation Instructions**
- **Operation Instructions**
- **Maintenance & Precautions**

#### 4.4.4 High-Precision RJ45 CT Input Power Meter

![](../../assets/images/aebc6493-3fb1-4ef3-a6f3-40226d6d0ff8.png)


- **Installation Instructions**
- **Precautions**

## Hardware Setup & Startup

### 5.1 System Startup Procedure

![](../../assets/images/7fdb32a2-1a09-4e4e-b716-fd95ca9eec17.png)


After 110V/220V power installation is complete, flip the switch upward to power on.

- To shut down, simply flip the switch downward to cut power. The internal system will automatically execute the shutdown procedure — wait approximately 10–15 seconds. After the relay indicator below turns off once, you may proceed with the next restart.

### 5.2 Initial Installation Hardware Inspection

- After powering on, check that the power supply indicator light is green (DC OK).
- Verify the router shows a steady green light.
- Confirm signal reception is functioning normally (red and green lights illuminated).

### 5.3 Hardware Troubleshooting Guide

- If the power supply indicator does not light up after powering on, the fuse may be blown. Replace the fuse (2A/250V fast-blow fuse, size 6.35×32mm).
- If the tri-color light does not display in sequence from green → orange → red, restart the system (refer to "System Startup Procedure" step 3).
- If the system cannot shut down or restart normally, turn off the monitoring system control board and then turn it back on.

---

## 6. Software Operation Guide

### 6.1 Core Features & Advantages

![](../../assets/images/4d0fb650-2430-434e-a013-7046745ba3ad.png)
![](../../assets/images/5a9b1f04-a26d-4f91-9066-a40f0f565f85.png)
![](../../assets/images/30833126-8869-4070-89e9-035752f210e9.png)
![](../../assets/images/0eb522a6-c930-4e9e-ad3c-f35e90bc6fe5.png)
![](../../assets/images/72067d30-10aa-42ba-9521-262770985859.png)


- Real-Time Monitoring & Analysis: Provides real-time equipment operational data monitoring including vibration, temperature, and other key parameters, with trend charts and FFT spectrum analysis support.
- **AI Smart Prediction**: Combines AI prediction models to anticipate potential equipment anomalies and failures, reducing maintenance costs and improving operational efficiency.
- Multi-Platform Support: Enables users to remotely view equipment status via various devices (smartphones, tablets, computers).
- Carbon Emission Tracking: Immediate alert notifications during equipment anomalies, plus carbon emission tracking functionality.

### 6.2 Equipment Diagram

![](../../assets/images/71922abb-a453-4eaf-acc8-0e39f327f67c.png)


Provides real-time visual equipment status display for quick access to key operational information for each device.

### **6.3 Monitoring Data**

![](../../assets/images/8e9b8727-f178-45fc-87cf-b613d8a4fe08.png)


Presents raw data in tabular format including temperature, vibration, current, and other detailed metrics for further analysis.

### **6.4 Trend Charts**

![](../../assets/images/98a5b725-a1eb-41c6-b446-11bcf8b2d016.png)
![](../../assets/images/3f8bce38-1865-4fb4-a7a1-fd492039d7f0.png)


Displays equipment operational data trends over time to help users assess long-term equipment performance.

### **6.5 Carbon Emission Monitoring**

![](../../assets/images/6f6648db-7e18-4396-9d8e-9bcc55291b0e.png)


Real-time monitoring of equipment carbon emission data to help enterprises achieve energy-saving and carbon reduction targets.

---

### 6.6 Data Analysis Features

- Anomaly Interpretation & Health Scoring

---

### 6.7 Notification & Alert Settings

- LINE Group Notification Setup
- Persistent Alert Notifications
- Alert Management
- Alert Notification Criteria

---

### 6.8 Monthly Report Generation

#### Automatic Monthly Report Generation

The system automatically generates complete equipment operation reports recording vibration, temperature, current, voltage, and other key parameter data.

#### Anomaly Event Tracking

Detailed records of each anomaly event including trigger time, system response, and maintenance recommendations.

#### Carbon Emission & Equipment Health Monitoring

Tracks carbon emission data and monitors equipment health values with future trend prediction analysis.

#### Earthquake Alert Integration

Real-time integration of earthquake alert information for rapid assessment and exclusion of potential earthquake-induced equipment damage.

- **Automatic Report Generation Settings**
- **Report Format & Output (PDF)**
- **Report Content Interpretation Guide**

![](../../assets/images/4496ce7c-590f-44d8-a342-1b1d56d6df2e.png)

![](../../assets/images/f59a85db-2c2f-4de7-845c-64019ac366e6.png)

![](../../assets/images/798a32cf-ed46-4920-a93d-e304045f9d01.png)

![](../../assets/images/140ff412-f2f7-48db-b704-884528790762.png)

![](../../assets/images/2a0d6fe9-d2cb-4212-9f99-161b90476201.png)


---

## 7. Software Troubleshooting

#### 7.1 Unable to Log In

**Possible Causes & Solutions**

- **Network Connection Issues**
- **Incorrect Username or Password**
- **System Maintenance or Server Issues**

---

#### 7.2 Data Update Delays or Anomalies

**Possible Causes & Solutions**

- **Server Operation Issues**

---
layout: page
title:  SmartTrashBin
description:
img: assets/img/SmartTrashBin.png
importance: 5
category: work
related_publications: false
---

As part of the EE 542 course at the University of Washington, our team of 4 developed the Smart Trash Bin to optimize waste management. This advanced system integrates sensors and a microcontroller to accurately assess garbage bin capacity, providing real-time data to improve collection scheduling and reduce costs.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SmartTrashBin.png" title="Smart Trash Bin prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Smart Trash Bin prototype
</div>

**Key Features:**

**Real-Time Monitoring:** Utilizes ultrasonic and optical time-of-flight (TOF) sensors to monitor bin fill levels with 10% accuracy, preventing overflows and optimizing collection routes.

**Low Power Consumption:** Employs an ultra-low power sleep mode, activating every 12 hours to transmit data, ensuring long battery life with a 3000 mAh LiPo battery.

**Particle Boron Microcontroller:** Central to the system is the Particle Boron microcontroller, chosen for its seamless cellular connectivity and compatibility with the sensors. It efficiently manages data transmission to the cloud.

**Cloud Integration:** Data is transmitted via cellular connection to the cloud, where it is analyzed and visualized for efficient waste management.

**NFC Technology:**  Facilitates easy data retrieval and system wake-up, enhancing the ease of use for waste management personnel.

**Durable Design:** The system is housed in a 3D-printed box designed to withstand harsh environmental conditions, ensuring long-term reliability.

**Resources:**
- **Code:** [GitHub](https://github.com/deekshaprabhu7/EE542-SmartTrashBin)
- **Report:** [Smart Trash Bin Report](/assets/pdf/SmartTrashBin.pdf)

This project demonstrates the practical application of IoT in waste management, providing a robust and efficient solution to optimize waste collection and reduce costs.


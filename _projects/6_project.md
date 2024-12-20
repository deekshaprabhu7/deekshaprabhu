---
layout: page
title:  Micropantry
description:
img: assets/img/Micropantry.jpg
importance: 6
category: work
related_publications: false
---

The Micropantry is a decentralized smart pantry system that leverages IoT technology to enhance food safety and ensure timely restocking in community pantries. Powered by an ESP32S3 microcontroller and environmental sensors, it provides real-time data on temperature, humidity, and inventory levels, enabling low-power, data-driven solutions to address food security challenges.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Micropantry.jpg" title="Micropantry prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Micropantry prototype
</div>

**Key Features:**

**Real-Time Monitoring:** Utilizes reed switches, BME688 sensors, load cells, and capacitive touch sensors to track door usage, measure weight, and monitor environmental conditions with high accuracy.

**Low Power Consumption:** Designed with an ultra-low-power mode, the system uses a 3.7V 2500mAh LiPo battery and solar charging to ensure long-term, sustainable operation.

**Seeedstudio XIAO:** The system leverages the XIAO ESP32S3 microcontroller for seamless data acquisition, processing, and wireless transmission.

**Data Analytics and Cloud Integration:** Collected data is sent to the Adafruit IO cloud for analysis and visualization, enabling efficient inventory management and insights into usage patterns.

**Durable and Modular Design:** Features a robust enclosure made with 3D-printed components and easily configurable sensor modules to adapt to various pantry designs and use cases.

**Scalable System:** Built to scale for deployment across multiple community pantries, ensuring widespread impact.

**Resources:**
- **Code:** [GitHub](https://github.com/deekshaprabhu7/Micropantry)
- **Dashboard:** [Adafruit IO](https://io.adafruit.com/deeksha795/dashboards/micropantry)

This project highlights the potential of IoT and smart sensing in community health and resource management, offering a scalable and sustainable solution to optimize pantry usage and reduce waste.

---
layout: page
title: Soluna
description: Senior Capstone Project
img: assets/img/1.jpg
importance: 1
category: fun
---

Researchers have found that our internal clock, or circadian rhythm, naturally regulates sleep and wake times, but modern life often disrupts these cues with electronic devices, busy schedules, blue light, and noise1. An alarm clock can help reestablish or adjust our internal clocks, ensuring we wake up on time and feel less groggy in the morning. Moreover, having a separate device for an alarm clock limits phone use before bed and first thing in the morning, offering protection from additional disruptions to our sleep cycle. Unfortunately, current alarm clocks on the market either use jarring wakeup methods or focus solely on aesthetics, often failing to get users out of bed.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Our project, “Soluna,” is a smart alarm clock designed to address all the common issues associated with traditional alarms. Composed of two devices (referred to as the alarm clock and docking station), our system gradually wakes users up with increasing light and a soothing sound from the alarm clock, gently easing them out of sleep and reducing cortisol-triggered stress. To ensure they fully awaken, Soluna requires users to get out of bed to turn off the alarm by placing a magnetic character on the docking station across the room in place of a snooze button. This innovative approach helps prevent sleep anxiety and additional cortisol triggers from repeated alarms. When the user is ready to sleep, they will place the magnetic character back on the alarm clock, which starts the system’s night mode. At this point, brown noise will begin to play with soft light that gradually decreases until both features turn off after 15 minutes, which is the time it typically takes people to fall asleep. Soluna uses red-light therapy for the LED lights to boost melatonin production, promoting better sleep. Finally, a wireless charger placed in the lockbox of the docking station allows users to prepare for the next day while limiting screen time before and after sleep.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

To facilitate wireless communication between the alarm clock and docking station we programmed two ESP32-S3 microcontrollers to use Wi-Fi/HTTP to routinely send updates to check when to initiate morning and nighttime mode features according to the alarm time set by the user. The ESP32-S3’s ability to handle multiple input and output tasks simultaneously makes it ideal for managing the various subassemblies on both main assemblies. The completion of this project totaled roughly $484.06, staying well within our allotted budget of $700. We were able to stick to the originally proposed schedule up until the final week, in which we had to overcome challenges regarding the PCBs and 3D-printing availability. With Soluna, our team hopes to help users enjoy a more relaxed and energized start to their day, free from the pitfalls of traditional alarm clocks.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

Here is a demo of our project:
<iframe src="https://drive.google.com/file/d/12TOcmPRRdOB98h9GDSzLtB5e6Etb27-I/preview" width="640" height="480" allow="autoplay"></iframe>

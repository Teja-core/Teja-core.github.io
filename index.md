---
layout: single
title: About Me
permalink: /about/
author_profile: true
---

# Embedded Firmware Engineer 🚀

Hi, I'm **Teja Vayila**, an Embedded Firmware Engineer specializing in STM32-based systems, bare-metal programming, and real-time embedded solutions.

I build reliable firmware for smart and automotive products with strong focus on performance and low-level debugging.

---

## 🔧 Core Expertise

- Embedded C / C++ Firmware Development  
- Bare-metal & RTOS-based System Design  
- STM32 & ARM Cortex-M Microcontrollers  
- Peripheral Drivers: UART, I2C, SPI, CAN  
- Real-time Debugging & Hardware Bring-up  
- Automotive & Smart Product Firmware  

---

## ⚙️ What I Do

- Design and develop efficient firmware architectures  
- Implement low-level drivers and communication stacks  
- Debug complex hardware-software integration issues  
- Optimize real-time system behavior  
- Collaborate with cross-functional hardware & product teams  

---

## 📁 Quick Access

- 👉 View my Projects: `/projects/`  
- 👉 Read my Blog: `/blog/`  
- 👉 Know more About Me: `/about/`  
- 👉 Download Resume: `/resume/`

---

## 📝 Latest Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) – {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

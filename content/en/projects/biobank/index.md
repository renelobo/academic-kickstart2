---
title: Biobank
summary: Remote monitoring system for biobanks for research purposes
date: 2016-04-27
tags:
  - Hardware
  - IoT
---

A biobank is a repository that stores and manages biological samples (biospecimens) for research. Correct handling, organisation and storage are essential to its purpose, and storage conditions such as humidity and temperature are critical: if these parameters fluctuate without an adequate control plan, biological material of high scientific value is put at risk.

We built a low-cost remote monitoring system for the UNAB biobank using open-source hardware and software. It monitors temperature, humidity, door opening, alarms and power failures using environmental sensors, a custom-built microcontroller and a Raspberry Pi, plus a web interface that helps the biobank staff follow the storage conditions.

<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:1rem;align-items:start">
  <img src="biobank-hardware.jpg" alt="Monitoring hardware: CPU, power system and sensors" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
  <img src="biobank-interface-1.jpg" alt="Biobank monitoring web interface" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
  <img src="biobank-interface-2.jpg" alt="Temperature history in the web interface" loading="lazy" style="width:100%;height:auto;border-radius:8px;margin:0">
</div>

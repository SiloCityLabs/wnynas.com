---
title: "Custom Docker Server with LochNAS: High-Speed Storage Meets Scalability"
description: Discover how we crafted a Linux-based Docker server with LochNAS, featuring blazing-fast SSD storage for development and massive RAID storage for media.
date: 2021-05-10
tags: ["Server Upgrade", "Docker", "Custom Build"]
draft: false
author: Luis Rodriguez
---

When it comes to combining **speed, scalability, and flexibility**, every detail matters. This customer wanted a server tailored to two distinct needs: **massive storage for media** and **blazing-fast performance for development and document handling**. Their existing setup just couldn’t keep up. Enter our custom-built **Linux Docker server** with a unique LochNAS implementation.

<!--more-->

With **64GB of RAM**, an **AMD 5600GE processor**, and **16 SATA ports running at full PCIe x16 speeds**, this server balances raw performance with practical design. Storage? It’s a dual-purpose beast. The **8x4TB RAID-Z1 array** delivers ample space for media, while the **8x300GB Intel SSDs** handle high-speed workloads with ease.

This isn’t just another build; it’s a carefully optimized system designed to grow with the customer’s needs while minimizing long-term costs and headaches. Let’s break it down.

---

## **Server Specs and Highlights**

### Hardware Specifications  
![Server Build - Front View](placeholder-for-image-front-view.jpg)  
* **CPU:** AMD 5600GE  
* **RAM:** 64GB DDR4  
* **Storage:**  
  - 8x4TB drives in RAID-Z1 for media storage  
  - 8x300GB Intel SSDs in RAID-Z1 for high-speed development and documents  
  - 1x512GB SATA SSD for system and caching  
* **HBA:** 16-port SATA HBA running at PCIe x16 speeds  
* **Power Supply:** 850W 80 Plus Platinum  
* **Chassis:** 4U Rosewill rackmount, expandable up to 15 drives  

### Key Features  
![Interior Components Layout](placeholder-for-image-interior-layout.jpg)  
1. **Dual-Purpose Storage**: Optimized RAID configurations for both massive media storage and high-speed development needs.  
2. **Docker-Friendly**: Built with Linux and a custom LochNAS setup for seamless containerized environments.  
3. **Efficient Performance**: Low-power 5600GE CPU and smart RAID configurations ensure long-term efficiency.  
4. **Cost-Effective Upgrades**: The 4TB drives strike the perfect balance between price and capacity, making future replacements affordable.  

---

## **The Build Process**

### 1. **Optimizing Storage for Two Workloads**  
The heart of this build lies in its dual-purpose storage design:  

- The **8x4TB RAID-Z1** array provides a robust and scalable media storage solution, ensuring redundancy without overcomplicating replacements.  
- The **8x300GB Intel SSD RAID-Z1** offers lightning-fast performance for Docker containers, document storage, and development environments.  

> **Pro Tip:** Pairing RAID-Z1 with high-speed SSDs provides the perfect blend of redundancy and rapid read/write speeds for intensive workloads.  

![Storage Configuration](placeholder-for-image-storage-configuration.jpg)  

### 2. **Harnessing Full PCIe x16 Speeds**  
To ensure no bottlenecks, we equipped the system with a **16-port SATA HBA**, fully utilizing the PCIe x16 bandwidth. This guarantees the drives can operate at their full potential, even during heavy workloads.  

### 3. **Customizing for Docker and LochNAS**  
The server runs a tailored **Linux Docker environment** with a custom **LochNAS** implementation. This allows the customer to:  
- Easily deploy and manage containerized applications.  
- Use LochNAS for smart file organization and streamlined access to development resources.  

### 4. **Energy Efficiency and Expandability**  
With a **low-power 5600GE CPU**, **80 Plus Platinum PSU**, and **4U chassis expandable up to 15 drives**, this build is not only efficient but ready to scale as needs grow.  

---

## **Performance Metrics**  
After deployment, we ran extensive tests to ensure the server met its demanding workload.  

| **Metric**        | **Media Array (8x4TB RAID-Z1)** | **SSD Array (8x300GB RAID-Z1)** |  
|-------------------|---------------------------------|--------------------------------|  
| Sequential Write  | XXX MB/s                        | XXXX MB/s                       |  
| Sequential Read   | XXX MB/s                        | XXXX MB/s                       |  
| Power Usage       | ~60W idle, ~140W under load     | ~65W under SSD-heavy load      |  

![Performance Testing](placeholder-for-image-performance-testing.jpg)  

---

## **Conclusion**  

This build proves that you don’t need to compromise between speed and capacity. By combining **smart RAID configurations**, a **future-proof HBA**, and a **custom LochNAS environment**, we delivered a server that excels at both storing large media libraries and supporting fast-paced development work.  

If you’re looking to build a server that can handle it all—media, development, and beyond—this project is proof that the right design can make all the difference.  

[Contact Us for Your Custom Build](/contact)  

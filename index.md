---
title: Introduction
layout: home
nav_order: 1
---

# TechExcel: Defender for Identity (level 300 / CSU) lab

**The estimated time to complete this lab is 210 minutes.**

Humongous’ IT department needs to protect the company's Active Directory environment. They need to leverage signals from Active Directory to help better identify, detect, and investigate advanced threats directed at their organization. The IT department has identified the following requirements:

- Prevent breaches, using proactive identity security posture assessments
- Detect threats, using real-time analytics and data intelligence
- Investigate suspicious activities, using clear, actionable incident information
- Respond to attacks, using automatic response to compromised identities

Brian Stitt, the Vice President of Information Security and Compliance, has engaged with Microsoft and his team to implement MDI in his enterprise. The team has provided you with the information listed throughout the rest of this section and would like assistance in deploying MDI, and then using the product to perform threat detection and investigation.​

This lab provides information and practice for deploying Microsoft Defender for Identity (MDI) and using MDI to detect and investigate attacks.

During the first day of this lab, you'll install and configure the Microsoft Defender for Identity sensor. Then, on the second day, you'll execute, detect, and investigate attacks. 

## Exercises

**To successfully complete this lab, you'll need to complete the following tasks:**
- Verify connectivity to the Defender for Identity service.
- Download the Defender for Identity sensor.
- Install the Defender for Identity sensor, from command line and using script. 
- Configure the Defender for Identity sensor to start receiving data (post-deployment configuration, including audit policies for Windows.
- Validate the installation.
- Execute, detect, and investigate Reconnaissance and discovery attacks.
- Execute, detect, and investigate Persistence and privilege escalation attacks.
- Execute, detect, and investigate Credential access attacks.
- Execute, detect, and investigate Lateral movement attacks.
- Execute, detect, and investigate other types of attacks.

## Disclaimer

This presentation, demonstration, and demonstration model are for informational purposes only and (1) are not subject to SOC 1 and SOC 2 compliance audits, and (2) are not designed, intended or made available as a medical device(s) or as a substitute for professional medical advice, diagnosis, treatment or judgment. Microsoft makes no warranties, express or implied, in this presentation, demonstration, and demonstration model. Nothing in this presentation, demonstration, or demonstration model modifies any of the terms and conditions of Microsoft’s written and signed agreements. This is not an offer and applicable terms and the information provided are subject to revision and may be changed at any time by Microsoft.

This presentation, demonstration, and demonstration model do not give you or your organization any license to any patents, trademarks, copyrights, or other intellectual property covering the subject matter in this presentation, demonstration, and demonstration model.

The information contained in this presentation, demonstration and demonstration model represents the current view of Microsoft on the issues discussed as of the date of presentation and/or demonstration, for the duration of your access to the demonstration model. Because Microsoft must respond to changing market conditions, it should not be interpreted to be a commitment on the part of Microsoft, and Microsoft cannot guarantee the accuracy of any information presented after the date of presentation and/or demonstration and for the duration of your access to the demonstration model.

No Microsoft technology, nor any of its component technologies, including the demonstration model, is intended or made available as a substitute for the professional advice, opinion, or judgment of (1) a certified financial services professional, or (2) a certified medical professional. Partners or customers are responsible for ensuring the regulatory compliance of any solution they build using Microsoft technologies.

## Copyright

© 2024 Microsoft Corporation. All rights reserved. 

By using this demo/lab, you agree to the following terms:

The technology/functionality described in this demo/lab is provided by Microsoft Corporation for purposes of obtaining your feedback and to provide you with a learning experience. You may only use the demo/lab to evaluate such technology features and functionality and provide feedback to Microsoft. You may not use it for any other purpose. You may not modify, copy, distribute, transmit, display, perform, reproduce, publish, license, create derivative works from, transfer, or sell this demo/lab or any portion thereof.

COPYING OR REPRODUCTION OF THE DEMO/LAB (OR ANY PORTION OF IT) TO ANY OTHER SERVER OR LOCATION FOR FURTHER REPRODUCTION OR REDISTRIBUTION IS EXPRESSLY PROHIBITED.

THIS DEMO/LAB PROVIDES CERTAIN SOFTWARE TECHNOLOGY/PRODUCT FEATURES AND FUNCTIONALITY, INCLUDING POTENTIAL NEW FEATURES AND CONCEPTS, IN A SIMULATED ENVIRONMENT WITHOUT COMPLEX SET-UP OR INSTALLATION FOR THE PURPOSE DESCRIBED ABOVE. THE TECHNOLOGY/CONCEPTS REPRESENTED IN THIS DEMO/LAB MAY NOT REPRESENT FULL FEATURE FUNCTIONALITY AND MAY NOT WORK THE WAY A FINAL VERSION MAY WORK. WE ALSO MAY NOT RELEASE A FINAL VERSION OF SUCH FEATURES OR CONCEPTS. YOUR EXPERIENCE WITH USING SUCH FEATURES AND FUNCITONALITY IN A PHYSICAL ENVIRONMENT MAY ALSO BE DIFFERENT.

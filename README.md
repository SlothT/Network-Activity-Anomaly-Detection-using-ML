# Network Activity Anomaly Detection

This project focuses on detecting anomalies in network activity, specifically identifying Neptune (SYN flood) attacks using machine learning techniques.

## Dataset

The dataset contains detailed records of network activities, with each record labeled as either normal or a "Neptune" attack. This binary classification problem aims to distinguish between legitimate network traffic and potential security threats.

### Key Details:
- Training set: 86,845 rows
- Test set: 21,712 rows
- Target variable: "Attack" (0 for normal, 1 for Neptune attack)

## What is a Neptune Attack?

A Neptune attack, also known as a SYN flood attack, is a type of denial-of-service (DoS) attack. The attacker overwhelms a target system with a high number of SYN requests, exploiting the TCP handshake process to consume resources and render the system unresponsive to legitimate traffic.

## Model

This project uses Support Vector Machine (SVM) for classification. SVM is chosen for its effectiveness in high-dimensional spaces and its versatility through different kernel functions.


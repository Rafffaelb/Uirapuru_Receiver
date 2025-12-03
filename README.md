# 📡 Receiver_Characterization

**Receiver_Characterization** is a repository dedicated to the RF characterization of the **Uirapuru Horn** antenna and its associated receiver components. It compiles measurement data, S-parameters, and system analysis obtained through high-precision instrumentation and laboratory experimentation.

---

## 🚀 Project Overview

This project provides a complete characterization of the **Uirapuru Horn antenna**, using a **Rohde & Schwarz ZNB Vector Network Analyzer (VNA)** to obtain accurate **S-parameter** measurements. These measurements support ongoing research and development of the Uirapuru radiometric receiver system.

A central component of the receiver is the **hybrid coupler**, designed and assembled at the **Federal University of Campina Grande (UFCG)**. This device enables signal combination and separation, producing **sum (Σ)** and **difference (∆)** outputs, essential to the receiver architecture.

All measurements — including the detailed S-parameter analysis of the hybrid coupler — were performed in the **Radiometry Laboratory at UFCG** and are included here through structured datasets and annotated Jupyter notebooks.

---

## 🔧 Hybrid Coupler Characterization

The hybrid coupler plays a critical role in the signal-routing process. Key measurement observations include:

- **Isolation** in the cross-port configurations (e.g., **ports 1–3** and **2–4**)  
- **Transmission** predominantly between adjacent port pairs: **1–2**, **2–3**, **3–4**, and **1–4**  
- **S11 stability**, with consistent reflection performance across all ports  

These results are visualized and discussed in the included Jupyter notebooks, providing clarity and reproducibility for anyone studying the device’s behavior.

---

## 🛰️ Full Receiver Integration

When integrated with the central receiver assembly (as shown in the system schematic), the signal chain includes:

- A **WanTcom LNA** providing an additional low-noise amplification stage  
- An **ADC + DSP system**, implemented using a **SKARAB** processing board from Peralex  

Together, these components form the complete front-end signal path of the Uirapuru receiver — from antenna to digital backend.

---

## 📁 Repository Structure


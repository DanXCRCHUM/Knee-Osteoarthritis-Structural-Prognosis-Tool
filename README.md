
# KOSP — Knee Osteoarthritis Structural Prognosis Tool
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17539544.svg)](https://doi.org/10.5281/zenodo.17539544)

KOSP is a clinically oriented software application designed to predict the risk of rapid structural progression in knee osteoarthritis. Based on imaging (magnetic resonance imaging and radiography) data for the outcomes, KOSP evaluates three biomarkers and two osteoarthritis risk factors to generate prognostic insights. By analyzing these parameters, KOSP assists healthcare professionals in identifying patients at an elevated risk of joint deterioration, facilitating earlier interventions and personalized treatment planning. Seamlessly integrated into clinical workflows, KOSP offers evidence-based support for specialists aiming to monitor and manage knee osteoarthritis with precision.

---

## System requirements
- **OS:** Windows 10 or 11 (64-bit)  
- **Runtime:** MATLAB Runtime **R2024a** (installer will offer to download on first install)

## Installation
1. **Download the installer.** In this repository, locate `MyAppInstaller_web.exe`.  
   If GitHub opens a new page, click **“View raw”** to start the download.
2. **Run the installer.** Double-click the downloaded file.
3. **Windows Defender warning.** You may see a security prompt. This is expected for unsigned installers.  
   Click **More info** → **Run anyway**.
4. **Follow the steps.**  
   - Choose the installation destination  
   - (Optional) Create a desktop shortcut  
   - Allow the installer to download **MATLAB Runtime R2024a** (one-time)  
   - Click **Next** through the prompts, then **Begin install**

## Usage
- Launch **KOSP** from the desktop shortcut or by searching **“KOSP”** in the Windows taskbar.  
- Enter the patient inputs and click **Predict** to generate the prognosis.  
  The interface behaves like a standard desktop application (e.g., a calculator).

## Versioning & archival
This project is archived on **Zenodo** for long-term accessibility and reproducibility.  
**Version DOI:** https://doi.org/10.5281/zenodo.17539544

## How to cite
Bonakdari D, Martel-Pelletier J, *et al.* **KOSP (Knee Osteoarthritis Structural Prognosis Tool)**, *v1.0.1*. Zenodo. https://doi.org/10.5281/zenodo.17539544

## Troubleshooting
- **Runtime not found / app won’t start:** Re-run the installer and ensure **MATLAB Runtime R2024a** is installed.
- **Windows “Protected your PC” message:** Use **More info → Run anyway** (see Install step 3).


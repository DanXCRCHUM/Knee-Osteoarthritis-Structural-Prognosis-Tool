# Knee-Osteoarthritis-Structural-Prognosis-Tool
Overview

The Knee Osteoarthritis Structural Prognosis Tool (KOSP) is a clinically oriented predictive software application designed to identify patients at high risk of rapid structural progression of knee osteoarthritis (OA). Leveraging machine learning (ML) techniques, specifically a Bayesian-optimized Support Vector Machine (SVM) model, KOSP provides healthcare professionals with a reliable, real-time risk assessment tool.

This tool was developed based on rigorous scientific validation, incorporating easily obtainable clinical and biochemical markers to facilitate personalized treatment decisions, allowing clinicians to intervene earlier and more effectively.

Model and Methodology

Machine Learning Model

The core predictive engine of KOSP is an SVM model optimized using Bayesian Optimization (BO). BO systematically tunes the model hyperparameters, significantly improving the accuracy and generalizability of predictions compared to traditional methods. The model uses the following input parameters:

Age

BMI (Body Mass Index)

Serum biomarkers:

Ratio of C-reactive protein (CRP) to Monocyte Chemoattractant Protein-1 (MCP-1)

Ratio of Leptin to CRP

Gender (1 for male, 0 for female)

Predictive Capabilities

The SVM-BO model has demonstrated exceptional predictive accuracy with an Area Under the Curve (AUC) reaching up to 99% in external validation phases, ensuring robust and reliable predictions in clinical settings.

Installation

Requirements

MATLAB software (R2019a or later recommended)

File Structure

PredictProbability.m: MATLAB script for prediction.

BO-SVM.mat: Pre-trained Bayesian-optimized SVM model.

KneeOAPredictor.mlapp: MATLAB App providing a user-friendly graphical interface for predictions.

Setup

Clone the repository to your local environment.

Ensure all files (PredictProbability.m, BO-SVM.mat, KneeOAPredictor.mlapp) are located in the same directory.

Usage

Using the MATLAB App

Open MATLAB and navigate to the directory containing KneeOAPredictor.mlapp.

Double-click on KneeOAPredictor.mlapp to launch the graphical user interface.

Input patient data when prompted:

Age

BMI

MCP-1 level

Leptin level

CRP level

Gender (enter "1" for male, "0" for female)

Click "Predict" to obtain the prognosis.

Using the MATLAB Script

Alternatively, use the PredictProbability.m script directly in MATLAB:

% Run the script
type PredictProbability.m

% Follow the dialog to input patient parameters

Interpreting the Results

The model outputs:

Progressor: Patient is at high risk of rapid structural progression of knee OA.

Non-Progressor: Patient is at low risk.

Clinical Integration

KOSP seamlessly integrates into clinical workflows, providing:

Quick and accurate identification of high-risk patients.

Evidence-based, real-time decision support for personalized patient management.

Repository

The complete application, including source code and model files, is available in this repository.

References

This tool was scientifically validated in the following research:

Bonakdari H, et al. A warning machine learning algorithm for early knee osteoarthritis structural progressor patient screening. Ther Adv Musculoskel Dis. 2021.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact

For further information or questions about KOSP, please contact the repository maintainer or open an issue in the repository.

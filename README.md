# Mefron PCB Analysis Tool

This Streamlit application is designed for Mefron to assist in determining quality check requirements and certification needs for user-defined PCB boards based on uploaded images.

**IMPORTANT NOTE:**
This project provides the user interface and structure for a PCB analysis tool. The core functionality of analyzing PCB images to determine "quality check required" or "certification needed" **requires a custom-trained Machine Learning (ML) model**. This repository includes a placeholder `analyze_pcb_image` function in `app.py` that you will need to replace with your own ML model's inference logic.

## Features

*   **Image Upload:** Upload PCB images for analysis.
*   **Analysis Options:** Choose between:
    1.  Check Certification & Quality Check
    2.  Quality Check Required
    3.  Certification Needed
*   **Results Display:** Displays simulated analysis results (to be replaced by real ML output).

## Project Structure

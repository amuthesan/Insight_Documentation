# Insight Light Rover: Quick Start Guide

*System: Tethered Fiber Optic Inspection Rover*
*Controller: Lenovo Legion Go*

## Beta Test Plan
Please download the `Insight Light Rover Beta v0.1.pdf` for the detailed test plan.

### Validation Feedback Form
I have also included a `Insight Rover EVT, DVT.pdf` which contains the **Validation Feedback Form**.
*   **Objective**: This form is critical for tracking the Engineering Validation Test (EVT) status.
*   **Instructions**: Please fill out this form as you conduct your tests. It covers:
    *   **Boot & Connection**: Verifying basic system startup and connectivity.
    *   **Mechanical Function**: Testing joystick controls and zoom.
    *   **Recording Logic**: Ensuring auto-recording works.
    *   **Critical Blockers**: Any issues that prevent testing must be noted here.

**A Note on Testing:**
While the test plan provides a structured guide, I encourage you to use the Insight Light Rover in your real-world use cases. Simulated tests are helpful, but real-world usage often reveals valuable insights and potential issues that might not appear in controlled environments. Your feedback from actual field operations is incredibly important to us!

## 1. Hardware Deployment

1.  **Connect Tether**: Securely connect the fiber optic tether to the **Insight Light Rover** and the **Ground Network Unit (GNU)**.
    *   *Check*: Ensure the LC fiber connectors are clean and fully seated ("Click" sound).
2.  **Power Ground Unit**: Turn on the GNU. Wait for 30 sec for warm up.
3.  **Power Rover**: Turn on the Rover.
    *   ⚠️ **Wait 15 Seconds**: Allow the SIYI A8 Gimbal to perform self-calibration. **Do not touch** the camera head during this process.
    *   *Note: Recording starts when vehicle arms.*

### Shutdown Procedure

1.  **Power Off Rover**: Turn off the rover **FIRST** (Safe file closure).
2.  **Power Off Ground Unit**.
3.  **Shut Down Legion Go**.

## 2. Controller Setup (Legion Go)

1.  **Power On**: Press the power button.
2.  **Auto-Launch**: The **Insight Dashboard** will open automatically.

## 3. Operations & Controls

| Component | Input | Action |
| :--- | :--- | :--- |
| **Movement** | **Left Joystick** | Forward / Reverse / Turn Rover |
| **Gimbal** | **Right Joystick** | Pitch (Up/Down) & Yaw (Left/Right) |

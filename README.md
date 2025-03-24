# 🛡️ Tanium Test Files for EDR Detection

This repository contains a collection of test files designed to evaluate the effectiveness of Endpoint Detection and Response (EDR) systems, such as Tanium. These files simulate various scenarios to help security professionals assess and fine-tune their detection capabilities.

---

## 📁 Repository Contents

- **`calc.hta`**: A simple HTML Application that, when executed, launches the Calculator application. Useful for testing script-based execution detections.

- **`dl.dat`**: A data file intended to simulate a download or data transfer operation. Can be utilized to test the EDR's ability to monitor and flag suspicious data movements.

- **`installUtil.cs`**: A C# source file that leverages the `InstallUtil.exe` utility for executing code. This technique is often used by adversaries to bypass standard execution policies.

- **`run_calc.dat`**: A data file designed to execute the Calculator application upon interaction. Serves to test the EDR's response to unconventional execution methods.

---

## ⚠️ Disclaimer

These test files are intended solely for educational and testing purposes within authorized environments. Unauthorized use of these files on systems without explicit permission is strictly prohibited and may violate legal and ethical guidelines.

---

> **Note**: Always ensure you have proper authorization before conducting security tests. Misuse of these files can lead to unintended consequences.

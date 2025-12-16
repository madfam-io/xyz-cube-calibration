# 🧊 XYZ Cube Calibration Cockpit

A standalone, interactive engineering dashboard designed to fine-tune OrcaSlicer settings for the perfect 20mm Calibration Cube.

This tool transforms a static list of slicer settings into an active "Flight Plan" for solving common printing defects like Elephant's Foot, Ghosting/Ringing, and Seam visibility.

## ✨ Features

* **📊 Tiered Settings Transcript:** A complete, lossless record of every setting (Quality, Strength, Speed, etc.) organized by hierarchy. Critical physics settings are highlighted; niche settings are faded to reduce noise.
* **👁️ Visual Diagnostics:** Interactive SVG diagrams that visually explain defects (e.g., distinguishing between "Bad" and "Good" geometry) to help identify issues on the physical part.
* **✅ Interactive Flight Plan:** A clickable checklist of the specific optimizations needed to fix the print, complete with "The Why" tooltips explaining the engineering physics behind each change.
* **🧮 Dynamic Flow Calculator:** Stop guessing. Input your caliper measurements (current flow + measured wall thickness) to calculate the exact Flow Ratio required for dimensional accuracy.
* **💾 Smart Profile Export:** One-click generation of a `.json` configuration file containing the optimized settings, ready to be imported into OrcaSlicer.
* **🌍 Fully Bilingual:** Instant toggle between **English** and **Spanish** (Español) for all technical terms and interface elements.
* **🌑 Dark Mode:** Automatically adapts to your system's light or dark theme.

## 🚀 How to Use

1.  **Download:** Save the provided code as `calibration.html` on your computer.
2.  **Open:** Double-click the file to open it in any web browser (Chrome, Safari, Edge, Firefox). No internet connection required.
3.  **Diagnose:** Compare your printed cube to the **Visual Diagnostics** panel.
4.  **Tune:** Follow the **Flight Plan** checklist. As you update settings in OrcaSlicer, check them off in the tool.
5.  **Calculate:** If your wall thickness isn't perfect (0.42mm), use the **Flow Calculator** section to get the precise ratio.
6.  **Export:** Click the **💾 Export Profile** button to download a Snapmaker-optimized config file.

## 🛠️ Calibration Targets

This cockpit is tuned to achieve:
* **Dimensional Accuracy:** +/- 0.05mm on X/Y/Z axes.
* **Sharp Corners:** Elimination of "bulging" or ringing on the embossed letters.
* **Invisible Seams:** Utilizing "Scarf Joint" logic to hide the Z-seam.
* **Perfect First Layer:** Elimination of "Elephant's Foot" (base flare).

---
*Generated for Snapmaker 2.0 A350 / OrcaSlicer optimization.*

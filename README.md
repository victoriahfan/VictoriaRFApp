# Receptive Field Explorer

A lightweight Dash web app for visualizing receptive‐field (RF) heatmaps and timecourses across multiple ROIs in 2-photon imaging data.

<img width="1440" alt="screenshot_app" src="https://github.com/user-attachments/assets/81e5d985-59e0-46bc-bb8d-fd734049384b" />

## Current Features

- **Interactive RF image**  
  Click on any ROI in the 2-photon image to select it. 

- **RF Traces Grid**  
  Displays the timecourse of dF/F for each of the receptive field stimulus positions for the current ROI.

- **Mean Timecourse Summary**  
  Overlays all ROIs’ mean responses, highlights the current ROI in red, and shows the overall mean in black.

- **RF COM Scatter**  
  Shows each ROI’s center-of-mass (COM) on the RF grid, with the selected ROI highlighted in red.

- **All-ROIs & Heatmap Views**  
  Toggle to show all ROIs’ mean traces or the 2D activation heatmap for the current ROI.

- **File Upload & Sample Data**  
  Load your own `.mat`, `.csv`, and image files via drag-and-drop, or fall back to included sample data.

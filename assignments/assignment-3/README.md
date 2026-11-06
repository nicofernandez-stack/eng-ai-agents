Assignment 3: Anti-UAV Visual Tracking System
Name: Nicolas Fernandez-Pallares 
Date of submission: 2026-11-05

Description:
Fine tunes a YOLO11n detector on the DUT Anti-UAV benchmark, and then tracks the drone through the benchmark's 20 tracking videos
with a constant velocity Kalman Filter and compares with the detector alone.

Files:
Assignment3_PartA.ipynb - The notebook, with all the outputs saved
Assignment3_PartB.ipynb - the output video as requested that has the kalman box and trajectory drawn on every frame

Results:
Detector mAP@0.5 is 0.885 at input size 640, 0.901, at 1280
Tracking AUC: 0.629 for detector alone and 0.647 with the Kalman filter

How To Run:
1.) Open the notebook in Google Colab and utilizes T4 GPU runtime
2.) Run all cells in order, full run take about 1 hour.

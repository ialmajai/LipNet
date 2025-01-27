# LipNet - Lipreading System with Automatic Lip ROI Extraction

This repository is a fork of the original **LipNet** implementation by **Nicholas Renotte**, available at [https://github.com/nicknochnack/LipNet](https://github.com/nicknochnack/LipNet).

## Added features

1. **Automatic Face Tracking**:
   - Utilizes **dlib's facial landmark detector** to locate and track faces in video frames.
  

2. **ROI Extraction for Lips**:
   - Extracts a dynamic Region of Interest (ROI) around the lips from the detected facial landmarks.

3. **Tracked Videos Caching**
   - Extracted ROIs are cached to avoid reruning dlib tracking during data loading. 







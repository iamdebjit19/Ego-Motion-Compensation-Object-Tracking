# Ego-Motion Compensation for Object Tracking

## Overview
This project explores ego-motion compensation techniques for object tracking in monocular video streams. The objective is to decouple camera motion from object motion to improve tracking stability and collision reasoning.

## Project Background
This project builds upon:
- Monocular Visual Odometry
- Vision-Based Obstacle Detection & Tracking

It was implemented as an experimental robotics + AI prototype using Jupyter Notebook.

## Implemented Components
- Ego-motion estimation using monocular visual odometry
- Object detection and multi-object tracking
- Camera motion compensation
- Relative motion analysis
- Time-to-Collision (TTC) estimation (prototype stage)

## Project Status
This project is a **prototype / experimental implementation**.

Development was intentionally halted due to:
- Kernel instability during repeated tracking and visualization
- Hardware and memory constraints in notebook-based execution
- Focus on conceptual correctness over forced completion

## Results
Partial results demonstrate:
- Improved object motion consistency after ego-motion compensation
- Feasible TTC estimation under monocular assumptions

## Limitations
- Monocular depth ambiguity
- Kernel instability under heavy computation
- No sensor fusion (LiDAR / Radar)
- Decision-level collision classification not fully implemented

## Future Work
- Script-based modular refactoring
- Ego-motion-aware tracking refinement
- Robust collision risk classification
- Embedded deployment (toy car / robot platform)

## Author
Debjit Ghosh


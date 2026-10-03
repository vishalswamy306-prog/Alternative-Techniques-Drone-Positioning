# Alternative Techniques of Positioning and Navigation of Aerial Drone

## AI-Based Drone Image Geolocation Using Satellite Image Matching

This project explores an alternative technique for aerial drone positioning and navigation using artificial intelligence, computer vision, and satellite image matching.

The implemented system uses an aerial drone image as the input, extracts a compact visual feature representation using an AI-based model, compares the extracted features with reference satellite imagery, estimates the geographical coordinates, and validates the estimated location against known ground-truth coordinates.

The implementation and validation were carried out using the Kaggle Notebook environment with GPU-based processing.

---

## Project Objective

The main objective of this project is to investigate visual geolocation as an alternative technique for positioning and navigation of aerial drones.

Instead of depending only on conventional positioning sources, the approach uses visual information from the surrounding environment to estimate the geographical location of the drone.

---

## Project Pipeline

The implemented workflow is:

```text
Drone Image
     ↓
AI Feature Extraction
     ↓
384-Dimensional Feature Vector
     ↓
Satellite Image Features
     ↓
Cosine Similarity Matching
     ↓
Local Refinement
     ↓
Estimated Geographic Coordinates
     ↓
Ground-Truth Validation
     ↓
Localization Error

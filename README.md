# Squatting Project
This project is a course requirement for BME 488 Computational Biomechanics.The project aims to investigate parameters that are crucial for performing a safe full squat using an individual's anthropometry.

## Anthropometry
- Body weight
- Leg length: Patella to ankle
- Thigh length: Greater trochanter to patella
- Torso-head-neck length: Nose to greater trochanter
- Upper extremity (arm) length: Shoulder to wrist

## Joint angles
- Arm angle: Angle between vetical and arm at shoulder
- Torso angle: Angle between vertical and spine at hip
- Thigh angle: Angle between vertical and thigh at knee
- Leg angle: Angle between vertical and leg at ankle

## Tests
Given an individual's body dimensions, does the length of the femur allow the individual to obtain stability when attempting a full squat?
#### torso_angle.py
Torso angle was incremented. For each torso angle, femur length was varied and the x coordinate for the centre of mass was calculated and plotted.
#### femur_angle.py
Femur angle was incremented. For each femur angle, femur length was varied and the x coordinate for the centre of mass was calculated and plotted.
#### leg_angle.py
Leg angle was incremented. For each leg angle, femur length was varied and the x coordinate for the centre of mass was calculated and plotted.

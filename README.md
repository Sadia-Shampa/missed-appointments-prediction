# Predicting Missed Medical Appointments

Final project for EE 656 (Introduction to Big Data Analytics), University of Alabama at Birmingham.

Predicts which clinic appointments are likely to be missed, so staff can target reminder calls where they help most.

## Data
- 800 patients and 3,200 appointments in two linked tables (patients and appointments)

## Tools
Python, pandas, scikit-learn, MySQL, Matplotlib

## What I did
- Merged patient and appointment data and explored no-show patterns in Python and MySQL
- Trained a logistic regression model to predict no-shows
- Ranked appointments by predicted risk to build a weekly call list

## Key results
- Appointments with reminders had a 16-point lower no-show rate (31.8% vs. 48.0%)
- Higher no-show rates among Medicaid patients, late-afternoon slots, and long scheduling lead times
- The model caught 67% of missed visits
- The top-100 risk list contained 61% actual no-shows vs. a 34.8% baseline (about 1.8x better than random calls)

## Files
- `EE656_Final_Project_Missed_Appointments.ipynb`: full analysis notebook

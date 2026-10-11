# Nearest Hospital Recommender

## Project Overview
Bhubaneswar hospital discovery and bed-request application. 
## Problem Statement 
Finding the nearest hospital with available beds during medical emergencies can be challenging. Patients and their families often struggle to identify hospitals with vacant beds, especially when timely treatment is critical. The lack of centralized, real-time information about hospital bed availability can cause delays in admission and increase the difficulty of accessing appropriate healthcare services.
## Solution 
Developed a hospital bed availability system that helps users identify the nearest hospitals with available beds using hospital location and bed availability data. The system provides hospital details and supports distance-based hospital identification, enabling users to find suitable healthcare facilities more efficiently during emergencies. It aims to reduce the time spent searching for available beds and support faster, more informed hospital selection.

## Setup Instructions
1. Place the CSV files (`hospital_master.csv`, `hospital_pmjay_status.csv`, `hospital_specialities.csv`) in `data/`.
2. Install Python dependencies:
   `pip install -r backend/requirements.txt`
3. Run the backend unit tests:
   `python backend/tests/test_core.py`

See [DEPLOYMENT.md](./DEPLOYMENT.md) for the implemented production safeguards, required environment configuration, and remaining deployment limitations.

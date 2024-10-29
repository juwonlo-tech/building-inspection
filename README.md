# Building Inspection
**Project Overview: Building Inspection Analysis**

**Introduction:**
This project entails analyzing building inspection data provided. The goal is to gain insights into inspection outcomes, identify patterns, and develop models to understand factors influencing building safety ratings.

**Data Structure:**
1. **Master Building List:** Contains information on buildings, each with a unique identifier.
2. **Inspection Data:** Ten separate files, one per year, containing inspection details including pass/fail status, safety rating, and violation counts.
3. **Location Codes Lookup Table:** Provides location information based on location codes appended to building IDs.

<img width="947" alt="Screenshot 2024-05-13 at 12 01 31 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/5ac24e66-939f-4672-88f6-c7c11cf420a6">

<img width="947" alt="Screenshot 2024-05-13 at 12 02 21 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/6d6a8b38-9942-430d-b110-7f98be6df0ee">


**Analysis Tasks:**

1. **Distribution of Building Floors:** A table and visualization are created to show the number of buildings with varying numbers of floors. Patterns in building size distribution can be observed, potentially indicating trends in construction or development over time.
<img width="947" alt="Screenshot 2024-05-13 at 12 03 40 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/4478ed43-cb7f-4e63-98ff-2a9000ae81fd">

2. **Inspection Frequency by Geography:** Another table and visualization display the number of inspections conducted in each geographical area. Patterns in inspection density across different areas may suggest variations in regulatory enforcement or building activity.
<img width="947" alt="Screenshot 2024-05-13 at 12 04 31 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/bd77f423-df2a-4fca-b35c-c10a464ec96e">


3. **Inspection Outcomes in Rural vs. Urban Areas:** A comparison of inspection outcomes (pass/fail) in rural versus urban areas is conducted, highlighting any disparities in building safety standards between these regions.
<img width="947" alt="Screenshot 2024-05-13 at 12 05 06 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/bd4a49c7-c874-4ad0-8414-acbbaf229c27">

4. **Uninspected Buildings:** The number of buildings from the master list that have not been inspected is determined, shedding light on potential gaps in regulatory oversight.
<img width="947" alt="Screenshot 2024-05-13 at 12 05 47 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/d9396637-af3b-436e-9381-37cf02c591d8">

5. **Hypothesis Testing on Elevator Violations:** A hypothesis regarding elevator violations' impact on building safety is tested using the first inspection date for buildings with multiple inspections. This analysis aims to validate or refute the hypothesis and provide insights into other contributing factors to building safety.
<img width="947" alt="Screenshot 2024-05-13 at 1 43 25 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/468bbf59-a0da-499b-9156-76452b035a50">


6. **Modeling Building Safety Ratings:** 2 predictive models are developed to quantify the relationship between building safety ratings, violations, and other potential variables. The modeling approaches are explained, and the results are interpreted to understand the factors influencing building safety ratings.
<img width="947" alt="Screenshot 2024-05-13 at 1 40 37 PM" src="https://github.com/juwonlo-tech/building-inspection/assets/77176412/c3abe04d-6829-4102-8e59-17abd5998e3d">

**Conclusion:**
This overview summarizes the objectives, data structure, and analysis tasks involved in the building inspection analysis project. Through comprehensive data exploration, hypothesis testing, and predictive modeling, the project aims to enhance understanding of building safety and inform policy decisions to improve regulatory effectiveness.


The jupyter notebook for this project is available on: https://github.com/juwonlo-tech/building-inspection/blob/main/Building%20Inspection.ipynb

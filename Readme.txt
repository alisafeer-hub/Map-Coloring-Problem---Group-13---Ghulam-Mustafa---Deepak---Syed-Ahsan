🗺️ AI-Based Map Coloring Problem using Forward Checking and MRV Heuristic

This project demonstrates how Artificial Intelligence (AI) techniques can be applied to solve the Map Coloring Problem, a classic Constraint Satisfaction Problem (CSP).
It uses Forward Checking and the Minimum Remaining Values (MRV) heuristic to efficiently assign colors to regions of a map so that no two adjacent regions share the same color.

The project focuses on the USA county adjacency dataset to demonstrate practical applications of CSP techniques in spatial problems.



📋 Project Overview

The Map Coloring Problem aims to assign colors to map regions while ensuring that neighboring regions have distinct colors.
This project implements CSP techniques to solve the coloring problem efficiently and visualizes the results using Python.

It provides a practical demonstration of constraint satisfaction applied to geographic data.



🎯 Objectives

Solve the Map Coloring Problem using Forward Checking and MRV Heuristic.

Visualize color assignments for all regions in the dataset.

Work with a real-world USA county adjacency dataset.

Provide an educational example of CSP applications.



🧩 Features

Applies Forward Checking to reduce conflicts during color assignment.

Uses MRV Heuristic to prioritize regions with fewer color options.

Visualizes colored maps using Python.

Dataset-based approach using USA counties adjacency information.

Step-by-step implementation in a Jupyter Notebook.



📂 Dataset Details

Dataset Name: USA County Adjacency Dataset (Kaggle)

Dataset Description:
The dataset contains adjacency information for all U.S. counties. Each record shows which counties border each other.



Attributes:

Attribute Name	Description
country name	Name of the U.S. county
fipscounty	FIPS code (unique identifier for each county)
neighborname	Name of neighboring county
fipsneighbor	FIPS code of the neighboring county




📦 Dataset Source:
👉 USA County Adjacency Dataset (Kaggle)




⚙️ Technologies Used

Programming Language: Python
Environment: Jupyter Notebook

Libraries Used:

pandas – Data manipulation

numpy – Numerical computation

matplotlib – Visualization

networkx – Graph-based map representation





🚀 How to Run This Project

Open the Jupyter Notebook

jupyter notebook Map_Coloring_Forward_Checking.ipynb


Run all cells step-by-step:

Load and inspect dataset

Preprocess adjacency data

Apply Forward Checking & MRV Heuristic

Visualize the colored map




🧾 Folder Structure
AI-Map-Coloring-Problem/
│
├── us_county_adjacency.csv              # Dataset file
├── Map_Coloring_Forward_Checking.ipynb  # Main project notebook
├── Map_Coloring_Presentation.pptx       # PowerPoint presentation
├── Map_Coloring_Report.docx             # project report
└── README.md                            # User guide (this file)



👨‍💻 Author

Ghulam Mustafa, Deepak, Syed Ahsan
BSCS – 6th Semester, Section A, 14th Batch
Department of Computer Science
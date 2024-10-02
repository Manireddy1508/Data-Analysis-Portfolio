# Uber-Ride-Analysis-Project

## About

Hi, I'm Manichandra! I recently recieved a degree in Information Systems Technology, where I have developed a solid foundation in both business and technology. I’m passionate about how technology can streamline operations and drive innovation. My coursework has covered a wide range of topics, including database management, systems analysis, and enterprise architecture.

I enjoy working with data-driven systems and exploring how technology can be applied to solve real-world business problems. My experience with tools like SQL, Python, and cloud computing platforms has enhanced my ability to manage and analyze information, providing actionable insights to decision-makers.

I’m excited to bring my skills in systems analysis, database design, and project management into the workplace, and I look forward to contributing to innovative IT solutions.

In my free time, I love exploring new data analysis tools and techniques, and I'm always looking for opportunities to expand my knowledge and skills. Whether working on a team or independently, I am motivated by the thrill of discovering new insights and the satisfaction of using data to solve complex business challenges.

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents
- [About](#About)
  
- [Overview](#Overview)
  
- [Structure](#Structure)     

- [Analysis](#Analysis)

- [Highlights](#Highlights)

- [Technologies](#Technologies)

# Uber Analysis Project :

(https://nbviewer.org/github/Manireddy1508/Uber-Ride-Analysis/blob/main/Uber%20analysis.ipynb) - Use this link to get detailed plots and tables.

## Overview

This project aims to analyze Uber ride patterns, focusing on both temporal and geographic dimensions. Through various data visualizations such as violin plots, pivot tables, and heat maps, the project provides insights into ride demand trends across different times of day, days of the week, and geographic locations. The goal is to understand peak hours, geographic hotspots, and operational efficiencies for Uber’s services.

## Structure

Jupyter Notebook (Uber_analysis.ipynb): The main notebook containing all the data analysis and visualizations.

Data Files: The dataset used for this project, which includes Uber ride information with attributes like Date/Time, dispatching_base_number, and active_vehicles.

README.md: This file, providing an overview of the project.

## Analysis

1. Temporal Analysis
Peak Hours Identification: Extracted the day and hour information from the Date/Time column to identify periods with the highest demand for Uber rides.
Day-to-Day Ride Patterns: Explored how ride volume fluctuates across different days of the week using pivot tables and heat maps.

2. Geographic Analysis
Heat Map of Ride Density: A heat map was generated to visualize where Uber rides are concentrated geographically, highlighting demand hotspots.
Dispatching Base Number Analysis: Analyzed how different dispatching base numbers handle rides across time, identifying the bases with the highest and lowest ride activity.

3. Visualizations
Violin Plot: Visualized the distribution of active vehicles across different dispatching base numbers.
Pivot Tables & Heat Maps: Used to provide intuitive visual insights into the ride volume across days, hours, and geographic locations.

## Highlights

Ride Patterns: The project successfully identifies peak demand periods, both hourly and daily, which can inform Uber’s fleet management.

Geographic Hotspots: Using heat maps, the project pinpoints geographic areas with the highest ride density, allowing Uber to optimize driver allocation.

Dispatching Base Efficiency: The violin plot and heat maps show how different base numbers manage ride demand, helping to evaluate operational performance.

##Technologies

Python: The primary programming language used in this project.

Jupyter Notebook: Used to write and run the analysis interactively.

Pandas: For data manipulation and analysis.

Plotly: For interactive visualizations (e.g., violin plots).

Seaborn & Matplotlib: For generating heat maps and other visualizations.

Folium: For creating geographical heat maps.




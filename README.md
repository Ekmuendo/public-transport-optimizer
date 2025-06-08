🚀Project Overview
This project focuses on improving public transport efficiency by optimizing bus stop clusters and routes using machine learning techniques. The goal is to help make urban transport smarter, faster, and more sustainable—supporting SDG 11: Sustainable Cities and Communities.

📋Problem Statement
Urban bus routes often get messy and inefficient, leading to longer trips and frustrated commuters. This project applies KMeans clustering to group stops logically and a Nearest Neighbor algorithm to optimize stop visitation order within each cluster.

🗂Dataset
Dataset: Synthetic public transport stops data (data/stops.csv)

Features: stop_id, stop_name, latitude, longitude

The data mimics GTFS stops info, essential for clustering and route optimization.

🧠Methodology
Stop Clustering (Notebook 1)

Load stops dataset

Use KMeans to cluster stops into groups based on location

Visualize clusters with an interactive Folium map

Route Optimization (Notebook 2)

For each cluster, apply the Nearest Neighbor heuristic

Determine the most efficient route order between stops

Output the optimized routes per cluster

🗂 Project Structure
csharp
Copy
Edit
public-transport-optimizer/
│
├── data/
│   └── stops.csv                # Raw stops data
│
├── notebooks/
│   ├── 1_stop_clustering_kmeans.ipynb   # Clustering and visualization
│   └── 2_route_optimization.ipynb        # Route optimization logic
│
└── README.md                   # Project documentation (this file)
⚙️ How to Run
Clone or download the repo

Make sure you have Python 3.x and Jupyter Notebook installed

Open the notebooks in Jupyter or VSCode

Run the notebooks cell by cell

Ensure the data/ folder with stops.csv is in the project root

🎯 Impact
This ML-powered approach provides city planners with an accessible way to rethink and optimize public transport routes, cutting commute times and boosting urban mobility aligned with SDG 11.

👨‍💻 About Me
I’m Evans Kyalo Muendo — software engineer and AI enthusiast, passionate about using data and code to solve real-world challenges.

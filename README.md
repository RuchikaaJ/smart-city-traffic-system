Smart City Traffic Management System

A Python-based traffic management application that uses graph algorithms to analyze road networks, find efficient routes, simulate traffic congestion, and support smart-city transportation planning.

Overview

The Smart City Traffic Management System represents a city's road network as a weighted graph, where intersections are nodes and roads are edges. Each edge has a weight representing travel time or cost.

The application uses Python, NetworkX, and Streamlit to provide an interactive dashboard for exploring routes, analyzing congestion, and evaluating network connectivity.

Features
Shortest Route Planning: Uses Dijkstra's algorithm to identify the minimum-cost route between locations.
Traffic Congestion Analysis: Uses Bellman–Ford to calculate routes when road travel times change.
Network Connectivity: Uses Breadth-First Search (BFS) and Depth-First Search (DFS) to explore connected locations.
Road Network Optimization: Uses Prim's and Kruskal's algorithms to generate a Minimum Spanning Tree (MST).
Interactive Dashboard: Allows users to select algorithms, simulate congestion, and compare route costs.
Dynamic Road Weights: Demonstrates how traffic changes can influence the optimal route.
Technologies Used
Python
NetworkX
Streamlit
Graph Theory and Graph Algorithms
Project Structure
smart-city-traffic-system/
├── App.py
├── route_planner.py
├── traffic_analysis.py
├── connectivity_module.py
├── mst_planner.py
├── requirements.txt
├── README.md
└── .gitignore
Installation and Setup
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/smart-city-traffic-system.git
cd smart-city-traffic-system

Replace YOUR-USERNAME with your GitHub username.

2. Create a virtual environment (recommended)
python -m venv .venv

Activate it on Windows:

.venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt

Ensure requirements.txt contains the packages required by your project, including streamlit and networkx.

4. Run the application
streamlit run App.py

Open the local URL displayed in your terminal to access the dashboard.

Algorithms Implemented
Algorithm	Purpose
Dijkstra's	Shortest-route calculation
Bellman–Ford	Route analysis with changing weights
BFS	Breadth-first network traversal
DFS	Depth-first network traversal
Prim's	Minimum Spanning Tree
Kruskal's	Minimum Spanning Tree
Learning Outcomes

This project demonstrates graph representation, algorithm implementation, route optimization, congestion simulation, and interactive dashboard development. It illustrates how graph algorithms can support transportation analysis and smart-city planning.

Future Improvements
Integrate real-time traffic data.
Display road networks on an interactive map.
Support more intersections and alternative routes.
Add traffic predictions using machine learning.
Include emergency vehicle route prioritization.

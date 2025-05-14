# 🚚 Smart Route Optimization System

An AI-powered web application for optimizing delivery routes using multiple vehicles, real road distances, and an interactive map interface. Built with Streamlit, OR-Tools, and OpenRouteService API.

---

## 🔍 Overview

This app helps businesses create the most efficient delivery routes by:
- Choosing a depot
- Selecting any number of delivery points
- Defining the number of available vehicles

The system calculates the optimal routes using real-world driving distances and visualizes them on a live map.

---

## ⚙️ Tech Stack

- **Frontend & UI:** Streamlit
- **Routing Engine:** Google OR-Tools (Vehicle Routing Problem Solver)
- **Distance API:** OpenRouteService (Real road distance matrix)
- **Map:** Folium (Leaflet-based interactive map)
- **Deployment:** Streamlit Cloud

---

## 🎯 Key Features

✅ Multi-vehicle route optimization  
✅ Real road distances (not Euclidean)  
✅ Fully interactive user input (vehicles, depot, markets)  
✅ Beautiful route map with step-by-step delivery points  
✅ Works with up to 10 vehicles and dozens of delivery locations  
✅ Instant deployment on the web  

---

## 🚀 Try It Live

👉 [Launch the App](https://route-optimizer-1.streamlit.app/)

> ℹ️ You can test it by selecting a depot and choosing your delivery markets. Then select how many vehicles to use, and the system will compute the optimal solution.


---



🧠 Use Case

This project was designed as a real-world logistics solution for companies delivering goods to supermarkets. The goal is to minimize total distance traveled and balance routes between vehicles.


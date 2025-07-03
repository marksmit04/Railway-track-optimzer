
# 🚆 Railway Track Optimizer

A C++ project that calculates the **most cost-effective way to connect cities using railway tracks**, based on **Prim's Minimum Spanning Tree (MST)** algorithm.

---

## 📌 Problem Statement

Design an optimal railway network by connecting cities such that:
- All cities are connected
- The total construction cost is **minimized**

This mirrors real-world infrastructure planning problems in transport networks.

---

## 🧠 Key Features

- **User Input**: Number of cities, city names, and connection costs  
- **Greedy Algorithm**: Uses Prim’s algorithm with priority queue for MST  
- **Readable Output**: Shows each optimal railway connection and the total minimum cost  
- **Real-World Simulation**: Uses actual city names instead of just numeric indices

---

## 💻 Technologies Used

- **Language**: C++  
- **Algorithm**: Prim’s MST (Greedy Approach)  
- **Data Structures**: Adjacency List, Priority Queue

---

## 🛠️ How It Works

1. Input the number of cities and their names
2. Enter the connection cost between each pair of cities
3. The program computes the Minimum Spanning Tree
4. Outputs the optimal connections and total cost

---

## ✅ Sample Output
____________________________________
                                             
 RAILWAY TRACK OPTIMIZER
____________________________________
Enter the number of cities: 4
Enter the names of the cities:
City 1: Noida
City 2: Pune
City 3: Hydrabad 
City 4: Gurgaon

Enter the cost to connect the cities (enter 0 if no direct connection):
Cost between Noida and Pune: 43
Cost between Noida and Hydrabad: 56
Cost between Noida and Gurgaon: 78
Cost between Pune and Hydrabad: 93
Cost between Pune and Gurgaon: 
6

Cost between Hydrabad and Gurgaon: : 

Optimal Railway Connections:
------------------------------------------
From City	To City		Cost
------------------------------------------
Noida	--->	Pune	= 43
Noida	--->	Hydrabad	= 56
Pune	--->	Gurgaon	= 6
------------------------------------------
Total Minimum Cost to Connect All Cities = 105


=== Code Execution Successful ===


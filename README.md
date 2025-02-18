## 🌳 **Spanning Trees with Two Criteria**

### 📖 Problem Overview
**"Spanning Trees with Two Criteria"** is an algorithmic problem that involves finding an optimal spanning tree in an **undirected connected graph** \( G(V, E) \). Each edge \( e \) has an associated **profit** \( p(e) \) and **weight** \( w(e) \). The goal is to construct a spanning tree \( T \) that maximizes the ratio:

\[
\frac{\sum_{e \in T} p(e)}{\sum_{e \in T} w(e)}
\]

This problem requires a **combination of algorithmic techniques**, including **greedy algorithms** and **binary search**, to efficiently compute the spanning tree with the optimal ratio.

### 📥 Input Format
The program reads:
1. Two integers **N** (number of vertices) and **M** (number of edges).
2. **M** lines follow, each containing four integers:
   - \( u, v \) → The two endpoints of the edge.
   - \( p(e) \) → The profit of the edge.
   - \( w(e) \) → The weight of the edge.

### 📤 Output Format
The program outputs two integers representing the **total profit and weight** of the optimal spanning tree. These values are reduced to their simplest form using the **Greatest Common Divisor (GCD)**, ensuring that the output is always in the most compact representation:

\[
p(T) / \gcd(p(T), w(T)), \quad w(T) / \gcd(p(T), w(T))
\]

### 🛠 Solution Approach
- Construct a **Minimum Spanning Tree (MST)** using **Kruskal's** or **Prim's Algorithm**.
- Utilize **binary search** on the ratio to find the maximum possible value.
- Employ **Greedy techniques** to optimize the spanning tree selection.



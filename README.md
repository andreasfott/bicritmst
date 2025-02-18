# bicritmst
"Spanning Trees with Two Criteria" is an algorithmic problem that involves finding an optimal spanning tree in an undirected connected graph 
𝐺
(
𝑉
,
𝐸
)
G(V,E). Each edge 
𝑒
e has an associated profit 
𝑝
(
𝑒
)
p(e) and weight 
𝑤
(
𝑒
)
w(e). The goal is to construct a spanning tree 
𝑇
T that maximizes the ratio:

∑
𝑒
∈
𝑇
𝑝
(
𝑒
)
∑
𝑒
∈
𝑇
𝑤
(
𝑒
)
∑ 
e∈T
​
 w(e)
∑ 
e∈T
​
 p(e)
​
 
This problem requires a combination of algorithmic techniques, including greedy algorithms and binary search, to efficiently compute the spanning tree with the optimal ratio.

The program reads:

N (number of vertices) and M (number of edges).
M lines describing each edge with four integers: 
𝑢
,
𝑣
,
𝑝
,
𝑤
u,v,p,w (endpoints, profit, and weight).
The output consists of two integers representing the total profit and weight of the spanning tree, reduced to their simplest form using the Greatest Common Divisor (GCD).

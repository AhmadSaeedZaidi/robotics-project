so if we have 2 position vectors, Po, and P1
and a distance vector D1 between then
we can define:

### **P1 = P0 + D1**

now if we apply a linear rotation matrix on d1, we can rotate p1 as well
and we can generalize our other position vector P2 as well, and so on.

$$
P_i = P_{i-1} + d_i + \text{rotate} \left( D_i, P_{i-1}, \sum_{k=0}^{i} \alpha_k \right)
$$

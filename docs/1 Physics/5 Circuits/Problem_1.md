# Problem 1
# **Problem 1: Equivalent Resistance Using Graph Theory**  

## **Motivation**  
Calculating equivalent resistance in electrical circuits can be complex for large networks. Using **graph theory**, we can model circuits as graphs where:  
- **Nodes** represent junctions.  
- **Edges** represent resistors (weights = resistance values).  

This method simplifies circuit analysis and enables automated calculations.  

---

## **Theory**  

### **Series and Parallel Resistance**  
- **Series:** \( R_{\text{eq}} = R_1 + R_2 + ... + R_n \)  
- **Parallel:** \( \frac{1}{R_{\text{eq}}} = \frac{1}{R_1} + \frac{1}{R_2} + ... + \frac{1}{R_n} \)  

### **Graph-Based Approach**  
1. **Build Graph:** Represent resistors as weighted edges.  
2. **Simplify Series Connections:** Merge nodes with two connections.  
3. **Simplify Parallel Connections:** Replace multiple edges between two nodes with their equivalent resistance.  
4. **Repeat Until One Resistance Remains.**  
![alt text](<image (1).png>)
## **Example Cases**  

| Circuit Type | Given Resistors | Equivalent Resistance |
|-------------|----------------|-----------------------|
| **Series** | 4Ω, 6Ω | 10Ω |
| **Parallel** | 4Ω, 6Ω | 2.4Ω |
| **Complex** | Mixed | Computed iteratively |

---

## **Conclusion**  
Using **graph theory**, we can systematically compute **equivalent resistance** in complex circuits, making circuit analysis more efficient and scalable. 🚀

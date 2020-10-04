# Neural-Network-XOR
Implement a Neural Network learning XOR gate in your favourite languages !

# File architecture
To avoid problems, follow this architecture :
```
<root>
  |_ python
      |_ <username>
          |_ my file.py
          |_ network.py
  |_ java
      |_ <username>
          |_ Main.java
          |_ Test.java
``` 

To increase lisibility, I recommend to create only **ONE FILE**.
For instance, `main.py` should contains all the code needed to run the project.

# XOR gate 
<img align="right" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/3_gate_XOR.svg">
An XOR gate (sometimes referred to by its extended name, Exclusive OR gate) is a **digital logic gate** with two or more inputs and one output that performs exclusive disjunction. The output of an XOR gate is true only when exactly one of its inputs is true. If both of an XOR gate's inputs are false, or if both of its inputs are true, then the output of the XOR gate is false.
<br/>
If an XOR gate has more than two inputs, then its behavior depends on its implementation. In the vast majority of cases, an XOR gate will output true if an odd number of its inputs is true.
<br/>

    Logical Proof of XOR

<table>
  <tr>
    <th>A</th>
    <th>B</th> 
    <th>A + B</th>
    <th>A'</th>
    <th>B'</th> 
    <th>A' + B'</th>
    <th>A ⊕ B = (A+B).(A'+B')</th>
  </tr>
  
<tr><td>0</td><td>0</td><td>0</td><td>1</td><td>1</td><td>1</td><td>0</td>
<tr>
  
 <tr><td>0</td><td>1</td><td>1</td><td>1</td><td>0</td><td>1</td><td>1</td>
<tr>
  
 <tr><td>1</td><td>0</td><td>1</td><td>0</td><td>1</td><td>1</td><td>1</td>
<tr>
  
<tr><td>1</td><td>1</td><td>1</td><td>0</td><td>0</td><td>0</td><td>0</td>
<tr>
  
</table>


In this table,
 - **A + B** represent **OR** operation between A and B
 - A' and B'represent A & B compliment respectively
 - dot(**.**) represent **AND** operation
 
### Significance of XOR in Neural Network
Gates are the building blocks of **Perceptron**. XOR is a **classification problem** and one for which the expected outputs are known in advance. It is therefore appropriate to use a supervised learning approach. The **XOR gate** consists of an **OR gate**, **NAND gate** and an **AND gate**. This means we need to combine two perceptrons.

# Power System Flow Analysis with Newton-Raphson Method (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab Code Implementation)

2.1 Overview of Power System Flow Calculation
The development of power system flow calculation initially relied on manual calculations. Later, to meet the growing needs of the power system, AC calculation stations were introduced. With the advent of electronic digital computers in 1956, Ward and others developed practical computer programs for flow calculations. This provided a powerful computational tool for the increasingly complex large-scale power systems. Over decades of development, power system flow calculation has become highly mature. The forms of power system flow calculation can be categorized into offline and online methods. The former is primarily used for power system planning and design, as well as determining system operation modes; the latter is employed for real-time monitoring and control of operational systems. Both offline and online flow calculations share the same principles: they require (1) reliable and convergent calculation methods; (2) minimal computer memory usage; (3) high computational speed; (4) good user interface for ease of use.
2.2 Newton-Raphson Method for Flow Calculation
2.2.1 Node Voltage Equation
The power network equation refers to a mathematical equation set that encapsulates the relevant parameters and variables of a network, reflecting its performance. It is not difficult to imagine that equations such as node voltage equations, loop current equations, and cutset voltage equations are included in this category. However, due to the fact that cutset voltage equations are not commonly used in power system calculations, it is generally advisable to use either node voltage equations or loop current equations. Nevertheless, measuring and collecting current parameters in a system can often be challenging, and since there are many grounded branches in the equivalent network of an electrical system, the number of equations for node voltage is relatively small. Moreover, when the structure of the network changes or transformer ratios change, the modification coefficients are conveniently adjusted, making the node voltage equations significantly advantageous.
2.2.2 Node Impedance Matrix
The node impedance matrix and the node impedance matrix are both square matrices with the same order as the number of nodes n in the network, except for the reference node. The reason we often use the node impedance matrix in power flow calculations is that it is a sparse matrix, with each row containing non-zero elements equal to the number of ungrounded branches connected to the node. Since the number of zeros between nodes i and j is equal to 0 when there is no direct connection between them, which is very common in real power systems, using the node impedance matrix facilitates modifications to the system structure.
2.2.3 Non-Standard Ratio Transformer Equational Circuit
For the equivalent circuit model of transformers, there are edit type equivalent circuit models and T-type equivalent transformer models. However, neither of these can fully represent the actual voltage transformation function of a transformer. It is necessary to convert all parameters and variables into the same voltage level. However, the equivalent transformer model can effectively represent the voltage transformation function of a transformer, and it is also the transformer model used in computer-based power system analysis. Although this model does not exclude manual calculations.
Firstly, as shown in Figure 3-2-3(a), the impedance or excitation branch of the transformer can be omitted, and a circuit representing a double-winding transformer can be represented by an impedance in series with an ideal transformer. The ideal transformer is just a parameter, namely the ratio. Now, let's assume that the transformer impedance is calculated according to the actual ratio to the low side as an example, and derive the equivalent transformer equational circuit.
Editor
The impedance of the transformer is normalized to the equivalent model at the low-voltage side, and the power flowing into and out of an ideal transformer are equal:
For the detailed articles, refer to Part Four:
Editor
3 Simulation Results ​Editing
Editor
Editor
Editor
4. Matlab code and article explanation: This article only displays a part of the code, all codes can be found in:
Editor
Editor
​  

## Images

![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](01.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](02.gif)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](03.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](04.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](05.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](06.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](07.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](08.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](09.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](10.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](11.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](12.png)
![Power System Flow Analysis [Newton-Raphson Method] (4 nodes, 5 nodes, 6 nodes, 9 nodes) (Matlab code implementation)](13.png)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->

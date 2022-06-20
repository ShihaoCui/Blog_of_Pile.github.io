## Pile length estimation based on the guided wave model-based dispersion analysis using two signals 

This blog is to show the process of pile length estimation using two signals, which can be collected on the lateral side or the top surface of the pile under investigation, based on the guided wave model. 

The process can be divided into five steps.

Two examples are given as follows:

1. Data acquisition. Two signals can be collected on the lateral side of the top surface.
2. Phase difference of the two collected signals.
3. Dispersion relation-building based on the guided wave model.
4. The dispersion analysis diagram (**DAD**) plotting.
5. Pile length estimation based on the parameter obtained from the **DAD**.

The following will show the above process in two cases: **Case 1:** The pile length estimation using two signals collected on the lateral side; **Case 2:** The pile length estimation using two signals collected on the top surface.

### **Case 1:** The pile length estimation using two signals collected on the lateral side.
![image](https://user-images.githubusercontent.com/50115572/174656935-b73d9901-7c7f-4d92-b8e4-5a07fe5501da.png)

The schematic diagram of the sensor position, in this case, is shown in the above figure. The pile length estimation process, in this case, is shown as follows.

- **Step 1:** Data acquisition on the lateral side.

The data is collected on a pile with Length L = 15 m; **Sensor 1** is collected on the position $L_1$; **Sensor 2** is collected on the position $L_2$. There, $L_1 = 14.5m$, $L_2 = 14.2m$, and the difference between two sensors $\Delta L = 0.3m$. The two signals are shown in the following figure.

![image](https://user-images.githubusercontent.com/50115572/174653822-fbad5e1b-7863-46e2-a908-3c458bea7235.png)

- **Step 2:** Phase difference of the lateral-side two-signal pair.

The two signals can be converted into the frequency domain $R_1$ and $R_2$, respectively. The phase difference of the two signals can be calculated as,

$\Delta \Phi$ = $Im(log(R_1)-log(R_2))$

- **Step 3:** The dispersion relation determined by the guided wave model.

The physical parameters: Young's modulus **E**, the density **$\rho$**, the Poisson's ratio **$\nu$** and the radius **r** of the test pile are shown in the following. 

```Markdown
E = 18773059558.275; # Young’s modulus
$\rho$ = 2200;# density
$\nu$ = 0.25001 # poisson's ratio
r = 0.5 # the radius 
```
The dispersion relation between the frequency $f$ and the wavenumber k, i.e., $D(f,k)=0$ can be obtained by the guided wave model. 

- **Step 4:** Dispersion Analysis Diagram ($DAD$).

According to the phase difference in **Step 2** and the dispersion relation in **Step 3**, the DAD can be plotted, which is shown in the following figure.

![image](https://user-images.githubusercontent.com/50115572/174660505-c09a2873-b27e-4f2b-a6e2-37871e35832d.png)

- **Step 5:** The pile length estimation based on DAD.

The cycle period **P_c** and the wiggle period **P_w** can be obtained from the DAD. 

There is $L_1 = (R_p+1+\sqrt{R_p^2+1})/2*\Delta L$ , 

where $R_p  = P_c/P_w$

In this case, $P_w = 0.38$, $P_c = 17.61$, therefore the estimated $L_1 = 14.06$, and the estimation error is $3.1$%.

### **Case 2:** The pile length estimation using two signals collected on the top surface.

![image](https://user-images.githubusercontent.com/50115572/174656971-7094842f-452a-4996-bb0f-cc46264f9041.png)

The schematic diagram of the sensor position, in this case, is shown in the above figure. The pile length estimation process, in this case, is shown as follows.

- **Step 1:** Data acqusition on the top surface.

The data is collected on a pile with Length L = 15 m; **Sensor 3** is collected on the position $r_1$; **Sensor 4** is collected on the position $r_2$. There, $r_1 = 0.2 m$, $r_2 = 0.4m$. The two signals are shown in the following figure.

![image](https://user-images.githubusercontent.com/50115572/174662194-293e6a50-7d80-4395-bee1-ae43b5f772e9.png)

- **Step 2:** Phase difference of the top-surface two-signal pair.

The two signals can be converted into the frequency domain $R_3$ and $R_4$, respectively. The phase difference of the two signals can be calculated as,

$\Delta \Phi$ = $Im(log(R_3)-log(R_4))$

- **Step 3:** The dispersion relation determined by guided wave model.

It is the same with the dispersion relation in the **Step 3** in **Case 1**.

- **Step 4:** Dispersion Analysis Diagram ($DAD$).

According to the phase difference in **Step 2** and the dispersion relation in **Step 3**, the DAD can be plotted, which is shown in the following figure.

![image](https://user-images.githubusercontent.com/50115572/174662394-b13ed63e-beff-4255-8ab0-0a446a67c24d.png)


- **Step 5:** The pile length estimation based on DAD.

The wiggle period $P_w$ _t can be obtained from the DAD. 

There is 

$L= 2*\pi/P_w$ _t , 

In this case, $P_wt = 0.401$, therefore the estimated $L = 15.67 m$, and the estimation error is $4.4$%.





You can use the [editor on GitHub](https://github.com/ShihaoCui/Blog_of_Pile.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

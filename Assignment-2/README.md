# Assignment - 2

## 1. Use exactly the same values for all variables as used in the class

![BP_A2](https://user-images.githubusercontent.com/6522987/135614643-31d850bf-3610-4fce-beba-777a7c685cc8.png)


## 2. Error graphs for different learning rates (0.1, 0.2, 0.5, 0.8, 1.0, 2.0)

![Different_LRs](https://user-images.githubusercontent.com/6522987/135614909-2bc8e980-0de5-4150-af72-8446c943ad28.png)


## 3. Steps involved in Backpropagation

  #### Step 1 - Network inputs, target and weight initialization 
  
  `i1 = 0.05`, `i2 = 0.1`
  
  `a_o1 = 0.01`, `a_o2 = 0.99`
  
  `W1 = 0.15` , `W2 = 0.2` , `W3 = 0.25` , `W4 = 0.3` , `W5 = 0.4` , `W6 = 0.45` , `W7 = 0.5` , `W8 = 0.55`
  

#### Network Diagram

![image](https://user-images.githubusercontent.com/6522987/135616790-b7c714d3-f873-4773-b2f4-1cee0ec8e4d6.png)

#### Step 2 - Feed Forward Operation 
  
Inputs to the neurons are passed through the layer, until it arrives at the outputs and there is no feedback layer. In the above diagram we have 2 inputs, sigmoid is the activation function used.

![image](https://user-images.githubusercontent.com/6522987/135621028-41ee2462-b339-443b-9ec8-66b8fde3753b.png)


  
  
  
  
    h1 = w1*i1+w2*i2
    h2 = w3*i1+w4*i2	
    a_h1 = 𝝈(h1)	1/1+exp(-h1)	
    a_h2 = 𝝈(h2)		
    o1 = w5*a_h1+ w6*a_h2		
    o2 = w7*a_h1 + w8*a_h2		
    a_o1 = 𝝈(o1)		
    a_o2 = 𝝈(o2)		
    E1 = (1/2) * (t1-a_o1)^2 		
    E1 = (1/2) * (t2-a_o2)^2 		
    E_Total = E1 + E2		

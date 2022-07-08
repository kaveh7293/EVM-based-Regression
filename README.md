# Overview

In conventional regression (e.g., simple linear regression), there are some simplifying assumptions. For example, consider the following single-input single-output model:
   
 <p align="center"><img src="https://github.com/kaveh7293/EVM-based-Regression/blob/main/Screenshot%202022-07-08%20144535.png" width="150"></p>
 where Y is the random variable corresponding to the measurements, g(.) is the function denoting the model predictions, x is the perfectly-known input,θ is the parameter vector requiring estimation , and ϵ is the random measurement noise. If it is assumed that the randon noises for different experimental conditions are all normally distributed with the same variance (i.e., they are identically distributed), and also they are all indepenent random variables, the corresponding objective function can be obtained based on maximum likelihood arguments:
 
 <p align="center"><img src="https://github.com/kaveh7293/EVM-based-Regression/blob/main/Screenshot%202022-06-26%20143650.png" width="220"></p>
In obtaining the above objective function, we assumed that measurements corresponding to the inputs are perfectly known (i.e., can be measured without error). However, in situations where inputs uncertainites are relatively large, parameter estimates obtained from minimizing the above objective function is bias. In this situation, a more-accurate objective function can be obtained using maximum-likelihood arguments based on the EVM equations. In this situation, equation (1) should be extended to accounts for errors in uncertain inputs:

<p align="center"><img src="https://github.com/kaveh7293/EVM-based-Regression/blob/main/Screenshot%202022-07-08%20144957.png"  width="200"></p>
                                                                     
where ϵy and ϵu are the random measurement noises for the model outputs and uncertain inputs, respectively. Likewise, using a maximum likelihood argument, the EVM-based objective function can be obtained:

<p align="center"><img src="https://github.com/kaveh7293/EVM-based-Regression/blob/main/Screenshot%202022-07-08%20142541.png"  width="320"></p>


 

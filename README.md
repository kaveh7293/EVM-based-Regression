# Overview

In conventional regression (e.g., simple linear regression), there are some simplifying assumptions. For example, consider the following single-input single-output model:
   
                                                                    Y=g(x,θ)+ϵ  (1)
 where Y is the random variable corresponding to the measurements, g(.) is the function denoting the model predictions, x is the perfectly-known input,θ is the parameter vector requiring estimation , and ϵ is the random measurement noise. If it is assumed that the randon noises for different experimental conditions are all normally distributed with the same variance (i.e., they are identically distributed), and also they are all indepenent random variables, the corresponding objective function can be obtained based on maximum likelihood arguments:
 
 ![](https://github.com/kaveh7293/EVM-based-Regression/blob/main/Screenshot%202022-06-26%20143650.png)

In obtaining the above objective function, we assumed that measurements corresponding to the inputs are perfectly known (i.e., can be measured without error). However, in situations where inputs uncertainites are relatively large, parameter estimates obtained from minimizing the above objective function is bias. In this situation, a more-accurate objective function can be obtained using maximum-likelihood arguments based on the EVM equations. In this situation, equation (1) should be extended to accounts for errors in uncertain inputs:

                                                                Y=g(x,u,θ)+ϵy    (3)
                                                                     U=u+ϵu      (4)
                                                                     
where ϵy and ϵu are the random measurement noises for the model outputs and uncertain inputs, respectively.
 

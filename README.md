# Overview

In conventional regression (e.g., simple linear regression), there are some simplifying assumptions. For example, consider the following model:
   
                                                                    Y=g(x,θ)+ϵ
 where Y is the random variable corresponding to the measurements, g(.) is the function denoting the model predictions, x is the perfectly-known input,θ is the parameter vector requiring estimation , and ϵ is the random measurement noise. If it is assumed that the randon noises for different experimental conditions are all normally distributed with the same variance (i.e., they are identically distributed), and also they are all indepenent random variables, the corresponding objective function can be obtained based on maximum likelihood arguments:
 
 ![](https://github.com/kaveh7293/EVM-based-Regression/blob/main/Screenshot%202022-06-26%20143650.jpg)

# Multi-model Approach to Image Classification for APTOS Dataset  
Here I observed experimental situations to experience different approaches.
https://www.kaggle.com/c/aptos2019-blindness-detection  

* STEP-1:  
Used kernels(APTOS-01a,01b,01c,01d jupyter notebooks) for train models
+The data set was prepared and determined.  
+ML algorithm was trained (effnet)  
https://ai.googleblog.com/2019/05/efficientnet-improving-accuracy-and.html  
https://arxiv.org/pdf/1905.11946.pdf  
  
* STEP-2:  
Inferance(APTOS-OOK jupyter notebooks)  
TARGET:::Images have five possible ratings, 0,1,2,3,4.  

Predicted was performed with the trained algorithm.  
  
  ![View](https://github.com/semskurto/APTOS/blob/master/aptosReadme.png)
  
Result:  
Stability was increased by replacing batch normalization with group normalization previously in Efficientnet.  
https://arxiv.org/pdf/1803.08494.pdf  

Training results are not stable at the desired level.  
A new methodology is currently being studied to reduce the error rate.  


[NEW EXPERIMENT] another methodology ===> [aptos_02a ,aptos_02b, aptos_ook(2) jupyter notebooks]

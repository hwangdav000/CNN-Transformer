# CNN-Transformer
This was the capstone project for my Master's Degree at the UMN, Twin Cities
<br>
Please read my paper here for more information:


[CNN Transformer (David Hwang)](DH_CNN_Transformer_Hybrid.pdf)


In this project I have implemented a Hybrid CNN-Transformer using spatial-spectral unification on 
satellites Sentinel-2 and Landsat-8 for crop classification. This is based on the paper from Zhengtao et al. 

(https://ieeexplore-ieee-org.ezp2.lib.umn.edu/document/8999620)


<br>
Study region is in Sacramento Valley, California.
<br>
![cropland](https://github.com/hwangdav000/CNN-Transformer/assets/29682356/9860474d-b211-42d5-8a41-98d69d6df35f)
<br>
I gathered data from Sentinel2 and Landsat 8 from google earth and then I preprocessed 
the data in google colab. I then used various models like RF-200, SVM-RBF, CNN-LSTM, Multi-Temporal CNN, CNN-Transformer
to assess how accurate it is in classifying crop data.
This spatial spectral data is then combined into: 
<br>

Result1 

![image](https://github.com/hwangdav000/CNN-Transformer/assets/29682356/dd178111-236b-46af-bf2f-4b61fe20a879)

Result2

![image](https://github.com/hwangdav000/CNN-Transformer/assets/29682356/90e48b39-7c74-43df-85cc-838c3ff2038e)

I found that RF-200 performed the best and that the classical machine learning models outperformed
the deep learning models. I did find that the CNN-Transformer did outperform the other deep learning 
models that I tested. There are some differences in my approach that I could have taken which
I outline in my paper to boost the accuracy of the deep learning models. 




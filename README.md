<p align="center">
  <a href="https://cognopy.vercel.app">
    <img src="https://github.com/xiaowuc2/Covid-19-Prediction-A-Machine-Learning-Approach/blob/main/Images/rotating-globe-slow.gif" alt="Logo" width="200" length="200" >
  </a>
</p>

<p><pre align="center">
<strong>Covid-19 Prediction: A Machine Learning Approach / <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">​Code​</a> / <a href="https://www.youtube.com/channel/UCX7oe66V8zyFpAJyMfPL9VA">​Research Paper​</a></pre></p></strong>

### Abstract

Coronavirus disease (COVID-19) is an infectious disease causedby the SARS-CoV-2 virus.In most cases, it is the largest category for anRNA  virus.  Authorities  in  222  countries  and  territories  have  reportedabout  244.2  million  Covid-19  cases  and  5  million  deaths  since  Chinareported its first cases to the World Health Organization (WHO) in De-cember  2019.  Our  proposed  classifier  assists  in  the  early  diagnosis  of Covid-19. There are many well established model which can give moreaccurate results based on X-ray or CT scans, but they are convoluted andabstruse for normal person. We’ve developed a more simpler model with‘`Yes`’ and ‘`No`’ types  on  question,  where our huge dataset are trained with these features : ‘`BreathingProblem`’, ‘`Fever`’, ‘`Dry Cough`’, ‘`Sore throat`’, ‘`Running Nose`’, ‘`Asthma`’, ‘`Chronic  Lung  Disease`’, ‘`Headache`’, ‘`Heart  Disease`’, ‘`Diabetes`’, ‘`HyperTension`’, ‘`Fatigue`’ and eight more. Based on these data the model willpredict result in a probabilistic view.

Dataset:
COVID-> 140 X-ray images
Normal-> 140 X-ray images
Pneumonia-> 140 X-ray images

How to use:
1-Run "preprocess_images.py" to preprocess images done by resizing, normalization, adaptive histogram equalization

2-Run "extract_features.py" to create three feature pools for covid or normal or pneumonia datasets

3-Run "evaluate_features.py" to evaluate extracted features

4-Run "train_model.py" to train and then evaluate model  

Test results:

	        Precision	 Sensitivity	 F-score	 Support
COVOD-19	   96%	           100%	           0.98	           25
Normal	           88%	           100%	           0.94	           31
Pneumonia	   100%	           82%	           0.91	           28

# Numerical model on banfkfull discharge and channel geometry

Numerical model that describes long-term spatiotemporal evolution of bankfull characteristics of an alluvial meandering river


## Model description

Here, two numerical models that are presented in two research papers submitted to Journal of Geophysical Research in December 2018. 
The models describe reach-characteristics spatiotemporal co-evolution of bankfull characteristics (i.e. bankfull dishcarge, bankfull width, bankfull depth and down-channel slope) are provided herein. 

The model is written with Python 2.7. However, it is developed in such a way that it can also be run with PyPy, which is a faster alternative implementation of Python. PyPy can be downloaded at https://pypy.org/. 


#### Part 1: Base run

[Here](./Part1_Base_run) the model, model products as well as a model-input flow duration curve are provided. 
The model is implemented for the case of Trinity River near Romayor, TX, USA to demonstrate fundamental behavior of the model. 


#### Part 2: Alteration of flow duration curve

[Here](./Part2_FDC_alteration) the model, its products as well as model-input flow duration curves are provided. 
The model is implemented for the case of Minnesota River near Jordan, MN, USA to demonstrate the potential application of the model. 
It is designed to examine the effect of the alteration in the flow duration curve on the bankfull channel characteristics. 
Since the analysis focuses on rapid channel cross-section (width and depth) deformation, longitudinal channel slope is specified and fixed. 


## Related papers

Naito, K., & Parker, G. (submitted). Can Bankfull Discharge and Bankfull Channel Characteristics of an Alluvial River be Co-specified from the Flow Duration Curve? Part 2: Application to the Minnesota River, USA. Journal of Geophysical Research: Earth Surface. Submitted in December 2018.

Naito, K., & Parker, G. (submitted). Can Bankfull Discharge and Bankfull Channel Characteristics of an Alluvial River be Co-specified from the Flow Duration Curve? Part 1: Framework for Analysis. Journal of Geophysical Research: Earth Surface. Submitted in December 2018.

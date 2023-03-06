# 4DFM
4D Facial Expression Diffusion Model

## 1. Dataset
We test our method on two commonly used facial expression datasets, [**CoMA**](https://coma.is.tue.mpg.de/) and [**BU-4DFE**](http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html).

## 2. Model architecture


<img  src="model.jpg"  />

## 3. Video results
Each video will repeat three times.

### 3.1 Label control

Examples


 <img src="results/angry.gif" width="50%" height="50%" /> <img src="results/eyebrow.gif" />  <img src="results/mouth_extreme.gif"  /> <img src="results/disgust.gif" />  <img src="results/mouth_open.gif"  /> <img src="results/lips_up.gif" /> 


### 3.2 Text control

Text to expression examples:

<center class="half">
 <img src="results/sad_text.gif" height="270" />
 <img src="results/bareteeth_text.gif" height="270" />
 <img src="results/angry_mouth_down.gif" height="270" />
</center>


### 3.3 Sequence filling

#### Filling from the beginning.
 <img src="results/ffb_1.gif" height="270" />  <img src="results/ffb_2.gif" height="270" />

#### Filling in the middle.
 <img src="results/fim_1.gif" height="270" />  <img src="results/fim_2.gif" height="270" />
 
 
#### Filling from the end.
 <img src="results/ffe_1.gif" height="270" />  <img src="results/ffe_2.gif" height="270" />

## 4. Code
The code will be made available very soon!

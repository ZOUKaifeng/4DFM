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


 <img src="results/angry.gif" width="30%" height="30%" /> <img src="results/eyebrow.gif" width="30%" height="30%"  />  <img src="results/mouth_extreme.gif"  width="30%" height="30%"  /> <img src="results/disgust.gif" width="30%" height="30%"  />  <img src="results/mouth_open.gif"  width="30%" height="30%"  /> <img src="results/lips_up.gif"  width="30%" height="30%" /> 


### 3.2 Text control

Text to expression examples:


 <img src="results/sad_text.gif"  width="30%" height="30%" />     <img src="results/bareteeth_text.gif" width="30%" height="30%"  /> <img src="results/angry_mouth_down.gif"  width="30%" height="30%"  />
 
  <img src="results/text_eyebrow.gif"  width="22.5%" height="22.5%" />  <img src="results/text_mouth_down.gif"  width="30%" height="30%" />



### 3.3 Sequence filling

#### Filling from the beginning.
 <img src="results/ffb_1.gif" width="30%" height="30%"  />  <img src="results/ffb_2.gif"  width="30%" height="30%"  />

#### Filling in the middle.
 <img src="results/fim_1.gif"  width="30%" height="30%" />  <img src="results/fim_2.gif"  width="30%" height="30%"  />
 
 
#### Filling from the end.
 <img src="results/ffe_1.gif"  width="30%" height="30%"  />  <img src="results/ffe_2.gif"  width="30%" height="30%"  />


### 3.3 Comparison
#### Label control
"high smile"


 <img src="results/comp_high_smile.gif"  width="50%" height="50%"  /> 
 
 <img src="results/comp_cheeks_in.gif"  width="50%" height="50%"  /> 
 
 <img src="results/comp_mouth_open.gif"  width="50%" height="50%"  /> 
 
 #### Text control
 
 <img src="results/text_comp_1.gif"  width="40%" height="40%"  /> 
 
 <img src="results/text_comp_2.gif"  width="40%" height="40%"  /> 
 
 
## 4. Code
The code will be made available very soon!

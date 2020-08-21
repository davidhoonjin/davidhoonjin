---
layout: post
title: <font size="7em"> <font style="color:Tomato;">Current Projects </font></font>
date: 2020-02-03
---
<br>
●<font size="6em"><b><u>BCI As an Emotional Assistant :</u></b></font><font size="6em"><b>A system that classifies the user's emotional state, and give feedback when needed.</b></font> <br>(Feb,2020 ~ )<br>
●<font size="6em"><b><u>Sensing Actuator (Silicon Finger with PVDF sensor):</u></b></font><font size="6em"><b>Automated soft actuator</b></font> <br>(Mar,2020 ~)<br>
<hr style="height:3px">


<!-- <p style="background-color:DodgerBlue;"><font size="2em">.</font></p>-->

<br>
<br>
<h1 style="background-color:LightCyan; text-align:center; color:black;"><font size="6em"><b>
 BCI As an Emotional Assistant</b></font></h1>
 <div style="float:right;">
<h><font size="5em">Computational Neuro Engineering(CoNE) LAB</font><br>
<br></h></div><br>

<br>
A system that measures bio-signals(EEG, PPG, GSR) to classify the user's emotional state. If it's classified below certain threshold, give a proper feedback to bring the user's emotion back to the desired status.
<br><br>
<img src="/images/fulls/09.jpg" class="image-img" width="370" height="350">
<img src="/images/fulls/03.jpg" class="image-img" width="300"> <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Accuracy over 80%
<font size="5em">
Currently accuracy of emotion classification is over 85%, and still working on improving the model. On-line experiment is planned to be held on September.
<br><br>
<br>

<b>Throughout the Project...</b> <br>
Developed Matlab function :<br>
1. <a href="/images/GSR_feature.m">Click here to download GSR feature extraction Matlab code</a><br><br>
Future project idea : &nbsp;&nbsp; "Removing Ocular(and emg) Artifact from EEG with Machine Learning"<br>
-> Motivation - Previous thesis only used ICA-based feature. If PCA and Regression based features are considered, accuracy can be improved.
</font>
<hr style="height:3px">

<br>
<br>
<h1 style="background-color:LightCyan; text-align:center; color:black;"><font size="6em"><b>
 Sensing Actuator (Silicon Finger with PVDF sensor)</b></font></h1>
<div style="float:right;"><font size="5em">
 Nanoelectronics Device LAB(NDL)</font></div>
 <br>
 <br>

<div class="w3-content" style="max-width:400px">
  <img class="mySlides" src="/images/fingers/finger1.jpg" style="width:100%">
  <img class="mySlides" src="/images/fingers/finger2.jpg" style="width:100%">
  <img class="mySlides" src="/images/fingers/finger3.jpg" style="width:100%">
  <img class="mySlides" src="/images/fingers/finger4.jpg" style="width:100%">
</div>

<script>
var slideIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > x.length) {slideIndex = 1}
  x[slideIndex-1].style.display = "block";
  setTimeout(carousel, 500);
}
</script>
 ↑ First model without PVDF sensor<br>
 <img src="/images/fingers/finger5.jpg" class="image-img" width="300"> <br>
 ↑ mold made with the 3D printer
<br>
<font size="5em">
Human-Friendly Flexible Finger can be advantageous in many fields that robots interacts with human body. When applied to Medical Robots or Medical catheters, minimum incision with soft movement will be possible.</font>
<br>
<hr style="height:3px">
<br>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">

<head>

<meta charset="utf-8">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="generator" content="pandoc" />

<meta name="author" content="SHILADITYA BOSE" />

<div class="container-fluid main-container">

<div id="header">
<h1 class="title">OUTLINE OF THE PROJECT BASED ON VEHICLE-INSURANCE-CLAIM-FRAUD-DETECTION-USING-DIFFERENT-CLASSIFICATION-TECHNIQUES</h1>
<h4 class="author"><em>Shiladitya Bose</em></h4>
<h4 class="date"><em><ol start="10" style="list-style-type: decimal">
<li>May 2022</li>
</ol></em></h4>
</div>


<div id="synopsis" class="section level2">
<h2>Synopsis</h2>
<p><b> 𝐈𝐍𝐒𝐔𝐑𝐀𝐍𝐂𝐄 𝐅𝐑𝐀𝐔𝐃</b> has accompanied insurance since its inception, but the manner in which these practices and their methods of operation have evolved over time, and the volume and frequency of insurance fraud incidents have recently increased. Vehicle insurance fraud involves conspiring to make false or exaggerated claims involving property damage or personal injuries following an accident. Some common examples include staged accidents where fraudsters deliberately “arrange” for accidents to occur; the use of phantom passengers, where people who were not even at the scene of the accident claim to have suffered grievous injury, and making false personal injury claims where personal injuries are grossly exaggerated.</p>
</div>
<div id="PROJECT OBJECTIVE" class="section level2">
<h2>PROJECT-OBJECTIVE</h2>
<p>Our <b>𝐎𝐁𝐉𝐄𝐂𝐓𝐈𝐕𝐄</b> of this project is focusing on detecting vehicle fraud by using machine learning algorithms, and also the final analysis and conclusion based on performance of the different <b>𝐂𝐋𝐀𝐒𝐒𝐈𝐅𝐈𝐂𝐀𝐓𝐈𝐎𝐍 𝐀𝐋𝐆𝐎𝐑𝐈𝐓𝐇𝐌𝐒</b> like <b>𝐋𝐈𝐍𝐄𝐀𝐑 𝐃𝐈𝐒𝐂𝐑𝐈𝐌𝐈𝐍𝐀𝐍𝐓 𝐀𝐍𝐀𝐋𝐘𝐒𝐈𝐒(LDA)</b>, <b>𝐑𝐀𝐍𝐃𝐎𝐌 𝐅𝐎𝐑𝐄𝐒𝐓</b>, <b>𝐃𝐄𝐂𝐈𝐒𝐈𝐎𝐍 𝐓𝐑𝐄𝐄</b> and <b>LOGISTIC CLASSIFIER</b> in terms of greater accuracy in predicting the fraud.</p>
</div>

<div id="VARIABLE DESCRIPTIONS" class="section level3">
<h2>VARIABLE DESCRIPTIONS</h2>
<p>For our analysis, total <b>27</b> variables, where</p>
<li>the <b>RESPONSE VARIABLE(Y)</b> is <b>FraudFound_P</b> </li>
<p>and the <b>26 EXPLANATORY VARIABLES</b> are </p>
<li><b>WeekOfMonth</b></li> 
<li><b>WeekOfMonthClaimed</b></li>
<li><b>AccidentArea</b></li>
<li><b>Sex</b></li>
<li><b>MaritalStatus</b></li>
<li><b>Age</b></li>
<li><b>Fault</b></li>
<li><b>PolicyType</b></li>
<li><b>VehicleCategory</b></li>
<li><b>VehiclePrice</b></li>
<li><b>Deductible</b></li>
<li><b>DriverRating</b></li>
<li><b>Days_Policy_Accident</b></li>
<li><b>Days_Policy_Claim</b></li>
<li><b>PastNumberOfClaims</b></li>
<li><b>AgeOfVehicle</b></li>
<li><b>AgeOfPolicyHolder</b></li>
<li><b>PoliceReportFiled</b></li>
<li><b>WitnessPresent</b></li>
<li><b>AgentType</b></li>
<li><b>NumberOfSuppliments</b></li>
<li><b>AddressChange_Claim</b></li>
<li><b>NumberOfCars</b></li>
<li><b>Year</b></li>
<li><b>BasePolicy</b></li>
<li><b>ClaimSize</b></li>
</div>
<div id="CONCLUSION AT A GLANCE" class="section level3">
<h2>CONCLUSION AT A GLANCE</h2>
<p>After apply the classification methods i.e. <b>LOGISTIC</b>, <b>DECISION TREE</b>, <b>RANDOM FOREST</b> AND
<b>LINEAR DISCRIMNINANT CLASSIFIER</b> on the train data, we found that in terms of
<b>ACCURACY</b>, <b>RANDOM FOREST</b> is the <b>BEST</b> classifier for detection Insurance Claim Fraud with
<b>94.37</b> Accuracy</p>
<p>And in terms of <b>PRECISION</b>, also <b>RANDOM FOREST</b> is the <b>BEST</b> classifier for detection
Insurance Claim Fraud with <b>62.5</b> Precision with respect to other 3 classifiers.</p>
And from <b>AUC-SCORE</b>, using the <b>RANDOM FOREST</b> Classifier, we can see
<b>AUC</b> score is <b>0.7839</b>.</p>
<p>So, for our dataset and for our objective of detection in Insurance Claim
Fraud, <b>RANDOM FOREST</b> is the <b>BEST</b> Classifier.
</div>
</body>
</html>

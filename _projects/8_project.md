---
layout: page
title: Resonance search
description: A concise exploratory project to get acquainted with the ROOFit mechanism. The prime focus of this exploration was to look for  J/\(\psi\) resonance peak signals in the given data.
img: assets/img/jpsi_1.png
importance: 5
---

<hr>

##### Report(s)
A brief summary report of the school can be found <a href = "/assets/pdf/jennifer2_school_2021.pdf" title = "jennifer2_school_2021"> here</a>.

A copy of the report of the work can be found <a href = "/assets/pdf/jennifer2_work_2021.pdf" title = "jennifer2_work_2021"> here</a>.

The source code can be found <a href = "https://github.com/vchirag/jpsi/tree/main" title = "jpsi_analysis"> here</a>.  And the corresponding data used for analysis <a href = "https://github.com/vchirag/data_files/releases/tag/jpsi" title = "jpsi_data"> here</a>.


<hr>

##### Skills acquired
<ul>
	<li> Introduction to computational techniques in high energy physics.</li>
	<li> Big data handling with CERN ROOT.</li>
	<li> Fitting with ROOFit mechanism.</li>
</ul> 

<hr>

##### Summary
My task was first to join (I do not know what the standard term is) the Monte Carlo data spread across several different _.root_ files. This was done using the _TChain_ class of the ROOT software. The attached report shows the histograms for counts vs. mass and/or energy.

The next step was to use appropriate _cuts_. Individual cuts on mass and energy were guessed using the vague histograms obtained in the previous step. The code snippet is displayed in the attached report. As soon as the cuts were made, the data took the form of _Breit-Wigner_ resonance superposed on sort of a _linear_ background.


Next, to implement the RooFit mechanism, the following seeds were passed:

	1.	Background profile: _Chebyshev polynomials_
	2.	Signal profile: _Gaussian_
	3.	Binning: 75, SNR: 0.5


**Notes to myself**: 

	1. I wonder how one implements a _Voigtian distribution_. 
	2. Is the background similar to an _Argus_ distribution?

<hr>

##### Comments


Attending the school was enthralling as this was one of the first few instances when I got the motivation (and courage) to delve deep into abstract mathematics, field theories, and particle physics. The thrill and joy of pursuing such excellent subjects still excite me.

Apart from some statistical tools, the post-school project introduced me to several academic bureaucracies and how one gets things done within the literary world and the world itself- by being _polite_. I believe the results I obtained are incorrect, and I do not know how to check their accuracy.






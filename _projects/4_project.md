---
layout: page
title: Stellar Flares
description: A group project that investigated various numerical techniques to analyze Chandrayan-2 Orbiter's XSM data for finding potential solar flares.

img: assets/img/solar_flare_1.png
importance: 4
---

<hr>

##### Final Report

The shortlisting problem statement can be found <a href = "https://github.com/vchirag/KSP2022-selection" title = "krittika_problem_2022"> here</a>. And its corresponding solution <a href = "https://github.com/vchirag/krittika2022/tree/main/selection_problem_and_solution" title = "krittika_solution_2022"> here</a>.

The project's python environment can be found <a href = "https://github.com/vchirag/krittika2022/tree/main/project" title = "krittika_project_2022"> here</a>. And the extracted data used can be found <a href = "https://github.com/vchirag/data_files/releases/tag/xsm_solar_flare" title = "data"> here</a> (courtesy of Devansh Jain, IIT Bombay).

<hr>

##### Acquired Skills

<ul>
    <li> Writing clean code (possibly) and making an environment in python </li>
    <li> Physics of stellar flares </li>
    <li> Statistical techniques to increase the SNR ratio in the given dataset</li>
</ul>

<hr>

##### Summary


As with any analysis work, the data was cleaned and scoured manually for elementary flares. The term elementary flare mathematically represents a _convolution_ of two profiles- a _gaussian_ for the transient rise of activity and a _decaying exponential_ for the short decay of the flare activity.

The primary goal of the work was to detect, identify, and analyze any detected solar flare in the XSM data. To our dismay, we couldn't complete the analysis part in the natural period of the project.

The data was cleaned using a boxed car average method- which works surprisingly well for heavily fluctuating data.

This was followed by searching for all local minima and maxima in the data. Furthermore, the background data below a certain level was deleted.

Once through with this, the identified flares were separated from the primary data file. These were later fit for the elementary profile as described previously.

<hr>

##### Comments

As the project progressed, I became more curious about studying _dynamical systems_ and _self-ordered criticality_. Added to the bucket-list.(?)

Also, it becomes difficult to manage two independent projects simultaneously. Alas, we humans aren't good at multitasking.

+++
showonlyimage = false
draft = false
image = ""
date  = "2019-12-11"
title = "Robust (Point-wise) Optimal Adaptive Control"
+++

**Abstract:** Employing modern control Lyapunov methods with modern
adaptive control methods leads to an adaptive control system with
strong trajectory tracking performance with sub-optimality properties.
Concurrent learning adaptive elements provide the robustness needed to
handle large parameter variation. Extension of the method improves
robustness of safety margins to uncertainty when using control barrier
functions.
<!--more-->

This work represents our first attempt at merging modern nonlinear
control techniques with modern adaptive control techniques.  Doing so
leads to some interesting differences when compared to classical model
reference adaptive control.  In fact, the approach looks more like
earlier methods of adaptive control (from the 90's) that did not
include a model reference. However, with contemporary insights into how
to structure adaptive control methods, we are now able to say more
about the performance of these techniques.[^1]

The last decade and some change has also seen an increase in research
towards safety or safety constraint satisfaction during closed-loop
operation.  Barriers and control barrier functions arose from the
controls community's efforts. Since adaptive control adapts online
uncertain parameters to meet a target Lyapunov stability specification,
it is sensible to expect for adaptive control to integrate well with
control barrier functions.[^2] In fact, doing so significantly improves
performance of a system with a barrier constraint and uncertainty in
the dynamics.


[^1]: V. Azimi and P.A. Vela. "Performance Reference Adaptive Control: A Joint Quadratic Programming and Adaptive Control Framework." In _American Control Conference_, pp. 1827-1834, 2018.  [Abstract](https://ieeexplore.ieee.org/document/8431150).
[^2]: V. Azimi and P.A. Vela. "Robust Adaptive Quadratic Programming and Safety Performance of Nonlinear Systems with Unstructured Uncertainties." In _IEEE Conference on Decision and Control_, pp. 5536-5543, 2018.  [Abstract](https://ieeexplore.ieee.org/document/8619728).


# DrowsyEye-Detection

By having the points shown in the figure the EAR(Eye Aspect Ratio) is calculated and the EAR will be set as 0.25 as threshold.If the computed EAR is less than the threshold EAR then there will be a sleep counter variable and it will be incremented and there will be a total counter variable where, it counts the number of frames for which it had calculated the EAR value. 

EAR = ( |p2 – p6| +|p3 – p5|)/(2*|p1-p4|)
Eye blink in general lasts from 150 to 300ms
Blink distance=Distance between((p2+p3)/2,(p6+p5)/2)
ECR will be calculated for every 15 frames.
ECR = (Sleep counter / Total Counter).

The reference of the paper that is used in the work is given below.

Mehta, Sukrit and Dadhich, Sharad and Gumber, Sahil and Jadhav Bhatt, Arpita, Real-Time Driver Drowsiness Detection System Using Eye Aspect Ratio and Eye Closure Ratio (March 20, 2019). Proceedings of International Conference on Sustainable Computing in Science, Technology and Management (SUSCOM), Amity University Rajasthan, Jaipur - India, February 26-28, 2019, Available at SSRN: https://ssrn.com/abstract=3356401 or http://dx.doi.org/10.2139/ssrn.3356401


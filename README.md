This program is the demo code of several segmentation algorithms provided by Qiang qiang Liu.  
Some of them are modified based on the disclosed code. Thanks for the source of the existing algorithms.  
For more information, please contact 970051450@qq.com.  
The function main() requires following inputs:  
simulation: "True" means using the synthesized image, "False" means reading the input image.  
function: the name of the selected algorithm, such as "CV", "RSF", and so on. The code of LGMLS and ILLS is hid at present.  
k: the coefficient in LGMLS.  
T:  the threshold in some threshold-based algorithms.  
Gsig: sigma in the Gaussian kernel function in PSF.  
filepath: the path of the input image.  

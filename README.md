Detailed numerical Data for the paper: Inner Bounds for the Almost Entropic Region and Network Code Construction

Authors: Sultan Alam, Student Member, IEEE, Satyajit Thakor, Senior Member, IEEE, and Syed Abbas


There are three directories: 1) Entropic Vectors and Associated Distributions- Section III, 2) Inner Bounds- Section IV, 3) Network Coding- Section V.
In all the above three directories we have detailed data of numerical results presented in Section III, Section IV, Section V, respectively. 
The details of these directories are given in the following three sections. There are some text files, MATLAB files and the files in the cddplus format (i.e., .ine and .ext). CDD is a package developed by Komei Fukuda; webpage: https://www.cs.mcgill.ca/~fukuda/soft/cdd_home/cdd.html. 


----------------------------------------------------------------------
Directory: Entropic Vectors and Associated Distributions- Section III
----------------------------------------------------------------------

Subdirectory "Data For The Three Different Target Points" contains the data (of Fig. 1) for 200 run of the Algorithm 1 for the three different target points (in MATLAB format): Vamos polymatroid point (VP), Entropic point in [20, Theorem 4] (EP), Four-atom conjecture point (CP).


File "EntropicPointResults.mat",
File "FourAtomConjecturePointResults.mat", 


File "VamosPolymatroidResults.mat".



Each of the above files contains the parameters: AllEntropyH, AllP, ingScore, iteration, minDistance, minIngScore, normDistance. Here,

"AllEntropyH" stands for all 200 entropy points (rows), 

"AllP" stands for the distributions of all 200 entropy points (each row distribution is for each row points), 

"ingScore" stands for Ingleton scores, a vector of 1x200 containing Ingleton scores, 

"iteration" stands for the number of iterations, a vector of 1x200 containing the number of iterations for each run of Algorithm 1,
"minDistance" stands for the minimum normalized distance in all 200 normalized distances, 

"minIngScore" stands for the minimum value of Ingleton score in all 200 Ingleton scores, 

"normDistance" stands for the normalized distances, a vector of 1x200 containing normalized distances. 



Subdirectory "Table I Data" contains the data of TABLE I in the following files: 



File "Min Ingleton Score of h.mat" contains four parameters: H, IngletonScoreOfH, numberOfIterations, P. Here, 

"H" stands for the entropy vector with minimum Ingleton score,

"IngletonScoreOfH" stands for value of the Ingleton score, 

"numberOfIterations" stands for number of iterations taken to achieve minimum Ingleton score,

"P" stands for the distribution associated with H. 


File "Max Violation Index of h.mat" contains four parameters H, numberOfIterations, P, violation_Index. Here,

"H" stands for the entropy vector corresponding to the maximum Ingleton violation index, 

"numberOfIterations" stands for the number of iterations taken to maximize the Ingleton violation index, 

"P" stands for the distributions associated with H, 

"violation_Index" stands for the value of maximum Ingleton violation index.



File "Ingleton Score Of Transformation of Tight Components of h.mat" contains the parameters: H, IngletonScoreOfH, IngletonScoreOfTightH, IngletonScoreOfTransformationOfTightH, numberOfIterations, P, TightH, TransformationOfTightH. Here,

"H" stands for the entropy vector with minimum Ingleton score of a linear transformation of the tight component of H, 

"IngletonScoreOfH" stands for the Ingleton score corresponding to H, 

"IngletonScoreOfTightH" stands for the Ingleton score of the tight component of H, 

"IngletonScoreOfTransformationOfTightH" stands for the Ingleton score of the vector obtained by applying the linear transformation on the tight component of H, 

"numberOfIterations" stands for the number of iterations taking to minimize the Ingleton score, 

"P" stands for the distributions associated with H, 

"TightH" stands for the tight component of H, 

"TransformationOfTightH" stands for the vector obtained by applying the linear transformation on the tight component of H.





------------------------------------
Directory: Inner Bounds- Section IV
------------------------------------
Subdirectory "Section IV-B Data" contains the following files that are used to compute the inner bounds:

File "poly0_Gamma Inersection Reverse Ingleton Hyperplane.ine" contains the H-representation of \Gamma_4 and reverse Ingleton inequality.
File "poly0_Gamma Inersection Reverse Ingleton Hyperplane_ExtrPoints.ext" contains the V-representation of \Gamma_4 and reverse Ingleton inequality.
File "poly1_TwoZY98 NSI.ine" contains the H-representation of \Gamma_4 and reverse Ingleton inequality and two ZY98 non-Shannon Inequalities.
File "poly1_TwoZY98 NSI_ExtrPoints.ext" contains the V-representation of the respective H-representation.
File "poly2_[13, Section V].ine" contains the H-representation of \Gamma_4 and reverse Ingleton inequality and two ZY98 non-Shannon Inequalities and non-Shannon inequalities from [13, Section V].
File "poly2_[13, Section V]_ExtrPoints.ext" contains the V-representation of the respective H-representation.
File "poly3_[13, Section VI].ine" contains the H-representation of \Gamma_4 and reverse Ingleton inequality and two ZY98 non-Shannon Inequalities and non-Shannon inequalities from [13, Section VI].
File "poly3_[13, Section VI]_ExtrPoints.ext" contains the V-representation of the respective H-representation.

File "Extreme Rays 23 with Volume 42.8139%.txt" contains 23 extreme rays.

File "Extreme Rays 43 with Volume 50.1021%.txt" contains 43 extreme rays.

File "Extreme Rays 835 with Volume 57.1990%.txt" contains 835 extreme rays.



Subdirectory "Table III Data" contains five files having the extreme rays of grids to compute the inner bounds:


File "G1 U G2.txt" contains 21 extreme rays.

File "G1 U G2 U G3.txt" contains 44 extreme rays.

File "G1 U G2 U G3 U G4.txt" contains 134 extreme rays.

File "G1 U G2 U G3 U G4 U G5.txt" contains 349 extreme rays.

File "G1 U G2 U G3 U G4 U G5 U G6.txt" contains 668 extreme rays.





-------------------------------------
Directory: Network Coding- Section V
-------------------------------------

File "Figure 2 Data For Alphabets [2, 2, 2, 2].mat",

File "Figure 3 Data For Alphabets [2, 2, 2, 2].mat",

File "Figure 3 Data For Alphabets [2, 2, 2, 4].mat"

Each of the above files contains four parameters: distance, H, P, tEntropy.
 Here,
"distance" stands for the normalized distance between the target point (vector) and the nearest point (vector);,
"H" stands for the nearest point to the target,
"P" stands for the distributions associated to the nearest point H, 

"tEntropy" stands for the target point taking in Algorithm 1.


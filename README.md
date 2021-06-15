# Montivipera_niche_evolution

##################
 Description of details relevant to the data package
##################

Suggested citation for this dataset:   
#### Ahmadi, M., Hemami, M-R., Kaboli, M., Nazarizadeh, M., Malekian, M., Behrooz, R., Geniez, P., Alroy, J., Zimmermann, N.E. The legacy of Eastern Mediterranean mountain uplifts – rapid disparity of phylogenetic niche conservatism and divergence in mountain vipers. BMC Ecology and Evolution. vol, nr (2021). 


Below, the content of the Zip file is described:

#### vipera_bio.vars.csv: 
Averaged climatic variables at occurrence points
Values of the six climatic variables were extracted from each of the species presence points
and used as input data in the contMap function.  

#### Montivipera_tree.newik:
A dated phylogenetic tree of mountain vipers.


#### Montivipera_tree.xml:
The XML file used to reconstruct the dated phylogenetic tree of mountain vipers.

#### Predicted niche occupancy:
PNO along the six climatic variables including:
"pno_bio4.csv","pno_bio5.csv","pno_bio6.csv","pno_bio13.csv","pno_bio14.csv","pno_bio15.csv".

#### RCode.R:
This is the code to explore Phylogenetic Niche Conservatism (PNC) of mountain vipers of the genus Montivipera.
The niche evolution was explored based on reconstructing ancestral niche occupancy profiles (Evans et al. 2009) and ancestral state estimation of the species.
To generate profiles of predicted niche occupancy (PNO), the map of each climatic variable was converted to a histogram of 100 equal-interval bins, and the total MaxEnt raw probabilities in each bin was calculated for each species.
Here for this code PNO of the speceis were already prepared using "pno" function of phyloclim package.



##################
Date 15.06.2021
##################





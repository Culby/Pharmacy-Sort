# Pharmacy-Sort

# Table of Contents

	1. Problem <tried using []() to add hyperlink [Problem](README.md#Problem) did not work.>
	2. Data 
	3. PSUEDO Code


# Problem  

	The probelm and challenge presented is to take a raw data set orginally derived from CMS data that provides information 
	on prescribing habits by physicans and to produce a new dataset with and do counts on the number of times a drug has been 
 	prescribed as well as the he total cost for each drug.

# DATA  
	The oringal data from CMS was cleaned and normalized for drug names and providers should be assumed to be distint entities if they 	    have a seperate listing.
 	 The orignal file is named intcont.txt 
	 The output file will be renamed top_cost_drug.txt
	 
# PSUEDO CODE 
	  READ IN FILE 
	  CREATE FOR LOOP
	  COUNT TOTAL TIMES EACH DRUG WAS PRESCRIBED
	  COUNT TOTAL DRUG COST FOR EACH DRUG
	  CREATE AND WRITE NEW UPDATED FILE

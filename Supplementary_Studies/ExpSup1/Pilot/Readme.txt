- The data ".txt" file in this folder contains the raw data of the main study. 

in this ".txt" file, the different columns mean the following: 

"sID": 				subject ID 
"Order":			Counterbalancing factor (whether subjects first gave a strength rating for the multiple	or the single-effect cause)
"Process":			Factor coding whether the causes were generative or preventive.
"Valence":			Factor coding whether the effects were positive or negative.
"Multiple_Effects":		Counterbalancing factor coding whether the multiple-effects common cause was red or blue
"Target":			Counterbalacning factor (whether the target effect was E1, E2, or E3)
"multiple_strength_rating":	DV (subjects' ratings for the multiple-effects cause)
"single_strength_rating":	DV (subjects' ratings for the single-effect cause)
"Desktop_Confirmation":		Check query (subjects had to indicate that they work on a Desktop PC [1]) 
"Attention_Confirmation":	Chech query (subjectes had to indicate that they will pay attention [1])
"Effect_Valence":		Control query (effect valence check) asking subjects to say whether the effects were postive or negative (only subjects who answered correctly were included)
"Age":				Subjects' age in years
"Sex":				Subjects' sex (1 = male, 2 = female, 3 = non-binary)
"Technical_issues":		Open query (subjects could report any experienced technical issues)
"Duration (sek)":		The time subjects needed to complete the study (in seconds)



#####################

- The Analysis ".RMD" file is the R-Markdown Script that contains the statistical analyses. 

#####################

- The Analysis ".html" file is a knitted (compiled) output of the ".RMD" script.
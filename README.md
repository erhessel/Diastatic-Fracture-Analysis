# Diastatic-Fracture-Analysis
README: Diastatic sutures vs. fractures: A histological study of human cranial trauma

Description of data and abbreviations:
The data analyzed consists of numerical scores assigned to histological features based on overall extent. Scores range from 0-3:
 0 – absent, 1 – minimal, 2 – moderate, and 3 – extensive
List of abbreviations used:
 
Spec – Specimen number – refers to individual
fx – Fracture type split into DF (diastatic fracture) and LF (linear fracture)
decage – Decedent age in years (rounded to whole numbers)
inage – Injury age in days
hem – Hematoma
fib – Fibrin
lct – Loose connective tissue
fb – Fibroblasts
fct – Fibrous connective tissue
sf – Sharpey’s fibers
nc – New capillary formation
infm – Inflammation
cm – Cartilage matrix
bm – Bone matrix
resor – Bone resorption
wb – Woven bone
lb – Lamellar bone
cl – Cement lines
 
Code Structure
Script 1 – This code imports the data, transforms it to include ordered factors and creates groups for decedent and injury age.
Script 2 – This code creates tables and figures for sample demographics, score distribution, and summary statistics.
Script 3 – This code runs Wilcoxon signed-rank tests, compile the results into a table, and creates a heatmap of paired differences between diastatic and linear fracture groups for each individual.

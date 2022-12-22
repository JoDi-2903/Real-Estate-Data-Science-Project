# Real-Estate-Data-Science-Project
Semester project for data science lecture at DHBW in 2022. 
<br/>
<h2>Task description</h2>
<h3>1. Business understanding (3 points)</h3> 
Articulate a goal or multiple
objectives following the CRISP-DM process that are meaningful to real estate speculators.
Speculation typically involves the purchase of real estate that is sold at a profit.
profit. Start with the idea "We need more
understanding of the selling price (Z_selling price)!". Enter your goals in
your Jupyter notebook as markup (max. ½ page). It is important here to set up your own
hypotheses to be investigated, which will then be investigated in task part 2.
. Also, use the existing data to add to the hypotheses
or adjust as necessary.
<h3>2. Data Exploration and Analysis (9 points)</h3>
Load and explore the
data set in data_for_training.csv according to the rules as taught in the lecture.
taught. Use mark-up to document key findings.
<h3>3. Data Preparation (3 points)</h3>
Clean the data and perform feature
Engineering. Note: May already be partially required for Task 2,
then identify and summarize.
<h3>4 Modeling - Regression with Inference (3 points)</h3>
Using an
appropriate linear regression procedure to predict price
(Z_sales price) using an appropriate linear regression procedure. If necessary, you will need several versions of the
"simple" regression solutions to achieve acceptable performance.
Explain important identified relationships in a human-understandable way as text
(e.g. "A front door increases the price by 2.75 EUR.").
<h3>5. Modeling and evaluation (6 points)</h3>
Compare and optimize one or
several other methods for predicting the sales price. Proceed as
taught in lecture with training and validation data (80-20). Optimize
your prediction when appropriate.
For the training and validation data set, enter the target values R2, MSE,
RMSE, MAPE, MAX. Document this as well.
Interpret the result and the influence of the features (if possible).
Examine variance and bias in the prediction.
In the data_for_test.csv, write the values predicted based on your best model
predicted values into a new column and submit this file with it. (Hint:
Do not re-sort).
<h3>6. Deployment (3 points)</h3>
Create a guide or handout for the audience identified in
Task 1. This should summarize important
important findings of tasks 2 to 5 from the target group's point of view and should comprise a maximum of 2 pages in pdf format.
printout, which, based on the texts from task 1, should then be completely
independently readable.
<h3>7. Classification (3 points)</h3>
Try to assign real estate to the correct district
you can use the price as input value. Evaluate the
quality of your solution and comment on your findings from this small test.
test. Expected score is 3 points out of 30.

<h2>Description of the data fields</h2>

* A_Index: Unique identification number, non-consecutive (by sampling into the issued and retained data)
* Anzahl Zimmer: total number of rooms (not including kitchens and bathrooms)
* Ausbaustufe: Number of levels above the basement
  * 1 level
  * 2 levels
* Baeder: Number of bathrooms not located in the basement (KG), toilets included
* BaederKG: Analogous to bathrooms, but in KG
* Baujahr: Year in which the building was built
* EG_qm: Size of the living space in sqm on the first floor
* Garage_qm: Size of the garage in sqm
* Garagen: number of vehicles that can be parked in the garage
* Gesamteindruck: impression of the overall condition of the building as a whole
  * 5 Very good
  * 4 Good
  * 3 Average
  * 2 Poor
  * 1 Very poor
* Keller_Typ_qm: number of sqm in the type of cellar (see "cellar type" below)
* Keller_qm: number of sqm of the whole cellar
* Kellerhoehe: height of the cellar
  * Sehr gut: ca. 250 cm
  * Gut: ca. 225 cm
  * Durchschnitt: ca. 200 cm
  * Schlecht: ca. 175 cm
  * Sehr schlecht: lower than 175 cm
  * Keine Angabe: no cellar
* Kellertyp: type of cellar
  * Good living space
  * Average living space
  * No living space
  * Recreational space
  * Low quality
  * Shell
* Lage: district in which the property is located
* OG_qm: Square meters of the floor above the OG
* Umgebaut: Year in which major remodeling / additions / renovations took place, if none were carried out, this corresponds to the year of construction
* Verkaufsjahr: Year of sale
* Verkaufsmonat: Month of sale
* Wohlflaeche_qm: Living space in sqm
* Z_Verkaufspreis: Selling price in Euro

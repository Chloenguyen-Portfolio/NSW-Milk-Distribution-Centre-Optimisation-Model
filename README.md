## NSW-Milk-Distribution-Centre-Optimisation-Model
You have been hired by the NSW state government to consult on a project in which they are proposing to develop several new milk distribution centres to service all LGAs of NSW. Some context for the problem is given below. Your task is to provide advice for the government to inform its decision to build up to three milk distribution centres. 

•	The cost of distributing n litres of milk from LGA A to LGA B is a function of the distance between A and B. The cost can be calculated as being d x n x $0.10 where d = distance between A and B (in km) and n = number of litres.

•	The cost of establishing a distribution centre is dependent on the proposed maximum capacity of the distribution centre. You can assume that the cost of creating a centre with processing capacity of n litres is n x $1000. 

•	There is sufficient budget to establish up to 3 distribution centres. To distribute external risk, no single distribution centre should be allowed to have more production capacity than 50% of the entire state’s demand.

•	The RDI data for different population groups is as shown below: 

Age and life stage	Recommended dietary intake of calcium (mg/day)
Babies 0-6 months - breastfed	210 mg
Babies 0-6 months - formula fed	350 mg
Babies 7-12 months	270 mg
Children 1-3 years	500 mg
Children 4-8 years	700 mg
Children 9-11 years	1,000 mg
Adolescents 12-18 years (including pregnant and breastfeeding young women)	1,300 mg
Women 19-50 (including pregnant and breastfeeding women)	1,000 mg
Women 51-70	1,300 mg
Men 19-70	1,000 mg
Adults over 70	1,300 mg
	
•	Additionally, you will require LGA distance data to determine distribution costs. For this assignment, you should use a random number generator (such as excel’s RANDBETWEEN() or python’s randint() functions) to generate a reasonable pseudo-dataset containing LGA distances to use.
Task 1: Suppose it is 2001. Formulate and solve a problem to determine the sites of the three distribution centres to minimise expected distribution costs while considering all other requirements. Provide a short description (as relevant) of your formulation. 
Task 2: An additional consideration for the government is that Australia’s population is forecasted to grow over the coming years. They forecast 10% growth per annum over the next three years. Run a sensitivity analysis of your model to accommodate for potential population growth in the next three years. The government is planning for each facility to have a lifespan of at least 20 years. Please provide a discussion of how you would take this into account (no need to re-formulate).  
Task 3: Aside from population change, what other factors might be important for the government to consider across a twenty-year lifespan? Consider factors both discussed and not discussed in the scenario provided. Provide a short discussion. 
Task 4: Suppose it is now 2006 and five years have passed since the construction and opening of the distribution centres. Re-run your model with data from 2006 and compare your findings with those discussed in part 2. How do they compare? Provide a discussion of any insights gained. [Note: you can assume that all parameters aside from population size/demand remain unchanged].
Task 5: Repeat part 4 now with data from 2021 (20 years since the opening of the centres). This time, account for both population change, and inflation (55.6% between 2001 and 2021). Again, provide a discussion of any insights you have gained. 

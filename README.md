# Correlated-Kelly-Formula-Study
Implementation of the Kelly Formula with multiple correlated assets. Breaks down the proofs behind it, and analyze the portfolio performances. 

Goes over the mathematics and proofs behind implementing a correlated kelly optimization problem. 
Uses the machine learning factors from my other project (which uses a gradient boosted tree to create return forecasts), and 
tries to maxamize the edge created by the machine learning model. Correalted kelly systems with multiple correalated assets 
calls for a quadratic maxamization problem, which is done here as well. 
Some further work is being done into adjusting
for correalted assets, with hierchical clutering techniques being used in tandem with the factors to reduce drawdowns and
risk being an interesting option. 

Link to other project:
(https://github.com/ewalsh1331/Predicting-Stock-Returns-Using-Machine-Learning-Factor-Model)

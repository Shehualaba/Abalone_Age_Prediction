# Abalone_Age_Prediction
![image_of_an_abalone](https://luxuryviewer.com/wp-content/uploads/2020/11/shutterstock_1716057922-1024x760.jpg)
An abalone is an edible mollusc of warm seas, with a shallow ear-shaped shell lined with mother-of-pearl and pierced with a line of respiratory holes.For operational and environmental reasons, it is an important consideration to estimate the age of the abalones when they go to market. Determining an abalone's age involves counting the number of rings in a cross-section of the shell through a microscope. Since this method is somewhat cumbersome and complex, We are interested in helping the farmers estimate the age of the abalone using its physical characteristics.

The data  
[Data source](https://archive.ics.uci.edu/ml/datasets/abalone)  
Abalone characteristics:
* "sex" - M, F, and I (infant).
* "length" - longest shell measurement.
* "diameter" - perpendicular to the length.
* "height" - measured with meat in the shell.
* "whole_wt" - whole abalone weight.
* "shucked_wt" - the weight of abalone meat.
* "viscera_wt" - gut-weight.
* "shell_wt" - the weight of the dried shell.
* "rings" - number of rings in a shell cross-section.
* "age" - the age of the abalone: the number of rings + 1.5.  
**Acknowledgments:** Warwick J Nash, Tracy L Sellers, Simon R Talbot, Andrew J Cawthorn, and Wes B Ford (1994) "The Population Biology of Abalone (Haliotis species) in Tasmania. I. Blacklip Abalone (H. rubra) from the North Coast and Islands of Bass Strait", Sea Fisheries Division, Technical Report No. 48 (ISSN 1034-3288).

**The project workflow**
* Exploratory Data analysis
* Data Preprocessing
* Creating a pipeline
* Model fitting
* Model evaluation
* Recommendation

**Libraries Used**
* Pandas
* Numpy
* Seaborn
* Matplotlib
* Sklearn

**Models used**
* RandomForestRegressor
* GradientBoostingRegressor
* AdaBoostingRegressor
* LinearRegression
* Lasso

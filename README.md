# Illinois Corn Yield Prediction Project
###### Background
This project is part of my undergraduate research with Dr. Karen McKinnon at UCLA. There were two primary goals for this project.
1. Serve as my introduction to the intersection of data science and environmental science.
2. Verify the results from Butler et al's "Peculiary pleasant weather for US maize" published in 2018 in PNAS.

###### File description 
- IL_Complete_Model.ipynb is the complete analysis and model construction of the effects of temperature on maize yields in counties in Illinois
- Area_Planted_Data.ipynb collects the area of corn planted in counties using USDA Quick Stats API.
- Yield_Data.ipynb collects the county level yearly corn yield using USDA Quick Stats API.
- Maize_Development_Data.ipynb collects and formats the development data for maize in Illinois. 
- Poster_Figures.ipynb contains a selection of figures used for a poster presented at UCLA's 2019 Undergraduate Research Week Poster Session

###### Project Abstract
Understanding the interaction between crop yields and climate trends is critical to preparing the agricultural sector for future warming. This study revisits a recent publication, Butler et al., (2018), which examines the relationship between temperature and maize yield in the Midwestern United States between 1981 and 2017. In the style of this publication, we used meteorological data from a sample of Global Historical Climatology Network stations in Illinois as well as county level maize data from the United States Department of Agriculture’s National Agricultural Statistics Service (USDA NASS) to construct a multiple linear regression model of yield for select counties. The objective was to determine the influence of beneficial warm days (9 - 29 degrees Celsius) and damaging hot days (> 29 degrees Celsius) on maize yield. Using state level crop development data from USDA NASS, the crop model accounts for the varying sensitivities of maize’s development phases to both temperature classifications. Model results reveal that yearly county level maize yields in Illinois are more sensitive to KDDs than to GDDs in all stages of development. KDDs in all development phases decreased maize yield with the strongest influence from KDDs in the early grain development stage. Using the complete model to predict yearly county level maize yield from 2007 to 2017 explained 53.27% of the observed yield variance. When only considering the influence of KDDs and GDDs, the model explained 50.06% of the variance. These results suggest that KDDs and GDDs are important predictors of yearly maize yield. Given the strong influence of KDDs on maize yield and the projected increase in extremely hot days across the Midwest, maize farmers may experience decreased yields in the future.

# Home Price 
![istockphoto-932278678-612x612](https://user-images.githubusercontent.com/75095471/218719588-a220a051-b5f4-46db-a29d-f360048d76f5.jpg)

# Dataset Description
# File descriptions
<ul>
<li>train.csv - the training set</li>
<li>test.csv - the test set</li>
<li>data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here</li>
<li>sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms</li>
</ul>

# Data fields
Here's a brief version of what you'll find in the data description file.
<ul>
<li><strong>SalePrice</strong> - the property's sale price in dollars. This is the target variable that you're trying to predict.</li>
<li><strong>MSSubClass</strong>: The building class</li>
<li><strong>MSZoning</strong>: The general zoning classification</li>
<li><strong>LotFrontage</strong>: Linear feet of street connected to property</li>
<li><strong>LotArea</strong>: Lot size in square feet</li>
<li><strong>Street</strong>: Type of road access</li>
<li><strong>Alley</strong>: Type of alley access</li>
<li><strong>LotShape</strong>: General shape of property</li>
<li><strong>LandContour</strong>: Flatness of the property</li>
<li><strong>Utilities</strong>: Type of utilities available</li>
<li><strong>LotConfig</strong>: Lot configuration</li>
<li><strong>LandSlope</strong>: Slope of property</li>
<li><strong>Neighborhood</strong>: Physical locations within Ames city limits</li>
<li><strong>Condition1</strong>: Proximity to main road or railroad</li>
<li><strong>Condition2</strong>: Proximity to main road or railroad (if a second is present)</li>
<li><strong>BldgType</strong>: Type of dwelling</li>
<li><strong>HouseStyle</strong>: Style of dwelling</li>
<li><strong>OverallQual</strong>: Overall material and finish quality</li>
<li><strong>OverallCond</strong>: Overall condition rating</li>
<li><strong>YearBuilt</strong>: Original construction date</li>
<li><strong>YearRemodAdd</strong>: Remodel date</li>
<li><strong>RoofStyle</strong>: Type of roof</li>
<li><strong>RoofMatl</strong>: Roof material</li>
<li><strong>Exterior1st</strong>: Exterior covering on house</li>
<li><strong>Exterior2nd</strong>: Exterior covering on house (if more than one material)</li>
<li><strong>MasVnrType</strong>: Masonry veneer type</li>
<li><strong>MasVnrArea</strong>: Masonry veneer area in square feet</li>
<li><strong>ExterQual</strong>: Exterior material quality</li>
<li><strong>ExterCond</strong>: Present condition of the material on the exterior</li>
<li><strong>Foundation</strong>: Type of foundation</li>
<li><strong>BsmtQual</strong>: Height of the basement</li>
<li><strong>BsmtCond</strong>: General condition of the basement</li>
<li><strong>BsmtExposure</strong>: Walkout or garden level basement walls</li>
<li><strong>BsmtFinType1</strong>: Quality of basement finished area</li>
<li><strong>BsmtFinSF1</strong>: Type 1 finished square feet</li>
<li><strong>BsmtFinType2</strong>: Quality of second finished area (if present)</li>
<li><strong>BsmtFinSF2</strong>: Type 2 finished square feet</li>
<li><strong>BsmtUnfSF</strong>: Unfinished square feet of basement area</li>
<li><strong>TotalBsmtSF</strong>: Total square feet of basement area</li>
<li><strong>Heating</strong>: Type of heating</li>
<li><strong>HeatingQC</strong>: Heating quality and condition</li>
<li><strong>CentralAir</strong>: Central air conditioning</li>
<li><strong>Electrical</strong>: Electrical system</li>
<li><strong>1stFlrSF</strong>: First Floor square feet</li>
<li><strong>2ndFlrSF</strong>: Second floor square feet</li>
<li><strong>LowQualFinSF</strong>: Low quality finished square feet (all floors)</li>
<li><strong>GrLivArea</strong>: Above grade (ground) living area square feet</li>
<li><strong>BsmtFullBath</strong>: Basement full bathrooms</li>
<li><strong>BsmtHalfBath</strong>: Basement half bathrooms</li>
<li><strong>FullBath</strong>: Full bathrooms above grade</li>
<li><strong>HalfBath</strong>: Half baths above grade</li>
<li><strong>Bedroom</strong>: Number of bedrooms above basement level</li>
<li><strong>Kitchen</strong>: Number of kitchens</li>
<li><strong>KitchenQual</strong>: Kitchen quality</li>
<li><strong>TotRmsAbvGrd</strong>: Total rooms above grade (does not include bathrooms)</li>
<li><strong>Functional</strong>: Home functionality rating</li>
<li><strong>Fireplaces</strong>: Number of fireplaces</li>
<li><strong>FireplaceQu</strong>: Fireplace quality</li>
<li><strong>GarageType</strong>: Garage location</li>
<li><strong>GarageYrBlt</strong>: Year garage was built</li>
<li><strong>GarageFinish</strong>: Interior finish of the garage</li>
<li><strong>GarageCars</strong>: Size of garage in car capacity</li>
<li><strong>GarageArea</strong>: Size of garage in square feet</li>
<li><strong>GarageQual</strong>: Garage quality</li>
<li><strong>GarageCond</strong>: Garage condition</li>
<li><strong>PavedDrive</strong>: Paved driveway</li>
<li><strong>WoodDeckSF</strong>: Wood deck area in square feet</li>
<li><strong>OpenPorchSF</strong>: Open porch area in square feet</li>
<li><strong>EnclosedPorch</strong>: Enclosed porch area in square feet</li>
<li><strong>3SsnPorch</strong>: Three season porch area in square feet</li>
<li><strong>ScreenPorch</strong>: Screen porch area in square feet</li>
<li><strong>PoolArea</strong>: Pool area in square feet</li>
<li><strong>PoolQC</strong>: Pool quality</li>
<li><strong>Fence</strong>: Fence quality</li>
<li><strong>MiscFeature</strong>: Miscellaneous feature not covered in other categories</li>
<li><strong>MiscVal</strong>: $Value of miscellaneous feature</li>
<li><strong>MoSold</strong>: Month Sold</li>
<li><strong>YrSold</strong>: Year Sold</li>
<li><strong>SaleType</strong>: Type of sale</li>
<li><strong>SaleCondition</strong>: Condition of sale</li>
</ul>

# Feature Engineering 
## Missing Values
<b>PoolQC:</b> Filled with 0, as 'NA' likely means no pool.

<b>MiscFeature: </b> Filled with 0, as 'NA' likely means no miscellaneous feature.

<b>Alley: </b> Filled with 0, as 'NA' likely means no alley access.

<b>Fence: </b> Filled with 0, as 'NA' likely means no fence.

<b>FireplaceQu:</b>  Filled with 0, as 'NA' likely means no fireplace.

<b>MasVnrType and MasVnrArea: </b> Filled with None and 0, respectively, as 'NA' likely means no masonry veneer for these houses.

<b>LotFrontage: </b> Filled with the median LotFrontage of the neighborhood, as houses in the same neighborhood likely have similar LotFrontage.

<b>GarageType, GarageFinish, GarageQual, and GarageCond:</b>  Filled with 'None', as 'NA' likely means no garage.

<b>GarageYrBlt, GarageArea, and GarageCars:</b>  Filled with 0, as 'NA' likely means no garage and thus no cars in the garage.

<b>BsmtFinSF1, BsmtFinSF2, BsmtUnfSF, TotalBsmtSF, BsmtFullBath, and BsmtHalfBath: </b> Filled with 0, as missing values are likely due to no basement.

<b>BsmtQual, BsmtCond, BsmtExposure, BsmtFinType1, and BsmtFinType2:</b>  Filled with 'None', as missing values for these categorical basement-related features likely means no basement.

<b>MSZoning:</b>  Filled with 'RL', as it is the most common value.

<b>Utilities: </b> Removed, as all records are 'AllPub', except for one 'NoSeWa' and two 'NA', and this feature won't help in predictive modelling.

<b>Functional:</b>  Filled with 'Typ', as 'NA' likely means typical.

<b>Electrical:</b>  Filled with the most frequent value 'SBrkr', as this feature mostly has that value.

<b>KitchenQual:</b>  Filled with 'TA', as it is the most frequent value and there is only one missing value.

<b>Exterior1st and Exterior2nd: </b> Filled with the most common string, as both features have only one missing value.

<b>SaleType:</b>  Filled with 'WD', as it is the most frequent value.

<b>MSSubClass:</b>  Filled with 0, as 'NA' likely means no building class.
<b>TotalSF :</b> TotalSF is a new feature that is the sum of 'TotalBsmtSF', '1stFlrSF', and '2ndFlrSF'


## Skew Features

Calculates the skew of all numerical features in a Pandas DataFrame.

Identifies features with skewness greater than 0.75 as highly skewed.

Applies a Box-Cox transformation to the highly skewed features.

Stores the transformed features back into the DataFrame.

the skew() function from the scipy.stats module is used to calculate the skewness of each numerical feature, and the results are sorted in descending order.

Next, the code identifies features with skewness greater than 0.75 and selects them for transformation using the boxcox1p() function from the scipy.special module. The Box-Cox transformation parameter lambda is set to 0.15, but this value can be adjusted as needed for the data.
Finally, the transformed features are stored back into the original DataFrame. The code assumes that the DataFrame has columns named 'TotalBsmtSF', '1stFlrSF', and '2ndFlrSF'.

Overall, this code is useful for identifying and transforming highly skewed features in a dataset, which can improve the performance of machine learning models that rely on normality assumptions.


 # Model Training and Evaluation with CatBoostRegressor
The first step is to perform data preprocessing with MinMaxScaler() to normalize the independent variables. The "Price" column is extracted and treated as the dependent variable "y" while the remaining columns are used as independent variable "X".
The training data and test data are then separated using the train_test_split() function. The model is then defined and trained on the training data using fit() method of CatBoostRegressor. The evaluation of the trained model is performed on the test set, and the mean absolute error is calculated using the mean_absolute_error() function from scikit-learn.
To get the error in original units, the predicted and true values of "Price" are transformed back to their original units using inverse_transform() and inv_boxcox1p() functions since the values were first box-cox transformed. Finally, the R-squared score is computed using r2_score() function.


# Ames, IA Housing Prices

## Data Dictionary

(Descriptions here culled from original data dictionary.)

| Dataset | Table    | Column              | Type                         | Dimensions | Description
|:--------|:---------|:--------------------|:-----------------------------|:-----------|:---------------------------------------------------------------------------------|
| ames    | **ames** |                     | ['int64' 'object' 'float64'] | (2926, 82) | Information on homes sold in Ames, IA from 2006 to 2010
| ames    |          | **Id**              | `int64` (Discrete)           | (2926,)    | Observation number
| ames    |          | **PID**             | `int64` (Nominal)            | (2926,)    | Parcel identification number—can be used with city web site for parcel review.
| ames    |          | **MS SubClass**     | `int64` (Nominal)            | (2926,)    | Identifies the type of dwelling involved in the sale.
| ames    |          | **MS Zoning**       | `object` (Nominal)           | (2926,)    | Identifies the general zoning classification of the sale.
| ames    |          | **Lot Frontage**    | `float64` (Continuous)       | (2926,)    | Linear feet of street connected to property
| ames    |          | **Lot Area**        | `int64` (Continuous)         | (2926,)    | Lot size in square feet
| ames    |          | **Street**          | `object` (Nominal)           | (2926,)    | Type of road access to property
| ames    |          | **Alley**           | `object` (Nominal)           | (2926,)    | Type of alley access to property
| ames    |          | **Lot Shape**       | `object` (Ordinal)           | (2926,)    | General shape of property
| ames    |          | **Land Contour**    | `object` (Nominal)           | (2926,)    | Flatness of the property
| ames    |          | **Utilities**       | `object` (Ordinal)           | (2926,)    | Type of utilities available
| ames    |          | **Lot Config**      | `object` (Nominal)           | (2926,)    | Lot configuration
| ames    |          | **Land Slope**      | `object` (Ordinal)           | (2926,)    | Slope of property
| ames    |          | **Neighborhood**    | `object` (Nominal)           | (2926,)    | Physical locations within Ames city limits (map available)
| ames    |          | **Condition 1**     | `object` (Nominal)           | (2926,)    | Proximity to various conditions
| ames    |          | **Condition 2**     | `object` (Nominal)           | (2926,)    | Proximity to various conditions (if more than one is present)
| ames    |          | **Bldg Type**       | `object` (Nominal)           | (2926,)    | Type of dwelling
| ames    |          | **House Style**     | `object` (Nominal)           | (2926,)    | Style of dwelling
| ames    |          | **Overall Qual**    | `int64` (Ordinal)            | (2926,)    | Rates the overall material and finish of the house
| ames    |          | **Overall Cond**    | `int64` (Ordinal)            | (2926,)    | Rates the overall condition of the house
| ames    |          | **Year Built**      | `int64` (Discrete)           | (2926,)    | Original construction date
| ames    |          | **Year Remod/Add**  | `int64` (Discrete)           | (2926,)    | Remodel date (same as construction date if no remodeling or additions)
| ames    |          | **Roof Style**      | `object` (Nominal)           | (2926,)    | Type of roof
| ames    |          | **Roof Matl**       | `object` (Nominal)           | (2926,)    | Roof material
| ames    |          | **Exterior 1st**    | `object` (Nominal)           | (2926,)    | Exterior covering on house
| ames    |          | **Exterior 2nd**    | `object` (Nominal)           | (2926,)    | Exterior covering on house (if more than one material)
| ames    |          | **Mas Vnr Type**    | `object` (Nominal)           | (2926,)    | Masonry veneer type
| ames    |          | **Mas Vnr Area**    | `float64` (Continuous)       | (2926,)    | Masonry veneer area in square feet
| ames    |          | **Exter Qual**      | `int64` (Ordinal)            | (2926,)    | Evaluates the quality of the material on the exterior
| ames    |          | **Exter Cond**      | `int64` (Ordinal)            | (2926,)    | Evaluates the present condition of the material on the exterior
| ames    |          | **Foundation**      | `object` (Nominal)           | (2926,)    | Type of foundation
| ames    |          | **Bsmt Qual**       | `float64` (Ordinal)          | (2926,)    | Evaluates the height of the basement
| ames    |          | **Bsmt Cond**       | `float64` (Ordinal)          | (2926,)    | Evaluates the general condition of the basement
| ames    |          | **Bsmt Exposure**   | `object` (Ordinal)           | (2926,)    | Refers to walkout or garden level walls
| ames    |          | **BsmtFin Type 1**  | `object` (Ordinal)           | (2926,)    | Rating of basement finished area
| ames    |          | **BsmtFin SF 1**    | `float64` (Continuous)       | (2926,)    | Type 1 finished square feet
| ames    |          | **BsmtFin Type 2**  | `object` (Ordinal)           | (2926,)    | Rating of basement finished area (if multiple types)
| ames    |          | **BsmtFin SF 2**    | `float64` (Continuous)       | (2926,)    | Type 2 finished square feet
| ames    |          | **Bsmt Unf SF**     | `float64` (Continuous)       | (2926,)    | Unfinished square feet of basement area
| ames    |          | **Total Bsmt SF**   | `float64` (Continuous)       | (2926,)    | Total square feet of basement area
| ames    |          | **Heating**         | `object` (Nominal)           | (2926,)    | Type of heating
| ames    |          | **Heating QC**      | `int64` (Ordinal)            | (2926,)    | Heating quality and condition
| ames    |          | **Central Air**     | `object` (Nominal)           | (2926,)    | Central air conditioning
| ames    |          | **Electrical**      | `object` (Ordinal)           | (2926,)    | Electrical system
| ames    |          | **1st Flr SF**      | `int64` (Continuous)         | (2926,)    | First Floor square feet
| ames    |          | **2nd Flr SF**      | `int64` (Continuous)         | (2926,)    | Second floor square feet
| ames    |          | **Low Qual Fin SF** | `int64` (Continuous)         | (2926,)    | Low quality finished square feet (all floors)
| ames    |          | **Gr Liv Area**     | `int64` (Continuous)         | (2926,)    | Above grade (ground) living area square feet
| ames    |          | **Bsmt Full Bath**  | `float64` (Discrete)         | (2926,)    | Basement full bathrooms
| ames    |          | **Bsmt Half Bath**  | `float64` (Discrete)         | (2926,)    | Basement half bathrooms
| ames    |          | **Full Bath**       | `int64` (Discrete)           | (2926,)    | Full bathrooms above grade
| ames    |          | **Half Bath**       | `int64` (Discrete)           | (2926,)    | Half baths above grade
| ames    |          | **Bedroom AbvGr**   | `int64` (Discrete)           | (2926,)    | Bedrooms above grade (does NOT include basement bedrooms)
| ames    |          | **Kitchen AbvGr**   | `int64` (Discrete)           | (2926,)    | Kitchens above grade
| ames    |          | **Kitchen Qual**    | `int64` (Ordinal)            | (2926,)    | Kitchen quality
| ames    |          | **TotRms AbvGrd**   | `int64` (Discrete)           | (2926,)    | Total rooms above grade (does not include bathrooms)
| ames    |          | **Functional**      | `object` (Ordinal)           | (2926,)    | Home functionality (Assume typical unless deductions are warranted)
| ames    |          | **Fireplaces**      | `int64` (Discrete)           | (2926,)    | Number of fireplaces
| ames    |          | **Fireplace Qu**    | `float64` (Ordinal)          | (2926,)    | Fireplace quality
| ames    |          | **Garage Type**     | `object` (Nominal)           | (2926,)    | Garage location
| ames    |          | **Garage Yr Blt**   | `float64` (Discrete)         | (2926,)    | Year garage was built
| ames    |          | **Garage Finish**   | `object` (Ordinal)           | (2926,)    | Interior finish of the garage
| ames    |          | **Garage Cars**     | `float64` (Discrete)         | (2926,)    | Size of garage in car capacity
| ames    |          | **Garage Area**     | `float64` (Continuous)       | (2926,)    | Size of garage in square feet
| ames    |          | **Garage Qual**     | `float64` (Ordinal)          | (2926,)    | Garage quality
| ames    |          | **Garage Cond**     | `float64` (Ordinal)          | (2926,)    | Garage condition
| ames    |          | **Paved Drive**     | `object` (Ordinal)           | (2926,)    | Paved driveway
| ames    |          | **Wood Deck SF**    | `int64` (Continuous)         | (2926,)    | Wood deck area in square feet
| ames    |          | **Open Porch SF**   | `int64` (Continuous)         | (2926,)    | Open porch area in square feet
| ames    |          | **Enclosed Porch**  | `int64` (Continuous)         | (2926,)    | Enclosed porch area in square feet
| ames    |          | **3Ssn Porch**      | `int64` (Continuous)         | (2926,)    | Three season porch area in square feet
| ames    |          | **Screen Porch**    | `int64` (Continuous)         | (2926,)    | Screen porch area in square feet
| ames    |          | **Pool Area**       | `int64` (Continuous)         | (2926,)    | Pool area in square feet
| ames    |          | **Pool QC**         | `float64` (Ordinal)          | (2926,)    | Pool quality
| ames    |          | **Fence**           | `object` (Ordinal)           | (2926,)    | Fence quality
| ames    |          | **Misc Feature**    | `object` (Nominal)           | (2926,)    | Miscellaneous feature not covered in other categories
| ames    |          | **Misc Val**        | `int64` (Continuous)         | (2926,)    | $Value of miscellaneous feature
| ames    |          | **Mo Sold**         | `int64` (Discrete)           | (2926,)    | Month Sold (MM)
| ames    |          | **Yr Sold**         | `int64` (Discrete)           | (2926,)    | Year Sold (YYYY)
| ames    |          | **Sale Type**       | `object` (Nominal)           | (2926,)    | Type of sale
| ames    |          | **SalePrice**       | `float64` (Continuous)       | (2926,)    | Sale price $$
| ames    |          | **Dataset**         | `object` (Nominal)           | (2926,)    | Represents one of "test" or "train", corresponding to the original test–train split



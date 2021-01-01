- [Home](./index.md)
- [Installation](./install.md)
- [Guide](./use.md)
- [About](./about.md)

## Load the data

The file must be in .csv or .xlsx format.

<img src="guide/step1.png" align="center" />

"The data order of the columns is ID, sex, age, reaction time, IQ, depression, anxiety. Columns 8-155 are 74 regions of the left hemisphere and 74 regions of the right hemisphere. All column names must exist, but related data can be null. In this OASIS data set, there are 300 data sets in total." 
<img src="guide/oasis.png" align="center"/>
<img src="guide/oasis_b.png" align="center"/>

You can filter the columns and information as you wish. To restart the Shiny App use the Restart-Button.

## Load the atlas

Different users have different names for the same brain region, so in this Shiny App you can import a file for this. The file must be also in .csv or .xlsx format. 

<img src="guide/step2.png" align="center" />

You can customize the brain region name to the name you want with the template areas.xlsx. In this file, the left column is the original name of the region (do not change) and in the right column is the user-defined name.

<img src="guide/atlas.png" align="center"/>

## Functions

### Quality Control with Raincloud-Plots:
<img src="example_raincloud.png" align="center"/>

### Descriptive Statistics:
<img src="example.png" align="center"/>

### Linear Regression:
<img src="example_regression.png" align="center"/>

### Lasso Regression:
<img src="example_lasso.png" align="center"/>
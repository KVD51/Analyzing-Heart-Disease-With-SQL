AHD - Analyzing Heart Disease With SQL

The purpose of the SQL code within the AHD.ipynb Jupyter Notebook file is to illustrate the use of sqlite. It is the result of a project that I completed while learning SQL.

If you wish to run the code within the AHD.ipynb, save the AHD_copy_original.db file with the name AHD.db to you local computer, then follow the instructions at the top of AHD.ipynb file to alter the path to the db file. You can save the db file using whatever name you wish, as long as you reference it correctly in the path.

AHD_copy_original.db contains three tables: patients, panels, recommended_values
patients - a list of patient related info: ID, name, address, etc
panels - the results from lipid panel tests. There can be more than one for each patient
recommended_values - contains threshold levels for whether a lipid level is Low, Desirable, Borderline_High or High

Analysis done:

- View contents of the tables to get a sense for them

- Perform some data manipulation and respond to ad-hoc requests

- Determine which patients are at risk of Coronary Artery Disease (CAD)

Ultimately, the SQL code analyzes lipid panel results for determining whether patients may be at risk of coronary artery disease (CAD). The data and analysis are based on simplified real life data, and does not reflect all factors and steps used in the process of evaluating patients for CAD.

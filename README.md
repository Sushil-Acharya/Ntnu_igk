The following notebooks process .las files from a specified folder, combining them into a single CSV file. They also read 2D seismic data to identify the corresponding trace for a specific well. Additionally, they establish the relationship between depth and time using AC log values and prepare training data for machine learning models to predict physical parameters.

LONCCARICA_1.ipynb 
REZOVACCKE_KRCCEVINE_1.ipynb
REZOVACCKE_KRCCEVINE_2.ipynb
SUHOPOLJE_1.ipynb
VIROVITICA_1.ipynb
VIROVITICA_3ALFA.ipynb

These are the accumulated CSV files.
LONCCARICA_1_ALL.csv 
REZOVACCKE_KRCCEVINE_1_ALL.csv
REZOVACCKE_KRCCEVINE_2_ALL.csv
SUHOPOLJE_1_ALL.csv
VIROVITICA_1_ALL.csv
VIROVITICA_3ALFA_ALL.csv

These CSV files have been prepared to train a machine-learning model to predict temperature(TEMP), deep resistivity (RT), porosity (PHIT), and water saturation (SW).
LONCCARICA_1_RT.csv
LONCCARICA_1_TEMP.csv
REZOVACCKE_KRCCEVINE_1_PHIT.csv
REZOVACCKE_KRCCEVINE_1_RT.csv
REZOVACCKE_KRCCEVINE_1_SW.csv
REZOVACCKE_KRCCEVINE_1_TEMP.csv
REZOVACCKE_KRCCEVINE_2_PHIT.csv
REZOVACCKE_KRCCEVINE_2_RT.csv
REZOVACCKE_KRCCEVINE_2_SW.csv
SUHOPOLJE_1_RT.csv
VIROVITICA_1_RT.csv
VIROVITICA_1_TEMP.csv
VIROVITICA_3ALFA_PHIT.csv
VIROVITICA_3ALFA_RT.csv
VIROVITICA_3ALFA_SW.csv


Lithology data.ipynb prepare lithology data.

These are the physical parameter prediction models.

Predict Porosity.ipynb
Predict Temperature.ipynb
Predict Water saturation.ipynb
Predict deep resistivity.ipynb

Some of the saved CSV files
Unknown1.csv
Unknown1_filtered.csv
Unknown1_non_zero_amplitude.csv
Unknown2.csv
Unknown_1_evaluations 1.csv
Unknown_2_evaluations 1.csv



Models to predict the temperature and deep resistivity for all the seismic logs.

full seismic unknown1_TEMP.ipynb
full seismic unknown2_TEMP.ipynb
full seismic-Unknown1_RD.ipynb
full seismic-Unknown2_RD.ipynb


These are the final predicted CSV files
unknown1_litho_with_actual.csv
unknown1_litho.csv
unknown2_litho.csv
unknown2_litho_with_actual.csv
lithology_mappings.csv

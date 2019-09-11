The Jupyter Notebook medical_deltas.ipynb will examine data pulled from the ‘data’ folder. 

The notebook relies on Medicare data (Inpatient_PYMT..), state census data and state centroid data (used to plot heatmaps). The top four medicare DRG codes (by patient volume) were initially considered. We subsequently reduced investigation to two – Diabetes complications and Major Joint replacement which have some element of facility electability. 

The notebook focused on creating dataframes from the files and analyzing for highest ‘List Price’ variance (measured by standard deviation at a state-level). New Jersey showed the highest deviation in list price. Mississippi also figured prominently, and because of its mainly rural and low-income status, presented an interesting field to examine cost variability.

Little correlation was seen between hospital list prices and State Census data

Graphs can be generated in the latter section of the Notebook.

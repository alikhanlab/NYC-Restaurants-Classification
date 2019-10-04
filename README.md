# NYC-Restaurants-Classification
NYC Restaurants Classification by Inspection Results



Team: Kuat Abdrau, Alikhan Nurlanuly

- Dataset description:
The dataset contains every sustained or not yet adjudicated violation citation from every full or special program inspection conducted up to three years prior to the most recent inspection for restaurants and college cafeterias in an active status on the RECORD DATE (date of the data pull). When an inspection results in more than one violation, values for associated fields are repeated for each additional violation record. Establishments are uniquely identified by their CAMIS (record ID) number. Keep in mind that thousands of restaurants start business and go out of business every year; only restaurants in an active status are included in the dataset. Records are also included for each restaurant that has applied for a permit but has not yet been inspected and for inspections resulting in no violations. Establishments with inspection date of 1/1/1900 are new establishments that have not yet received an inspection. Restaurants that received no violations are represented by a single row and coded as having no violations using the ACTION field.
Because this dataset is compiled from several large administrative data systems, it contains some illogical values that could be a result of data entry or transfer errors. Data may also be missing.
This dataset and the information on the Health Department’s Restaurant Grading website come from the same data source.

- Source: DOHMH New York City Restaurant Inspection Results
https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection- Results/43nn-pn8j

- Number of tuples and features 
Tuples: 393K
Features: 26

- Data mining goal:
Classify restaurants according to inspections results.

- Category groups:
restaurant, inspection, violation, grade, adjudication, fines, 2018od4a-report, 2018od4a-video, food safety

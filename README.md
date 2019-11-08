# Directory structure for machine learning projects.

```
*    credentials/  <-- passwds and api keys
**    email
**    aws
*    data/         <-- all kinds of data 
**    raw/         <-- raw datasets, not overwritten by any code
**    cache/       <-- intermediate data like pkl version of processed dataset
**    processed/   <-- preprocessed data in form suitable for feeding into the models
**    parameters/  <-- nn weights or any other parameters
*    docs/         <-- documentation for end user
*    notes/        <-- technical notes and ideas mostly internal stuff
**    references/  <-- notes pertaining to dataset schema
**    snippets/    
*    notebooks/    <-- exploratory notebooks
*    libs/         <-- external modules and packages
*    src/
**    scripts/     <-- scripts mostly bash, sometime python too
**    model/       
*    tex/          <-- in case this work is for publication
**    images/      <-- images other than charts, like arch diagrams
*    reports/      
**    diagnostics/  <-- data diagnostics like missing values, model diagnostics
**    profiling/    <-- code coverage and profiling
**    logs/
***    model/      <-- logs produced by model objects
***    datafeed/   <-- logs produced by dataloaders and feeders
* README
* TODO
* CONTRIBUTING
* CHANGELOG (OR) HISTORY (OR) CHANGE

```

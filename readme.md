This repository illustrate the data used for the study.
# Study Setup 
The **Study Setup** folder contains the study setup data and its intermediate results.

## RQ1 
The **RQ1 Patterns of Non-trivial Type-annotation Practices** folder contains the data corresponding to RQ1 of *Evaluation* section.
## RQ2
File "projectname.json"  represents both explicit and possible dependencies of each file.
File "projectname_degree.csv" shows the degree of each file in a networkx graph.
File "projectname_statistics.csv" illustrates the result of precision and recall when using top any% files ranked by degree centrality to captrue type-hinted files, from top 10%, 20% ... to 100%.
projectname_filetype.csv
File "projectname_drh.csv" represents the hierarchial location of each file. 
File "projectname_drhstatistics.csv" depicts the propotion of type_annotated files at each layer.


## RQ3
File "projectname_typedlog_statis.csv"  illustrates the result of precision and recall when using top any% files ranked by #author, #changeCmt, #changeLoc, #issue, #issueCmt, #issueLoc  to captrue type-hinted files, from top 10%, 20% ... to 100%.
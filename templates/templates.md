# Templates

Thank you for contributing to Fun<sup>fun</sup> (a fungal functional trait database). Below you will find a set of templates for the essential files used to generate the dataset.

## Data file template


| Species | dsDNA..ug.mg.1.dry.weight. | Mean.growth.rate..cm.day. |
| ------------------ | --------------------------- | ------------------------- |
| Alternaria | 5.34 |0.73 |
| Aspergillus niger | 4.51 | 0.65
| Aspergillus niger | 2.83 | NA
| Aspergillus niger | 1.12 | NA
| Botrytis allii | 4.00 | 0.53




[Download the template for data.csv](https://raw.githubusercontent.com/habacucfm/contribute_fttf/master/templates/data.csv)



## Template for dataMatchColumns.csv


| var_in | method | unit_in | var_out | notes|
|--------------------------- | ------- | -------- | --------------- | ------|
| Species | NA | NA | species | NA |
| dsDNA (ug mg-1 dry weight) | NA | ug/mg | dsDNA | NA |
| Mean growth rate (cm/day) | NA | cm/day | extension_rate | NA |



[Download the template for dataMatchColumns.csv](https://raw.githubusercontent.com/habacucfm/contribute_fttf/master/templates/dataMatchColumns.csv)



## Template for study metadata



| Topic | Description |
| ---------------------- | ------------------------------------------------------------------- |
| culture_preconditions | Martin`s agar as slant cultures and stored at 4 °C until use |
| culture_ph | 7 |
| culture_volume | 200 ml |
| container_type | 250 ml Erlenmeyer flasks |
| culture_media | fresh sterile modified Czapek-Dox liquid medium with yeast extract|
| culture_temp | 20-25 °C |
| culture_community | individual |
| tissue_type | mycellium |
| experiment_type | Lab |
| replicates | 3-5 per fungus |



[Download the template for studyMetadata.csv](https://raw.githubusercontent.com/habacucfm/contribute_fttf/master/templates/studyMetadata.csv)



## Template for study reference


@article{wallace1902island,

  title={Island life, or, the phenomena and causes of insular faunas and floras: including a revision and attempted solution of the problem of geological climates},

 author={Wallace, Alfred Russel},

 journal={Journal of Biogegraphy},

 volume={58},

 number={1},

 pages={19-20},

 year={2008},

 publisher={Macmillan}
}




[Download the template for the study reference](https://raw.githubusercontent.com/habacucfm/contribute_fttf/master/templates/studyRef.bib)



## Template for study contact information



| name | email | address |
| ---------- | ------------------------------ | -----------------
| Your name | youremailadress@somewhere.edu | Physical address|




[Download the template for study contact information](https://raw.githubusercontent.com/habacucfm/contribute_fttf/master/templates/studyContact.csv)

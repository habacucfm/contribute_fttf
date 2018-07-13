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




[Download the template for data.csv](data:text/csv;base64,U3BlY2llcyxkc0ROQSAodWcgbWctMSBkcnkgd2VpZ2h0KSxNZWFuIGdyb3d0aCByYXRlIChjbS9kYXkpCkFsdGVybmFyaWEsNS4zNCwwLjczCkFzcGVyZ2lsbHVzIG5pZ2VyLDQuNTEsMC42NQpBc3BlcmdpbGx1cyBuaWdlciwyLjgzLE5BCkFzcGVyZ2lsbHVzIG5pZ2VyLDEuMTIsTkEKQm90cnl0aXMgYWxsaWksNCwwLjUz) **or** open it directly in your | <a download="dataMatchColumns.csv" href="data:application/csv;base64,U3BlY2llcyxkc0ROQSAodWcgbWctMSBkcnkgd2VpZ2h0KSxNZWFuIGdyb3d0aCByYXRlIChjbS9kYXkpCkFsdGVybmFyaWEsNS4zNCwwLjczCkFzcGVyZ2lsbHVzIG5pZ2VyLDQuNTEsMC42NQpBc3BlcmdpbGx1cyBuaWdlciwyLjgzLE5BCkFzcGVyZ2lsbHVzIG5pZ2VyLDEuMTIsTkEKQm90cnl0aXMgYWxsaWksNCwwLjUz">browser</a>



## Template for dataMatchColumns.csv


| var_in | method | unit_in | var_out | notes|
|--------------------------- | ------- | -------- | --------------- | ------|
| Species | NA | NA | species | NA |
| dsDNA (ug mg-1 dry weight) | NA | ug/mg | dsDNA | NA |
| Mean growth rate (cm/day) | NA | cm/day | extension_rate | NA |



[Download the template for dataMatchColumns.csv](data:text/csv;base64,InZhcl9pbiIsIm1ldGhvZCIsInVuaXRfaW4iLCJ2YXJfb3V0Iiwibm90ZXMiCiJTcGVjaWVzIixOQSxOQSwic3BlY2llcyIsTkEKImRzRE5BICh1ZyBtZy0xIGRyeSB3ZWlnaHQpIixOQSwidWcvbWciLGRzRE5BLE5BCiJNZWFuIGdyb3d0aCByYXRlIChjbS9kYXkpIixOQSwiY20vZGF5IiwiZXh0ZW5zaW9uX3JhdGUiLE5B) **or** open it directly in your | <a download="dataMatchColumns.csv" href="data:application/csv;base64,InZhcl9pbiIsIm1ldGhvZCIsInVuaXRfaW4iLCJ2YXJfb3V0Iiwibm90ZXMiCiJTcGVjaWVzIixOQSxOQSwic3BlY2llcyIsTkEKImRzRE5BICh1ZyBtZy0xIGRyeSB3ZWlnaHQpIixOQSwidWcvbWciLGRzRE5BLE5BCiJNZWFuIGdyb3d0aCByYXRlIChjbS9kYXkpIixOQSwiY20vZGF5IiwiZXh0ZW5zaW9uX3JhdGUiLE5B">browser</a>



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



[Download the template for studyMetadata.csv](data:text/csv;base64,VG9waWMsRGVzY3JpcHRpb24KY3VsdHVyZV9wcmVjb25kaXRpb25zLCAiTWFydGluYHMgYWdhciBhcyBzbGFudCBjdWx0dXJlcyBhbmQgc3RvcmVkIGF0IDQgwrBDIHVudGlsIHVzZSIKY3VsdHVyZV9waCwgIjciCmN1bHR1cmVfdm9sdW1lLCAiMjAwIG1sIgpjb250YWluZXJfdHlwZSwgIjI1MCBtbCBFcmxlbm1leWVyIGZsYXNrcyIKY3VsdHVyZV9tZWRpYSwiZnJlc2ggc3RlcmlsZSBtb2RpZmllZCBDemFwZWstRG94IGxpcXVpZCBtZWRpdW0gd2l0aCB5ZWFzdCBleHRyYWN0IgpjdWx0dXJlX3RlbXAsIjIwLTI1IMKwQyIKY3VsdHVyZV9jb21tdW5pdHksaW5kaXZpZHVhbAp0aXNzdWVfdHlwZSxteWNlbGxpdW0KZXhwZXJpbWVudF90eXBlLExhYgpyZXBsaWNhdGVzLCAiMy01IHBlciBmdW5ndXMi) **or** open it directly in your | <a download="dataMatchColumns.csv" href="data:application/csv;base64,VG9waWMsRGVzY3JpcHRpb24KY3VsdHVyZV9wcmVjb25kaXRpb25zLCAiTWFydGluYHMgYWdhciBhcyBzbGFudCBjdWx0dXJlcyBhbmQgc3RvcmVkIGF0IDQgwrBDIHVudGlsIHVzZSIKY3VsdHVyZV9waCwgIjciCmN1bHR1cmVfdm9sdW1lLCAiMjAwIG1sIgpjb250YWluZXJfdHlwZSwgIjI1MCBtbCBFcmxlbm1leWVyIGZsYXNrcyIKY3VsdHVyZV9tZWRpYSwiZnJlc2ggc3RlcmlsZSBtb2RpZmllZCBDemFwZWstRG94IGxpcXVpZCBtZWRpdW0gd2l0aCB5ZWFzdCBleHRyYWN0IgpjdWx0dXJlX3RlbXAsIjIwLTI1IMKwQyIKY3VsdHVyZV9jb21tdW5pdHksaW5kaXZpZHVhbAp0aXNzdWVfdHlwZSxteWNlbGxpdW0KZXhwZXJpbWVudF90eXBlLExhYgpyZXBsaWNhdGVzLCAiMy01IHBlciBmdW5ndXMi">browser</a>



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




[Download the template for the study reference](data:text/csv;base64,QGFydGljbGV7d2FsbGFjZTE5MDJpc2xhbmQsCiAgdGl0bGU9e0lzbGFuZCBsaWZlLCBvciwgdGhlIHBoZW5vbWVuYSBhbmQgY2F1c2VzIG9mIGluc3VsYXIgZmF1bmFzIGFuZCBmbG9yYXM6IGluY2x1ZGluZyBhIHJldmlzaW9uIGFuZCBhdHRlbXB0ZWQgc29sdXRpb24gb2YgdGhlIHByb2JsZW0gb2YgZ2VvbG9naWNhbCBjbGltYXRlc30sCiAgYXV0aG9yPXtXYWxsYWNlLCBBbGZyZWQgUnVzc2VsfSwKICBqb3VybmFsPXtKb3VybmFsIG9mIEJpb2dlZ3JhcGh5fSwKICB2b2x1bWU9ezU4fSwKICBudW1iZXI9ezF9LAogIHBhZ2VzPXsxOS0yMH0sCiAgeWVhcj17MjAwOH0sCiAgcHVibGlzaGVyPXtNYWNtaWxsYW59Cn0=) **or** open it directly in your | <a download="dataMatchColumns.csv" href="data:application/csv;base64,QGFydGljbGV7d2FsbGFjZTE5MDJpc2xhbmQsCiAgdGl0bGU9e0lzbGFuZCBsaWZlLCBvciwgdGhlIHBoZW5vbWVuYSBhbmQgY2F1c2VzIG9mIGluc3VsYXIgZmF1bmFzIGFuZCBmbG9yYXM6IGluY2x1ZGluZyBhIHJldmlzaW9uIGFuZCBhdHRlbXB0ZWQgc29sdXRpb24gb2YgdGhlIHByb2JsZW0gb2YgZ2VvbG9naWNhbCBjbGltYXRlc30sCiAgYXV0aG9yPXtXYWxsYWNlLCBBbGZyZWQgUnVzc2VsfSwKICBqb3VybmFsPXtKb3VybmFsIG9mIEJpb2dlZ3JhcGh5fSwKICB2b2x1bWU9ezU4fSwKICBudW1iZXI9ezF9LAogIHBhZ2VzPXsxOS0yMH0sCiAgeWVhcj17MjAwOH0sCiAgcHVibGlzaGVyPXtNYWNtaWxsYW59Cn0=">browser</a>



## Template for study contact information



| name | email | address |
| ---------- | ------------------------------ | -----------------
| Your name | youremailadress@somewhere.edu | Physical address|




[Download the template for study contact information](https://raw.githubusercontent.com/habacucfm/contribute_fttf/master/templates/studyContact.csv)
 |

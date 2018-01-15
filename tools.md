
# Technology and Tools for Data Ethics

## Provenance Tooling 
There are two methods, static approaches which analyse scripts for commands, 

#### Approaches
*Dynamic provenance tracking* 

Code can be analysed at run-time, including tracing high level commands and lower level commands in the run time execution call stack. 

*Static provenance tracking*

A script file can be parsed and analysed to investigate individual function inputs/outputs and operations. 

####Resources/ Working Groups
http://end-to-end-provenance.github.io/

####Existing tools
Some existing tools that claim to track data provenance :

*R script*

* https://github.com/NCEAS/recordr
* https://github.com/End-to-end-provenance/RDataTracker - creates a data derivation graph (DDG) that keeps track of data in an intuitive way. Provides dynamic tracking.

*Python*

* https://github.com/trungdong/prov: A python library implementing W3C PROV
* http://prov.readthedocs.io/en/latest/readme.html
* https://github.com/Data2Semantics/prov-o-matic ipython/ jupyter notebook integration of tools to generate W3C PROV serializations. Uses Python decorators around functions. Session persistent.
* https://github.com/recipy/recipy - add line at top of code to record meta-data for each run.




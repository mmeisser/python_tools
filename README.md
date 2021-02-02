# python_tools

Author: M.Meisser (Jan 2021)
## introduction
 some scripts useful to be used in a jupyter notebook that can parse csv log file data captured by some of our vr applications (sarto input tool or akra).
 
## References
Follow this [link](https://docs.google.com/document/d/1nbtnkmugINfLZDkXvd0Pg-F84M_gCakWoVQM8z54nQs/edit#heading=h.2wsf72o3ozki) to get the details and setup the environment 

## input
You'll need a csv-based file at first

## output
the script will generate some graphs and some calculated parameters that allows to caracterize a sample (from which the log was captured) with these parameters:

- NIB & PRIMARY min and max values
- NIB & PRIMARY range (max-min)
- NIB & PRIMARY minimum value change over the period
- NIB vs PRIMARY correlation (ie crosstalk)

---
layout: page
title: Data Management in the Ocean, Weather, and Climate Sciences
---

Our previous lessons have shown us how to write programs that ingest a list of data files,
perform some calculations on those data,
and then print a final result to the screen. 
While this was a useful exercise in learning the principles of scripting and parsing the command line, 
in most cases the output of our programs will not be so simple. 
Instead, programs typically take data as input, 
manipulate that data, 
and then output yet more data. 
Over the course of a multi-year research project, 
most reseachers will write many different programs that produce many different output datasets.   

We want to:

* Develop a personal data management plan so as to avoid confusion/calamity  

Along the way, we will learn:

* how to create a Data Reference Syntax
* how to view the contents of binary files
* about data provenance and metadata
* about the Python libraries and command line utilities commonly used in the ocean, weather and climate sciences


> ## Prerequisites {.prereq}
>
> It is assumed that learners will have completed the core Software Carpentry
> lessons on the Unix Shell, Python and Git before tackling this lesson.
>
> The following additional Python libraries must also be installed to complete the lesson:  
>
> GitPython:  
> `pip install gitpython`  
>
> netCDF4:  
> `conda config --add channels conda-forge`  
> `conda install netcdf4`  
> 

## Topics

1.  [Data Management](01-data-management.html)
2.  [Data Processing](02-data-processing.html)
3.  [Data Provenance](03-data-provenance.html) 

## Other Resources

*   [Motivation](motivation.html)
*   [Reference](reference.html)
*   [Discussion](discussion.html)
*   [Instructor's Guide](instructors.html)

# Campaign: WORKFLOWS

Improving Scientific Data Analysis Workflows

## Overview

In a very general sense, scientific data analysis workflows usually have a
particular process structure to them:

1. **Search & Discovery**: Locate the data you need to analyze
2. **Injestion**: Open and read this data
3. **Analysis**: Perform some computations on this data
4. **Check-point**: Save computed artifact as a new dataset
5. **Visualize**: Produce images (e.g., for publication) from the computed artifact

Implied by this process is the existence of a **Platform** for the user to 
conduct each step.  *It is not necessary that the same platform be used for each 
step.*  In fact, multiple platforms *could* be used in a single step (e.g., during
the *Search & Discovery* phase, the scientist might use a combination of web
searching to find the larger dataset or collection, and then move to a Jupyter
Notebook to make queries of the larger dataset to produce subsets).  It is not
critical that a *single platform* be emphasized or prioritized, but making it
easier and more productive for the scientist is critical.  That could mean
reducing the number of platforms the scientist must use, but it could also mean
making multiple platforms inter-operate better.

Throughout this process, there are many tools in the Pangeo ecosystem that can
be used to improve the scientist's UX.  Some thoughts on these different phases
of the process follow.

### Search & Discovery (S&E)

Some minimal S&E is provided by Intake and Intake-ESM.  General search and
discovery is *not* provided by Intake, which would include making it easy for
a scientist ignorant of an Intake catalog's to semantically search and discover
relevant datasets, on what system they can be analyzed, and where to locate
their Intake catalogs.  In general, Intake and Intake-ESM provide *semantic
subsetting* of the datasets or collections.

NCAR's [Digital Asset Services Hub (DASH)](https://www2.cisl.ucar.edu/dash),
could provide easy S&E for NCAR assets.  One thought then might be for each
"analyzable" DASH asset to also indicate the path/link to an associated
Intake catalog file.  Then, the DASH asset can be easily discovered via
DASH's online S&E interface, it is is just a simple "cut and paste" of the
Intake catalog link into a Jupyter Notebook session to then get the
queriable Intake collection.

Another, more complicated, option is to integrate NCAR's DASH S&E into
Jupyter Notebooks via something like a DASH Labextension.  Then the S&E
step that occurs via DASH could then be made "push-button" with no
cut-and-paste step between the user's DASH session and their Jupyter-based
analysis.

### Injestion



## Objectives

[Bulleted list of objectives for this campaign]

## Example Projects

[Bulleted list of example project ideas that might fit into this campaign]

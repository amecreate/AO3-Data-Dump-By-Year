# AO3-Data-Dump-By-Year
Python code for saving the official AO3 data dump into smaller files, filtered by year. (2008-2021)

Check out the original "Selective data dump for fan statisticians" on [AO3 website](https://www.archiveofourown.org/admin_posts/18804).

The data comes in two CSV files.

The first includes information about works:

creation date
language
word count
restricted or not
complete or not
associated tag IDs

__The python code [Works](Works.ipynb) filters it by year and saves to separate, smaller csv files.__

The second provides the key to the tag IDs:

tag ID
tag type (e.g. Warning, Fandom, Relationship)
tag name (unless the tag has fewer than 5 uses)
canonical or not
an approximate number of uses
merger ID (i.e. the tag's canonical version, if it has one)

__The python code [Tags](Tags.ipynb) filters it by type and saves to separate, smaller csv files.__




    


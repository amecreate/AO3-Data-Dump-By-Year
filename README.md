# AO3-Data-Dump-By-Year
Python code for saving the official AO3 data dump into smaller files, filtered by year. (2008-2021)

# Original Data

Check out the official post "Selective data dump for fan statisticians" on [AO3 website](https://www.archiveofourown.org/admin_posts/18804).

The data released by AO3 comes in two CSV files.

The first includes information about works:

- creation date
- language
- word count
- restricted or not
- complete or not
- associated tag IDs

The second provides the key to the tag IDs:

- tag ID
- tag type (e.g. Warning, Fandom, Relationship)
- tag name (unless the tag has fewer than 5 uses)
- canonical or not
- an approximate number of uses
- merger ID (i.e. the tag's canonical version, if it has one)

# Filtered Data

The python code [Works](Works.ipynb) filters the first file by year and saves to separate, smaller csv files.

The python code [Tags](Tags.ipynb) filters the second file by type and saves to separate, smaller csv files.

You can download these smaller csv files from [MEGA](https://mega.nz/folder/wkxiTD7S#-s0nBJVPIdXdhLGwcHDYDQ).
    
More analysis and data visualization can be found on my repo [AO3-Data-Vis](https://github.com/amecreate/ao3-data-vis) and my website [A Look Into AO3 Data](https://amecreate.github.io/ao3-data-vis/).

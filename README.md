# data4paprbag
This package provides trained classifiers to be used together with the package [paprbag](https://github.com/crarlus/paprbag).


# Available data
Data is stored in directory
[data](https://github.com/crarlus/data4paprbag/tree/master/data)
       

* __classifier_small_foldX.rda__ provides a trained pathogenicity classfier for cross validation fold _X_. The small classifier was built from 200,000 training reads

* __labels_foldX.rda__ provides a list of Bioproject accessions and their associated pathogenicity phenotype for the bacterial strains trained in fold _X_

* __Labels.rda__ provides a list of all Bioproject accessions and their associated labels.

* __classifier_foldX.rda__ The large classifiers for cross validation fold _X_ are supplied in the [release](https://github.com/crarlus/data4paprbag/releases). 

Note that each large classifier is approx. 250 MB and the package itsself (without the large classifiers) is 141 MB.

# Usage
Either download and install the package (via `devtools::install_github("crarlus/data4paprbag")`)

__or__ 

manually download the files of your choice from directory [data](https://github.com/crarlus/data4paprbag/tree/master/data)
and the [release](https://github.com/crarlus/data4paprbag/releases) tab.

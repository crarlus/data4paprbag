# data4paprbag
This package provides trained classifiers to be used together with the package [paprbag](https://github.com/crarlus/paprbag).


# Available data
Data is stored in directory
[data](https://github.com/crarlus/data4paprbag/tree/master/data)
       

_classifier_small_foldX.rda_ provides a trained pathogenicity classfier for fold X. The small classifier was built from 200,000 training reads

_labels_foldX.rda_ provides a list of Bioproject accessions and their associated pathogenicity phenotype for the bacterial strains trained in fold X

_Labels.rda_ provides a list of all Bioproject accessions and their associated labels.

# Usage
Either download and install the package (via `devtools::install_github("crarlus/data4paprbag")`)

or manually download the files of your choice from directory [data](https://github.com/crarlus/data4paprbag/tree/master/data)

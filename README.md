# EOS dataset

Utility to manage CMS datasets registerd in DBS and stored on a EOS Disk System.

## Installation

The utility requires a CMSSW environment and CVMFS for the Crab Library. The command is
python based and can be simply downloaded


    curl -LO https://raw.githubusercontent.com/dietrichliko/eos-dataset/main/eos-dataset
    chmod +x eos-dataset


## Usage

The command has following format:

    eos-dataset <command> [Options] 

supports folowing commands

* list    ... list a users dataset
* files   ... list content of a user dataset (use -l for attributes)
* verify  ... verify files associated to a user dataset (-c to verify also the adler32 checksum)
* remove  ... remove files from storage and mark the dataset as deleted

Further details on the commands and their options can be obtained 

    eos-dataset <command> --help


## Author

<Dietrich.Liko@oeaw.ac.at>

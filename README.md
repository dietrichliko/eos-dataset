# EOS dataset

Utility to manage CMS datasets registerd in DBS and stored on a EOS Disk System.

## Installation

The utility requires a CMSSW environment and CVMFS for the Crab Library. The command is
python based and can be simply downloaded

'''shell
curl -LO https:
chmod +x eos-dataset
'''

## Usage

The command has following format:

    eos-dataset <command> [Options] 

supports folowing commands

* list  
* files
* verify
* remove 

Further details on the commands and their options can be obtained 

    eos-dataset <command> --help


## Author

Dietrich Liko <Dietrich.Liko@oeaw.ac.at>
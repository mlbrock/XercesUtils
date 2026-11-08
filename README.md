# XercesUtils

## Description
Wrapper library around the Xerces C++ parser library for parsing XML documents.
																								 
## This Repository
https://github.com/mlbrock/XercesUtils

## Related Repositories
* UtilityOld (in https://github.com/mlbrock/UtilityOld)

## External Dependencies
### Git
* Any recent version of git.
### GNU C++ Compiler
* GNU g++ 4.1.2 through gcc 16.1.1 are supported.
### Boost
* Boost 1.32 through Boost 1.90 are supported.
### Xerces-c
* Xerces 3.0.0 and above are supported.

## How-to Build
### Install external dependencies:
* Install git
* Install GNU g++
* Install Boost
* Install Xerces-c (https://xerces.apache.org/xerces-c/)
### Get the related repositories and build them:
* Clone the related repositories:

    `git clone https://github.com/mlbrock/UtilityOld`

* Follow the build instructions in the related repositories README.md files.
### Get the current source distribution:
    git clone https://github.com/mlbrock/XercesUtils
### Change to the cloned top-level directory:
    cd XercesUtils
### Clean an existing build (if necessary):
    ./SimpleBuildDriver.sh clean
### Run the build script:
    ./SimpleBuildDriver.sh
### Check for build warnings or errors:
    grep -P '((warning)|(error)):' `ls -1 BuildResults.*|sort -r|head -n 1`


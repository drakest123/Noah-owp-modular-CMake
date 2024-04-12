# Noah-OWP-Modular CMake

This repo contains a CMake build environment for the refactored version of the Noah-MP community land surface model.

## Dependencies

Noah-OWP-Modular has been tested on Unix-based systems such as MacOS and Linux. Its only dependency is NetCDF Fortran.

This CMake project builds the codebase outside of the source directory tree.
Setup: copy these files to the matching noah-owp-modular directory structure.

## Usage
From noah-owp-modular directory type:
<pre>
mkdir ../build
cd ../build
cmake ../noah-owp-modular
cmake --build . -- VERBOSE=1
cd ../noah-owp-modular
../build/noah-owp-modular.exe run/namelist.input
</pre>
## Contents
<pre>
% pwd
noah-owp-modular
% ls -R
CMakeLists.txt		FindNetCDF.cmake	SECURITY.md		TODO			driver
CTestTestfile.cmake	README.md		TERMS.md		bmi			src

./bmi:
CMakeLists.txt

./driver:
CMakeLists.txt

./src:
CMakeLists.txt
</pre>
## Getting help

If you have questions, concerns, bug reports, etc., please file an issue in this repository's [Issue Tracker](https://github.com/NOAA-OWP/noah-owp-modular/issues).

## Getting involved

We encourage community involvement in code development. For more info, please check out our [CONTRIBUTING](CONTRIBUTING.md) document.


----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)


----

## Credits and references

1. This project was developed by Lynker in association with NOAA OWP.

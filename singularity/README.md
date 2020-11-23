# Containers changelog

## a
- Installs Ubuntu (bionic)
- Installs basic libraries
- Installs gdal

## b
a+
- Required R packages
  - And dependencies

## c
b+
- OpenCV 4.1
  - And [dependencies](https://docs.opencv.org/4.1.0/d7/d9f/tutorial_linux_install.html)
- FORCE [dependencies](https://force-eo.readthedocs.io/en/latest/setup/depend.html)
## d
c+
- R packages needed for makeDataCube
- FORCE dependencies
- python packages needed for makeDataCube
## e
d+
- R makeDataCube package (commit 971bb08)
- FORCE 

## f
e+
- pylandsat for python 3 with dependences

## g
f+
- BenchmarkRecovery package (commit 060dffc)
## h
f+
- R terra package 
- updated version of gdal 
- updated version of makeDateCube package (commit 02769e42849634739bf33c40f580ebb4906a253d)
## i
h+
- updated version of FORCE (note: part of the installation needs to be done in a sandbox (see comment in hi.def file))
- updated version of makeDateCube package

# Naming convention
![image](img/diagram.png)

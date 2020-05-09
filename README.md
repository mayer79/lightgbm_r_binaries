# lightGBM binaries
Binary [lightGBM](https://github.com/Microsoft/LightGBM) package for R Windows with the following relevant info

- Built under Windows 10
- CPU: i7 quadcore 
- Compiled with MSVC
- R versions: 3.4, 3.5, 3.6
- No GPU

The idea is to keep these binaries up to date for people without admin rights. 

The packages are build by first running in console

```
git clone --recursive https://github.com/microsoft/LightGBM
cd LightGBM
Rscript build_r.R
```
and then manually zipping the installed package in the R library.
 
## Installation
Depending on the R version, go for one of these guys:

- R 3.4.x: `install.packages("https://github.com/mayer79/lightgbm_r_binaries/raw/master/R_3_4_4/lightgbm_2_1_2/lightgbm.zip", repos = NULL)`

- R 3.5.x: `install.packages("https://github.com/mayer79/lightgbm_r_binaries/raw/master/R_3_5_0/lightgbm_2_2_3/lightgbm.zip", repos = NULL)`

- R 3.6.0: `install.packages("https://github.com/mayer79/lightgbm_r_binaries/raw/master/R_3_6_0/lightgbm_2_2_4/lightgbm.zip", repos = NULL)`

- R 3.6.3: `install.packages("https://github.com/mayer79/lightgbm_r_binaries/raw/master/R_3_6_3/lightgbm_2_3_2/lightgbm.zip", repos = NULL)`

- R 4.0.0: `install.packages("https://github.com/mayer79/lightgbm_r_binaries/raw/master/R_4_0_0/lightgbm_2_3_2/lightgbm.zip", repos = NULL)`

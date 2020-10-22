## Test environments
* local OS X install, R 4.0.2
* Ubuntu 16.04.6 LTS (on travis-ci), R 4.0.2
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs.

There were 2 NOTEs:

Flavor: r-devel-linux-x86_64-debian-gcc, r-devel-windows-ix86+x86_64
Check: CRAN incoming feasibility, Result: NOTE
 Maintainer: 'Rebecca Steorts <beka@stat.duke.edu>'

New submission

 Possibly mis-spelled words in DESCRIPTION:
   Fienberg (11:93)
   Sadinle (11:84)
   Steorts (11:66)
   TLSH (3:8, 11:58)
   Ventura (11:75)
   
The Title field starts with the package name.   

** running examples for arch 'x64' ... [17s] NOTE
Examples with CPU (user + system) or elapsed time > 10s
            user system elapsed
pp_weights 10.36   0.05   10.54


## Downstream dependencies
There are currently no downstream dependencies for this package.





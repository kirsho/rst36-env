# rst36-env


This file is a singularity definition file to create simg with conda  

It starts with a docker image of miniconda  

It allows direct creation of the env by specifying which package or with a .yml file  

unlock desired method by removing # and set variable (defname) or file name (xxxx.yml)   

future dev: if else, yml or package names as argument for `singularity build` command  

Image build with `sudo singularity build imagename.simg Singularity `  


conda yml file and singularity file for rstudio, r-3.6.0 and biocManager as installed on my machine.  

note that rstudio won't run in this Singularity image.  

follows this recipe for rstudio integration in a simg.  

script needs improvment, def and yml file allow simg build with this command locally in a folder

yml, def file and installed packages.md backed up in /setupfile



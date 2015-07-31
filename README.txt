How to test caRpools
====================

1. install Mageck according to the mageck website
2. install bowtie2 according to the bowtie2 website (set PATH!)
3. install pandoc according to pandoc.org website
4. install carPools package (caRpools.tar.gz)
5. copy the folder to where you want to do the analysis.
if this is not your R working directory, you need to pass the working directory to caRpools by either starting it with use.caRpools() or set it manually before using setwd("YOUR WORKING DIR").
6. Check that everything is in place by
check.caRpools()
7. If everything is in place and functional, you can start caRpools Report generation.
Either by open the template Rmd file and clicking on KNIT
or by telling R to start report generation by use.caRpools().

In case you changed the MIACCS file name, the R working directory or the Rmd template file name, pass on the new parameters to carpools!
use.caRpools(work.dir="your new work dir", miaccs="new miaccs file name", file="new Rmd template file name").

MIACCS and Rmd template file must be in the working directory!

You can skip the check for correct caRpools installation by check=FALSE.

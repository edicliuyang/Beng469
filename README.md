


# BENG 469 Lab 7-1 - instructions (Spatial transcriptomics analysis of DBiT-seq data)

In this computational lab, we will go through data analysis and visualization for spatial transcriptomics data using the example data in the [DBiT-seq Paper](https://www.sciencedirect.com/science/article/pii/S0092867420313908?via%3Dihub).

### Pre-lab task:
1. Download "DBiT_seq_analysis.R" under "3-6-2024_ L7-1 _ Spatial transcriptomics mapping (1)/" from Files on Canvas.

2. Upload the files to your project folder on HPC:

Open McCleary OnDemand at [beng469.ycrc.yale.edu](https://beng469.ycrc.yale.edu)  in a browser window, and go to **Files** menu and click open your project folder (/gpfs/gibbs/project/beng469/beng469_YourNetID).

Then create a new directory called "**Lab7_1**" and upload the files ("DBiT_seq_analysis.R") under this new directory. 

### During the lab session (Thursday):

1. Open OOD at [beng469.ycrc.yale.edu](https://beng469.ycrc.yale.edu) in your web browser (make sure that you are on Yale Secure Network or Yale VPN).
2. Launch an Rstudio-server session:
Go to the Rstudio-server initialization page, and specify the parameters/resources as follows:

| Parameters      | Values |
| ----------- | ----------- |
| R version      | R/4.2.0-foss-2020b       |
| Number of hours   | 2        |
| Number of CPU cores per node   | 1        |
| Memory per CPU core in GiB   | 10       |
| Partitions   | devel / day / education     |

Then click Launch to launch an Rstudio session, and connect the Rstudio session once it’s started

3. Open the R code:

Once you are inside Rstudio, use the file navigation panel at the bottom right to click open your **project**/ folder then the **Lab7_1**/ folder you created, then click open “**DBiT_seq_analysis.R**” . 

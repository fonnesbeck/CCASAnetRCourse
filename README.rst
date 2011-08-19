CCASAnet Short Course: Introduction to R
========================================

This is a repository for files related to the CCASAnet short course on 1 Sept, 2011 in Mexico City. The goal of this course is to expose CCASAnet members to the R statistical programming language.

The primary data file in the repository ``haart.csv`` is a simulated dataset of highly active antiretroviral therapy (HAART) outcomes. As such, it is not information from real patients, but is included only for the purposes of a statistical exercise.

The variables are defined as follows:

- male: 1 if male, 0 otherwise
- age: Age at HAART initiation
- aids: 1 if AIDS prior to HAART initiation, 0 otherwise
- cd4baseline: CD4 measurement closest to HAART initiation; not more than 6 months prior to or 7 days after the date of starting HAART
- logvl: Log10-transformed HIV-1 plasma viral load measurement closest to HAART initiation; no more than 6 months prior to or 0 days after date of starting HAART
- weight: Weight in kg closest to HAART initiation within +/- 30 days
- hemoglobin: Hemoglobin (g/dL) closest to HAART initiation within +/- 30 days
- init.reg: Initial regimen
- init.date: Date of HAART initiation
- last.visit: Date of last visit
- death: 1 if died, 0 otherwise
- date.death: Date of death (NA if not applicable)
- event: 1 if died within 365 days of HAART initiation, 0 otherwise
- followup: Days of follow-up after HAART initiation; set at 365 days if length of follow-up was greater than 365 days  
- lfup: 1 if lost to follow-up in the first year, 0 otherwise. A person was considered lost to follow-up if status (alive or dead) 365 days after HAART initiation was not known and if their last visit occurred more than 365 days before the closing date of the database.  The closing date of the: database was defined separately for each site as the date of the most recent follow-up recorded in the database.
- pid: Patient identifier

Required Software
-----------------

Course attendees should install both the `R application <http://cran.r-project.org/>`_ itself and `RStudio <http://rstudio.org>`_, an integrated development environment that many users prefer to use when interacting with R.

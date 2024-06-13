# LPGM
Power simulations for PRISMA: latent profile growth model of school readiness, instructional quality, and the development of Math of self-regulation in first-graders. Project title: Interactions of primary schoolers' readiness and instructional quality on the development of self-regulation and mathematical competence

Folders:
- `Scripts` contains R-scripts for data simulations, analyses of simulated data and analyses of simulation results
    `LPA` contains R-scripts for latent profile analysis without growth structure or multilevel structure
    `LPGM` contains R-scripts for latent profile growth model with growth structure without multilevel structure

Files in `Scripts`-folders:
-   `Step1_Creating_Simulated_Data_sets_LPGM.Rmd` R markdown: Create simulated data sets via MplusAutomation
-   `Step2_Analysis_of_simulated_data_sets_LPGM.Rmd` R markdown: Analyse simulated data sets via MplusAutomation
-   `Step3_Analysis_of_results_LPGM.Rmd` R markdown: Analyse results from analyses of simulated data sets to examine statistical power

Files in `Results`-folder:
- PNGs of results for different fit statistics plus overview of all fit statistics in one figure (`plots_fit.png`)

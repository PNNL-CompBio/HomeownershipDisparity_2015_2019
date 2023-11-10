# Homeownership_disparity
Supplemental Material for submitted work on homeownership disparity demographics in US Counties.

Due to file size limits, most large datafiles are tracked via GitHub LFS. Please refer to the link below for additional information and installation to access all associated files.
https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github

Files and folders are arranged as follows:

Data_preprocessing_and_EDA
- Folders containing the original data from our sources, data cleaning, and the merging of datafiles into a master spreedsheet for running a random forest model.

Data_preprocessing_and_EDA Subfolders
- og_data: original data files. Subfolders contain each dataset.
- og_data_processing: cleaning and pre-processing of data files. Subfolders contain processing for each dataset. Some cross-over is in the Response Data subfolder, as the census data is combined with homeownership data to determine equity in a county. Some un-used datasets, such as housing_permits, are included here, but not in the final model. Additionally, many of these files contain visualizations in .rmds that were used to explore the data initially. Large trelliscope visualizations can be rendered by running the associated code in these files, but are not included directly in the repository to preserve storage.
- all_data_merge: merging data files before random forest. All cleaned data con be found in this folder as well as a copy of the data used in random forest models.

Rf_model
- Contains a single rmd for generating the random forest model and extracting results, as presented in associated csvs.

Visualizations
- Folders containing visualizations used in manuscript and additional plots.

Visualizations Subfolders:
- Figures: Manuscript figures, rmd to make figures, and associated .csv files used to make said figures. Large trelliscope visualizations can be rendered by running the associated code in this rmd file, but are not included directly in the repository to preserve storage.
- Plots: EDA of some of the individual datasets in a variety of plot types.

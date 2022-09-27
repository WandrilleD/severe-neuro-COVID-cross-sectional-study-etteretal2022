# Computational documents of "Severe Neuro-COVID is associated with peripheral immune signatures, autoimmunity and neurodegeneration: a prospective cross-sectional study" by Etter et al. 2022

This repository contains the html rendering of the computational documents pertaining to the data analysis of  "Severe Neuro-COVID is associated with peripheral immune signatures, autoimmunity and neurodegeneration: a prospective cross-sectional study" by Etter et al. 2022 (correct and insert link when published).

The associated data is available as supplementary material of the article.

1. [01_OLINK_data_wrangling](01_OLINK_data_wrangling.html) : Imputation of the OLINK cytokine panel
2. [02_OLINK_data_marginalization](02_OLINK_data_marginalization.html) : Marginalization of the OLINK cytokine panel on age and sex
3. [03_OLINK_data_heatmaps](03_OLINK_data_heatmaps.html) : Heatmaps of the cytokine panels measured from plasma and CSF samples. Fig S2
4. [04_OLINK_data_roseplot](04_OLINK_data_roseplot.html) : Roseplots of the cytokine panels measured from plasma and CSF samples. Fig4A
5. [05_OLINK_data_boxplot](05_OLINK_data_boxplot.html) :  Test for significant different between subgroups (controls, I, II ,III) for each of the molecule in the cytokine panels measured from plasma and CSF samples. Fig5.
6. [06_OLINK_data_PCA_plots](06_OLINK_data_PCA_plots.html) : PCA of the data of the cytokine panels measured from plasma and CSF samples. Fig 4B, supplementary data file 5
7. [07_OLINK_data_PLASMA_CSF_correlation](07_OLINK_data_PLASMA_CSF_correlation.html) : Explore and represent the correlation between measurements in the plasma and CSF among the cytokine panels. Supp. Fig 5
8. [08_OLINK_data_CSF_plasma_ratios](08_OLINK_data_CSF_plasma_ratios.html) : Explore and visualize the ratio between the plasma and CSF measurements of the cytokine panels. Fig S4, Supp. Data file 3
9. [09_OLINK_data_stageIII_prediction_using_ROC_AUC_and_RF](09_OLINK_data_stageIII_prediction_using_ROC_AUC_and_RF.html) : Finding which molecules are good predictors of stage III among the cytokine panels collected on the CSF and plasma samples using univariate ROC-AUC and Random Forest. Fig 6
10. [10_routine_inflammatory_parameters_marginalization](10_routine_inflammatory_parameters_marginalization.html) : Marginalization of the effect of sex and age for each of the routine inflammatory parameters. Fig2A and Fig2B
11. [11_routine_inflammatory_parameters_boxplot](11_routine_inflammatory_parameters_boxplot.html) :  Test for significant different between subgroups (controls, I, II ,III) for each of the routine inflammatory parameters. Fig S2A
12. [12_immunoglobulin_data_marginalization](12_immunoglobulin_data_marginalization.html) : Marginalization of the immunoglobulin on age and sex. Fig2C And Fig S1
13. [13_immunoglobulin_data_CSF_boxplot](13_immunoglobulin_data_CSF_boxplot.html) : Boxplot for the CSF immunoglobulins. Fig2C
14. [14_immunoglobulin_data_Plasma_boxplot](14_immunoglobulin_data_Plasma_boxplot.html) : Boxplot for the Plasma immunoglobulins. Fig S1B
15. [15_immunoglobulin_data_CSF_total_Ig_boxplot](15_immunoglobulin_data_CSF_total_Ig_boxplot.html) : Boxplots for total CSF and plasma IgG/A/M and albumin levels. Fig S1 C and D
16. [16_immunoglobulin_data_CSF_hMOG_NF155_boxplot](16_immunoglobulin_data_CSF_hMOG_NF155_boxplot.html) : Boxplot visualizations for the Humanized MOG- (hMOG) and NF155-specific monoclonal antibodies, which were included as positive controls. Fig S1A
17. [17_immunoglobulin_data_dimension_reduction_visualisation](17_immunoglobulin_data_dimension_reduction_visualisation.html): Kruskal's non-metric multidimensional scaling to visualise immunoglobuline datasets (CSF and plasma). Fig2B
18. [18_top_PlasmaCSFprot_vs_SeverityIndex](18_top_PlasmaCSFprot_vs_SeverityIndex.html): Association between severity score and CSF and plasma mediators significantly differing across groups (see Fig5) Fig6A
19. [19_LongCovid_predictors](19_LongCovid_predictors.html): association between CSF and plasma molecules and long-COVID. Fig8
20. [20_CSF_plasma_ratio_heatmaps](20_CSF_plasma_ratio_heatmaps.html): heatmaps of CSF/plasma ratio. Fig S4


## Dependencies

Documents 1 to 16 correspond to python notebooks whose dependencies are detailed in the [etter_env.yml](etter_env.yml) file (which can be used to create an appropriate conda environment directly).

Documents 17 to 20 correspond to R markdown notebooks.


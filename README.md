

Folders:

* *2017_E65_MP-dirty*
 * Mouth-pippeted data
 * initial_attempts -- ignore
 * second_attempt -- looking for biological variability 
* *2017_E65_MP-clean*
 * Mouth-pippeted data, clean approach. 
 * Hemberg workflow
* *2018_E65_HP-TODO*
 * Hand-picked data (skipped due to priority given to E725 data)
* 2018_E725_FACS-multi*
 * 0_test_matrix\* - comparing different workflow parameters
 * analy_\* - analyses of interest (presented in last meeting)


```
├── 2017_E65_MP-dirty
│   ├── initial_attempts
│   │   ├── 2_CLEMENS_postanaly.ipynb
│   │   ├── 2_postanal_lowres_singlebatch.ipynb
│   │   ├── 3_viz_conf_norm.ipynb
│   │   ├── 4_confounder_removal.ipynb
│   │   ├── 5_otherNormTechniques.ipynb
│   │   ├── 6_normalise_again.ipynb
│   │   ├── 7_sc3_pcareduce_tsnekmeans.ipynb
│   │   ├── 8_featureselection.ipynb
│   │   ├── 9_pseudotime_DE.ipynb
│   │   ├── General.ipynb
│   │   ├── RaceID_pipeline.ipynb
│   │   ├── Suerat_pipeline.ipynb
│   │   └── test_workflow
│   └── second_attempt
│       ├── a_qcandnorm_comparison_of_genefilters.ipynb
│       ├── a_qcandnorm.ipynb
│       ├── b_confounders.ipynb
│       ├── c_clustering.ipynb
│       ├── d_plotSC3clusters.ipynb
│       ├── e_sueratclust.ipynb
│       ├── plots
│       └── rds
├── 2017_E65_MP-clean       
│   ├── 1_filter_cells.ipynb
│   ├── 2_filter_genes.ipynb
│   ├── 3_normalisation.ipynb
│   ├── 4_genes_of_interest.ipynb
│   ├── 5_remove_cellcycle_effect.ipynb
│   ├── 6_deconfounding.ipynb
│   ├── 7_clustering.ipynb
│   ├── 8_clustering_plots.ipynb
│   ├── imgs
│   ├── load_matrix.R
│   ├── rds_checkpoints
│   ├── test
│   │   └── backup.form
│   └── TODO.txt
├── 2018_E65_HP-TODO
└── 2018_E725_FACS-multi
    ├── 0_test_matrix_raceid3_basicrun2.ipynb
    ├── 0_test_matrix_raceid3_basicrun.ipynb
    ├── 0_test_matrix_raceid3_different_filtering.ipynb
    ├── 0_test_matrix_raceid3_fullrun.ipynb
    ├── 0_test_matrix_scater_vs_raceid3.ipynb
    ├── analy_hemberg.ipynb
    ├── analy_monocle_clust_pstime.ipynb
    ├── analy_raceid3_compr.ipynb
    ├── analy_seurat_highfilt_wandwo_cCcP.ipynb
    ├── checkpoint_biomart
    ├── checkpoint_rds
    ├── source
    └── __vennlogs
```

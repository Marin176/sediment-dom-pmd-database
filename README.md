# fenhe-sediment-dom-pmd-database
This repository contains a supplementary potential mass difference (PMD) annotation table used to support sediment DOM transformation analysis in an urbanized catchment.

The table compiles frequently detected PMDs from broad location categories, including outlet-associated sediments and receiving sediments. PMDs were screened using the getrda() function of the PMD package. The repository is intended to provide transparency on the PMD values and literature references used for putative transformation interpretation.

Contents
pmd_database.csv
PMD values, putative transformation annotations, interpretation notes, instrument type, study matrix, reference type, and supporting references.
pmd_presence_by_location_type.csv
Broad presence/absence summary of PMDs across location categories.
pmd_data_dictionary.csv
Column descriptions for the included tables.
Notes

The PMD annotations are provided as putative transformation candidates and should not be interpreted as confirmed reaction assignments. This repository does not include raw FT-ICR MS data, raw sample-level intensity matrices, site coordinates, or full molecular formula datasets.

Method reference

PMDs were screened using the PMD package, following the getrda() workflow described here:
https://yufree.cn/en/2024/05/29/reactomics-analysis-for-ms-only-data/

Referenced literature
(1) Wang, L.; Lin, Y.; Li, J.; Yu, Q.; Xu, K.; Ren, H.; Geng, J. Deciphering Microbe-Mediated
Dissolved Organic Matter Reactome in Wastewater Treatment Plants Using Directed Paired
Mass Distance. Environ. Sci. Technol. 2024, 58 (1), 739–750.
https://doi.org/10.1021/acs.est.3c06871.
(2) Linne, B. M.; Tello, E.; Simons, C. T.; Peterson, D. G. Chemical Characterization and
Sensory Evaluation of a Phenolic-Rich Melanoidin Isolate Contributing to Coffee
Astringency. Food Funct. 2025, 16 (7), 2870–2880. https://doi.org/10.1039/D4FO04934A.
(3) Lobodin, V. V.; Nyadong, L.; Ruddy, B. M.; Curtis, M.; Jones, P. R.; Rodgers, R. P.; Marshall,
A. G. DART Fourier Transform Ion Cyclotron Resonance Mass Spectrometry for Analysis of
Complex Organic Mixtures. International Journal of Mass Spectrometry 2015, 378, 186–
192. https://doi.org/10.1016/j.ijms.2014.07.050.
(4) Urban, J.; Jin, C.; Thomsson, K. A.; Karlsson, N. G.; Ives, C. M.; Fadda, E.; Bojar, D.
Predicting Glycan Structure from Tandem Mass Spectrometry via Deep Learning. Nat
Methods 2024, 21 (7), 1206–1215. https://doi.org/10.1038/s41592-024-02314-6.
(5) Danczak, R. E.; Goldman, A. E.; Chu, R. K.; Toyoda, J. G.; Garayburu-Caruso, V. A.; Tolić, N.;
Graham, E. B.; Morad, J. W.; Renteria, L.; Wells, J. R.; Herzog, S. P.; Ward, A. S.; Stegen, J. C.
Ecological Theory Applied to Environmental Metabolomes Reveals Compositional
Divergence despite Conserved Molecular Properties. Science of The Total Environment
2021, 788, 147409. https://doi.org/10.1016/j.scitotenv.2021.147409.
(6) Wu, M.; Li, P.; Li, G.; Liu, K.; Gao, G.; Ma, S.; Qiu, C.; Li, Z. Using Potential Molecular
Transformation To Understand the Molecular Trade-Offs in Soil Dissolved Organic Matter.
Environ. Sci. Technol. 2022, 56 (16), 11827–11834.
https://doi.org/10.1021/acs.est.2c01137.
(7) Naim, A.; Hubert-Roux, M.; Cirriez, V.; Welle, A.; Vantomme, A.; Kirillov, E.; Carpentier, J.-F.;
Giusti, P.; Afonso, C. Characterization of Modified Methylaluminoxane by Ion Mobility
Spectrometry Mass Spectrometry and Ultra-High Resolution Fourier-Transform Ion
Cyclotron Resonance Mass Spectrometry. New J. Chem. 2023, 47 (46), 21244–21252.
https://doi.org/10.1039/D3NJ03877G.
(8) Yu, L.; Xiong, Y.-M.; Polfer, N. C. Periodicity of Monoisotopic Mass Isomers and Isobars in
Proteomics. Anal. Chem. 2011, 83 (20), 8019–8023. https://doi.org/10.1021/ac201624t.
(9) Ayala-Ortiz, C.; Graf-Grachet, N.; Freire-Zapata, V.; Fudyma, J.; Hildebrand, G.;
AminiTabrizi, R.; Howard-Varona, C.; Corilo, Y. E.; Hess, N.; Duhaime, M. B.; Sullivan, M. B.;
Tfaily, M. M. MetaboDirect: An Analytical Pipeline for the Processing of FT-ICR MS-Based
Metabolomic Data. Microbiome 2023, 11 (1), 28. https://doi.org/10.1186/s40168-023-
01476-3.
(10) Oberleitner, D.; Schmid, R.; Schulz, W.; Bergmann, A.; Achten, C. Feature-Based Molecular
Networking for Identification of Organic Micropollutants Including Metabolites by Non-
Target Analysis Applied to Riverbank Filtration. Anal Bioanal Chem 2021, 413 (21), 5291–
5300. https://doi.org/10.1007/s00216-021-03500-7.
(11) Gicquel, T.; Pelletier, R.; Bourdais, A.; Ferron, P.-J.; Morel, I.; Allard, P.-M.; Le Daré, B.
Interest of Molecular Networking in Fundamental, Clinical and Forensic Toxicology: A
State-of-the-Art Review. TrAC Trends in Analytical Chemistry 2024, 172, 117547.
https://doi.org/10.1016/j.trac.2024.117547.
(12) Ma, Y.; Kind, T.; Yang, D.; Leon, C.; Fiehn, O. MS2Analyzer: A Software for Small Molecule
Substructure Annotations from Accurate Tandem Mass Spectra. Anal. Chem. 2014, 86 (21),
10724–10731. https://doi.org/10.1021/ac502818e.
(13) Cheng, C.; Yang, M.; Yu, K.; Guan, S.; Tao, S.; Millar, A.; Pang, X.; Guo, D. Identification of
Metabolites of Ganoderic Acid D by Ultra-Performance Liquid
Chromatography/Quadrupole Time-of-Flight Mass Spectrometry. Drug Metabolism and
Disposition 2012, 40 (12), 2307–2314. https://doi.org/10.1124/dmd.112.047506.
(14) Aron, A.; Gentry, E.; Mcphail, K.; Nothias, L.-F.; Nothias-Esposito, M.; Bouslimani, A.;
Petras, D.; Gauglitz, J.; Sikora, N.; Vargas, F. Reproducible Molecular Networking of
Untargeted Mass Spectrometry Data Using GNPS.
(15) Hess, S. Sample Preparation Guide for Mass Spectrometry–Based Proteomics | LCGC
International. https://www.chromatographyonline.com/view/sample-preparation-guide-
mass-spectrometry-based-proteomics-0 (accessed 2026-04-23).
(16) Sato, H.; Nakamura, S.; Teramoto, K.; Sato, T. Structural Characterization of Polymers by
MALDI Spiral-TOF Mass Spectrometry Combined with Kendrick Mass Defect Analysis. J.
Am. Soc. Mass Spectrom. 2014, 25 (8), 1346–1355. https://doi.org/10.1007/s13361-014-
0915-y.

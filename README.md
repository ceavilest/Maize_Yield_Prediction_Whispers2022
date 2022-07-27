# Maize_Yield_Prediction_Whispers2022
Supplemental Material for MAIZE YIELD PREDICTION BASED ON MULTI-MODALITY REMOTE SENSING AND LSTM MODELS IN NITROGEN MANAGEMENT PRACTICE TRIALS

## Table Hyperspectral Indices Extracted

No. |Hyperspectal Index |Formula |Name
----|-------------------|:------:|-----
1|NDVI705| $\LARGE\frac{\rho_{750}-\rho_{705}}{\rho_{750}+\rho_{705}}$ |Red Edge Normalized Difference Vegetation Index [^1]
2|mNDVI705|$\LARGE\frac{\rho_{750}-\rho_{705}}{\rho_{750}+\rho_{705}-2\rho_{445}}$|Modified Red Edge Normalized Difference Vegetation Index. [^1]
3|mSR705|$\LARGE\frac{\rho_{750}-\rho_{445}}{\rho_{705}-\rho_{445}}$|Modified Red Edge Simple Ratio Index [^2]
4|GNDVI|$\LARGE\frac{\rho_{750}-\rho_{550}}{\rho_{750}+\rho_{550}}$|Green Difference Vegetation Index [^2]
5|RNDVI|$\LARGE\frac{\rho_{800}-\rho_{670}}{\rho_{800}+\rho_{670}}$|Relative Normalized Difference Vegetation Index [^3]
6|NDCI|$\LARGE\frac{\rho_{762}-\rho_{527}}{\rho_{762}+\rho_{527}}$|Normalized Difference Chlorophyll Index [^4]
7|Datt1|$\LARGE\frac{\rho_{850}-\rho_{710}}{\rho_{850}-\rho_{680}}$|Datt Water Content Index [^5]
8|Datt2|$\LARGE\frac{\rho_{850}}{\rho_{710}}$|Datt Water Content Index [^5]
9|Datt3|$\LARGE\frac{\rho_{754}}{\rho_{704}}$|Datt Water Content Index [^5]
10|Carte1|$\LARGE\frac{\rho_{695}}{\rho_{420}}$|Carte Ratios of Leaf  Reflectance [^6]
11|Carte2|$\LARGE\frac{\rho_{695}}{\rho_{760}}$|Carte Ratios of Leaf  Reflectance [^6]
12|Carte3|$\LARGE\frac{\rho_{605}}{\rho_{760}}$|Carte Ratios of Leaf  Reflectance [^6]
13|Carte4|$\LARGE\frac{\rho_{710}}{\rho_{760}}$|Carte Ratios of Leaf  Reflectance [^6]
14|Carte5|$\LARGE\frac{\rho_{695}}{\rho_{670}}$|Carte Ratios of Leaf  Reflectance [^6]
15|SR800680|$\LARGE\frac{\rho_{800}}{\rho_{680}}$|Simple Band Ratio [^7]
16|SR675700|$\LARGE\frac{\rho_{675}}{\rho_{700}}$|Simple Band Ratio [^7]
17|SR700670|$\LARGE\frac{\rho_{700}}{\rho_{670}}$|Simple Band Ratio [^7]
18|SR750700|$\LARGE\frac{\rho_{750}}{\rho_{700}}$|Simple Band Ratio [^7]
19|SR752690|$\LARGE\frac{\rho_{752}}{\rho_{690}}$|Simple Band Ratio [^7]
20|SR750550|$\LARGE\frac{\rho_{750}}{\rho_{550}}$|Simple Band Ratio [^7]
21|SR750710|$\LARGE\frac{\rho_{750}}{\rho_{710}}$|Simple Band Ratio [^7]
22|NVI|$\LARGE\frac{\rho_{777}-\rho_{747}}{\rho_{673}}$ |Normalized Vegetation Index [^8]
23|EVI|$\LARGE\frac{2.5(\rho_{800}-\rho_{670})}{\rho_{800}+6\rho_{670}+7.5\rho_{475}+1}$|Enhanced Vegetation Index [^9]
24|OSAVI|$\LARGE\frac{1.16(\rho_{800}-\rho_{670})}{0.16+\rho_{800}+\rho_{670}}$|Optimized Soil-Adjusted Vegetation Index [^10]
25|OSAVI2|$\LARGE\frac{1.16(\rho_{750}-\rho_{705})}{0.16+\rho_{750}+\rho_{705}}$|Optimized Soil-Adjusted Vegetation Index [^10]
26|TCARI|$\large 0.5+3[(\rho_{700}-\rho_{670})-0.2(\rho_{700}-\rho_{550})(\frac{\rho_{700}}{\rho_{670}})]$|Transformed Chlorophyll Absorption in Reflectance [^11]
27|TCARI2|$\large 3[(\rho_{750}-\rho_{705})- 0.2(\rho_{750}-\rho_{550})*(\frac{\rho_{750}}{\rho_{705}})]$|Transformed Chlorophyll Absorption in Reflectance [^11]
28|MCARI|$\large 4[(\rho_{700}-\rho_{670})-0.2(\rho_{700}-\rho_{550})]*(\frac{\rho_{700}}{\rho_{670}})$|Modified Chlorophyll Absorption in Reflectance Index [^12]
29|TVI|$\large 0.5[120(\rho_{750}-\rho_{550})-2.5(\rho_{670}-\rho_{550})]$|Triangular Vegetation Index [^13]
30|SPVI|$\large 0.4*3.7(\rho_{800}-\rho_{670})-1.2\mid\rho_{530}-\rho_{670}\mid$|Spectral Polygon Vegetation Index [^14]
31|REP|$\large 700+40*[\frac{(\rho_{670}-\rho_{780})}{2}-\frac{(\rho_{700}}{\rho_{740}-\rho_{700}})]$|Red Edge Position Index [^15]
32|PRI|$\LARGE\frac{\rho_{531}-\rho_{570}}{\rho_{531}+\rho_{570}}$|Photochemical Reflectance Index [16]
33|RI1db|$\LARGE\frac{\rho_{735}}{\rho_{720}}$|Ratio Index [^17]
34|VOG1|$\LARGE\frac{\rho_{740}}{\rho_{720}}$|Vogelmann Red Edge Index [^18]
35|VOG2|$\LARGE\frac{\rho_{734}-\rho_{747}}{\rho_{715}+\rho_{726}} $|Vogelmann Red Edge Index [^18]
36|VOG3|$\LARGE\frac{\rho_{734}-\rho_{747}}{\rho_{715}+\rho_{720}} $|Vogelmann Red Edge Index [^18]
37|RDVI|$\LARGE\frac{\rho_{800}-\rho_{670}}{\sqrt{\rho_{800}+\rho_{670}}}$|Renormalized Difference Vegetation Index [^19]
38|MSAVI|$\large 0.5[2(\rho_{800}+1-\sqrt{(2\rho_{800}+1)^2}-1.2\mid\rho_{530}-\rho_{670}\mid] $ |Modified Soil Adjusted Vegetation Index [^20]
39|MCARI2|$\large [(\rho_{750}-\rho_{705})-0.2(\rho_{700}-\rho_{550})]*(\frac{\rho_{750}}{\rho_{705}})$|Modified Chlorophyll Absorption in Reflectance Index [^12]
40|MCARI2/OSAVI2|$\large\frac{MCARI2}{OSAVI2}$|MCARI2/OSAVI2 [^21]
41|PSRI|$\LARGE\frac{\rho_{678}-\rho_{500}}{\rho_{750}}$|Plant Senescence Reflectance Index  [^22]
42|HBSI1|$\LARGE\frac{\rho_{855}-\rho_{682}}{\rho_{855}+\rho_{682}}$|Hyperspectral Biomass and Structural Index [^23]
43|HBSI2|$\LARGE\frac{\rho_{910}-\rho_{682}}{\rho_{910}+\rho_{682}}$|Hyperspectral Biomass and Structural Index [^23]
44|HBSI3|$\LARGE\frac{\rho_{550}-\rho_{682}}{\rho_{550}+\rho_{682}}$|Hyperspectral Biomass and Structural Index [^23]
45|DCNI|$\LARGE\frac{(\rho_{720}-\rho_{700})*(\rho_{700}-\rho_{670})}{\rho_{720}-\rho_{670}+0.03}$|Double-peak Canopy Nitrogen Index [^24]
46|HBCI8|$\LARGE\frac{\rho_{550}-\rho_{515}}{\rho_{550}+\rho_{515}}$|Hyperspectral Biochemical Indices [^23]
47|HBCI9|$\LARGE\frac{\rho_{550}-\rho_{490}}{\rho_{550}+\rho_{490}}$|Hyperspectral Biochemical Indices [^23]
48|HREI15|$\LARGE\frac{\rho_{855}-\rho_{720}}{\rho_{855}+\rho_{720}}$|Hyperspectral Red Edge Indices [^23]
49|HREI16|$\LARGE\frac{\rho_{910}-\rho_{705}}{\rho_{910}+\rho_{705}}$|Hyperspectral Red Edge Indices [^23]
50|NDRE|$\LARGE\frac{\rho_{790}-\rho_{720}}{\rho_{790}+\rho_{720}}$|Normalized Difference Vegetation Indexes [^25]


### References

[^1]:	A. A. Gitelson and M. N. Merzlyak, “Remote sensing of chlorophyll concentration in higher plant leaves,” Adv. Space Res., vol. 22, no. 5, pp. 689–692, Jan. 1998, doi: 10.1016/S0273-1177(97)01133-2.

[^2]:	A. Gitelson and M. N. Merzlyak, “Spectral Reflectance Changes Associated with Autumn Senescence of Aesculus hippocastanum L. and Acer platanoides L. Leaves. Spectral Features and Relation to Chlorophyll Estimation,” J. Plant Physiol., vol. 143, no. 3, pp. 286–292, Mar. 1994, doi: 10.1016/S0176-1617(11)81633-0.

[^3]:	P. Li, L. Jiang, Z. Feng, S. Sheldon, and X. Xiao, “Mapping rice cropping systems using Landsat-derived Renormalized Index of Normalized Difference Vegetation Index (RNDVI) in the Poyang Lake Region, China,” Front. Earth Sci., vol. 10, no. 2, pp. 303–314, Jun. 2016, doi: 10.1007/s11707-016-0545-8.

[^4]:	S. Mishra and D. R. Mishra, “Normalized difference chlorophyll index: A novel model for remote estimation of chlorophyll-a concentration in turbid productive waters,” Remote Sens. Environ., vol. 117, pp. 394–406, Feb. 2012, doi: 10.1016/j.rse.2011.10.016.

[^5]:	B. Datt, “Remote Sensing of Water Content in Eucalyptus Leaves,” Aust. J. Bot., vol. 47, no. 6, p. 909, 1999, doi: 10.1071/BT98042.

[^6]:	G. A. CARTER, “Ratios of leaf reflectances in narrow wavebands as indicators of plant stress,” Int. J. Remote Sens., vol. 15, no. 3, pp. 697–703, Feb. 1994, doi: 10.1080/01431169408954109.

[^7]:	D. Sims and J. Gamon, “Relationships Between Leaf Pigment Content and Spectral Reflectance Across a Wide Range of Species, Leaf Structures and Developmental Stages,” Remote Sens. Environ., vol. 81, pp. 337–354, Aug. 2002, doi: 10.1016/S0034-4257(02)00010-X.

[^8]:	X. Li, X. Liu, M. Liu, C. Wang, and X. Xia, “A hyperspectral index sensitive to subtle changes in the canopy chlorophyll content under arsenic stress,” Int. J. Appl. Earth Obs. Geoinformation, vol. 36, pp. 41–53, Apr. 2015, doi: 10.1016/j.jag.2014.10.017.

[^9]:	A. Huete, K. Didan, T. Miura, E. P. Rodriguez, X. Gao, and L. G. Ferreira, “Overview of the radiometric and biophysical performance of the MODIS vegetation indices,” Remote Sens. Environ., vol. 83, no. 1–2, pp. 195–213, Nov. 2002, doi: 10.1016/S0034-4257(02)00096-2.

[^10]:	G. Rondeaux, M. Steven, and F. Baret, “Optimization of soil-adjusted vegetation indices,” Remote Sens. Environ., vol. 55, no. 2, pp. 95–107, Feb. 1996, doi: 10.1016/0034-4257(95)00186-7.

[^11]:	D. Haboudanea, J. R. Millera, E. Patteyc, P. J. Zarco-tejadad, and I. B. Strachane, “vegetation indices (Normalized Difference Vegetation Index [NDVI], Renormalized Difference Vegetation Index [RDVI], Modified Simple ent 90Vegetation Index [TVI], and Modified Chlorophyll Absorption Ratio Index [MCARI]) and to design new ones (MTVI1, MCARI.” 

[^12]:	C. Daughtry, C. Walthall, M. S. Kim, E. B. D. Colstoun, and J. McMurtrey, “Estimating Corn Leaf Chlorophyll Concentration from Leaf and Canopy Reflectance,” 2000, doi: 10.1016/S0034-4257(00)00113-9.

[^13]:	N. H. Broge and E. Leblanc, “Comparing prediction power and stability of broadband and hyperspectral vegetation indices for estimation of green leaf area index and canopy chlorophyll density,” Remote Sens. Environ., vol. 76, no. 2, pp. 156–172, May 2001, doi: 10.1016/S0034-4257(00)00197-8.

[^14]:	M. Vincini, “Narrow-Band Vegetation Indexes from Hyperion and Directional Chris/Proba Data for Canopy Chlorophyll Density Estimation in Maize,” Jan. 2007, Accessed: Jul. 26, 2022. [Online]. Available: https://www.academia.edu/57179926/Narrow_Band_Vegetation_Indexes_from_Hyperion_and_Directional_Chris_Proba_Data_for_Canopy_Chlorophyll_Density_Estimation_in_Maize

[^15]:	J. G. P. W. Clevers, “Imaging Spectrometry in Agriculture - Plant Vitality And Yield Indicators,” Eurocourses Remote Sens., p. 193, Jan. 1994.

[^16]:	J. Peñuelas, M. F. Garbulsky, and I. Filella, “Photochemical reflectance index (PRI) and remote sensing of plant CO2 uptake,” New Phytol., vol. 191, no. 3, pp. 596–599, 2011, doi: 10.1111/j.1469-8137.2011.03791.x.

[^17]:	R. Gupta, D. Vijayan, and T. Prasad, “Comparative analysis of red-edge hyperspectral indices,” Adv. Space Res. - ADV SPACE RES, vol. 32, pp. 2217–2222, Dec. 2003, doi: 10.1016/S0273-1177(03)90545-X.

[^18]:	J. E. VOGELMANN, B. N. ROCK, and D. M. MOSS, “Red edge spectral measurements from sugar maple leaves,” Int. J. Remote Sens., vol. 14, no. 8, pp. 1563–1575, May 1993, doi: 10.1080/01431169308953986.

[^19]:	J.-L. Roujean and F.-M. Breon, “Estimating PAR absorbed by vegetation from bidirectional reflectance measurements,” Remote Sens. Environ., vol. 51, no. 3, pp. 375–384, Mar. 1995, doi: 10.1016/0034-4257(94)00114-3.

[^20]:	J. Qi, A. Chehbouni, A. R. Huete, Y. H. Kerr, and S. Sorooshian, “A modified soil adjusted vegetation index,” Remote Sens. Environ., vol. 48, no. 2, pp. 119–126, May 1994, doi: 10.1016/0034-4257(94)90134-1.

[^21]:	C. Wu, Z. Niu, Q. Tang, and W. Huang, “Estimating chlorophyll content from hyperspectral vegetation indices: Modeling and validation,” Agric. For. Meteorol., vol. 148, no. 8, pp. 1230–1241, Jul. 2008, doi: 10.1016/j.agrformet.2008.03.005.

[^22]:	M. N. Merzlyak, A. A. Gitelson, O. B. Chivkunova, and V. YU. Rakitin, “Non-destructive optical detection of pigment changes during leaf senescence and fruit ripening,” Physiol. Plant., vol. 106, no. 1, pp. 135–141, 1999, doi: 10.1034/j.1399-3054.1999.106119.x.

[^23]:	P. Thenkabail, M. Gumma, P. Teluguntla, and M. I. Ahmed, “Hyperspectral Remote Sensing of Vegetation and Agricultural Crops.,” Photogramm. Eng. Remote Sens., vol. 80, Aug. 2014.

[^24]:	X. Jin, Z. Li, H. Feng, X. Xu, and G. Yang, “Newly Combined Spectral Indices to Improve Estimation of Total Leaf Chlorophyll Content in Cotton,” IEEE J. Sel. Top. Appl. Earth Obs. Remote Sens., vol. 7, no. 11, pp. 4589–4600, Nov. 2014, doi: 10.1109/JSTARS.2014.2360069.

[^25]:	E. Barnes et al., “Coincident detection of crop water stress, nitrogen status, and canopy density using ground based multispectral data,” Jan. 2000.


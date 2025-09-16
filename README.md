# CPSC444 Project: EXPLAINING AND PREDICTING SPATIAL VARIATION IN WETLAND N2O EMISSIONS THROUGH MICROBIAL FUNCTIONAL GENE ASSOCIATIONS 

**Data Source:** Bahram, M., Espenberg, M., Pärn, J. et al. Structure and function of the soil microbiome underlying N2O emissions from global wetlands. Nat Commun 13, 1430 (2022). https://doi.org/10.1038/s41467-022-29161-3
https://www.nature.com/articles/s41467-022-29161-3#Sec21

## Available Data

### All Collected & Measured Variables
| Variable                        | Levels / Unit|
|----------|---------------------------------|
| Location  | Coordinates(Latitude/Longitude)<br>Country/Region<br>Regional ISO code<br> |
| Land_use | Raised Bog<br>Fen<br>Forest<br>Hay field<br>Pasture<br>Peat extraction area |
| Climate    | A (rainy tropical)<br>C (temperate)<br>D (boreal) |
| Landscape  | lowland<br>high mountain<br>mountain valley<br>river valley<br>floodplain |
| Vegetation | Mosses<br>Sedges<br>Grasses<br>Herbs<br>Trees<br>Bare Soil |
| Agricultural intensity  | 0 = no agricultural land use (natural mire, swamp, or bog forest)<br>1 = moderate grazing or mowing (once a year or less)<br>2 = intensive grazing or mowing (more than once a year)<br>3 = arable land (directly fertilized or unfertilized)  |
| N2O flux | µg N O-N m h |
| N2 flux  | µg           |
| phyla relative & absolute abundance  | Bacteria; Acidobacteria<br>Bacteria; Proteobacteria; Alphaproteobacteria<br>Bacteria; Actinobacteria<br>Bacteria; Proteobacteria; Deltaproteobacteria<br>Bacteria; Chloroflexi<br>Bacteria; Proteobacteria; Betaproteobacteria<br>Bacteria; Proteobacteria; Gammaproteobacteria<br>Bacteria; Planctomycetes<br>Bacteria; Verrucomicrobia<br>Bacteria; Bacteroidetes<br>Archaea; Euryarchaeota<br>Bacteria; Nitrospirae<br>Bacteria; Firmicutes<br>Bacteria; Gemmatimonadetes<br>Bacteria; Parcubacteria<br>Bacteria; Spirochaetae<br>Bacteria; Ignavibacteriae<br>Eukaryota; Ascomycota<br>Bacteria; Microgenomates<br>Bacteria; Chlamydiae<br>Archaea; Bathyarchaeota<br>Archaea; Thaumarchaeota<br>Bacteria; Latescibacteria<br>Bacteria; Saccharibacteria<br>Eukaryota; Basidiomycota |
| functional (N-cycling) gene abundance | nirK<br>nirS<br>nosZI<br>nosZII<br>bacterial amoA<br>archaeal_amoA<br>nrfA<br>nifH<br>n-dammo<br>coammox  |
| species diversity  | archaeal<br>bacterial<br>fungal  |
| gene diversity & abundance  | archaeal amoA<br>bacterial amoA<br>coammox<br>nirK<br>nirS<br>nrfA<br>nosZI<br>nosZII<br>n-damo<br>nifH  |
| nitrogen metabolism pathways  | ammonia oxidation IV (autotrophic ammonia oxidizers)<br>ammonia oxidation I (aerobic)<br>ammonia assimilation cycle III<br>reduction I (denitrification)<br>nitrite oxidation<br>ammonia oxidation II (anaerobic)<br>L-tryptophan degradation VI (via tryptamine)<br>L-citrulline-nitric oxide cycle<br>N-glucosylnicotinate metabolism<br>hydroxycinnamic acid serotonin amides biosynthesis<br>hydroxycinnamic acid tyramine amides biosynthesis<br>nitrate reduction IV (dissimilatory)<br>spermidine hydroxycinnamic acid conjugates biosynthesis<br>hordatine biosynthesis<br>nitrate reduction VII (denitrification)<br>nitric oxide biosynthesis (plants)<br>ammonia assimilation cycle I<br>nitrifier denitrification	nitrate reduction III (dissimilatory)<br>nitrate reduction VIII (dissimilatory)<br>nitrate reduction IX (dissimilatory)<br>nitrate reduction X (periplasmic, dissimilatory)  |
| Environmental Factors  | MAP<br>MAT |
| Soil Chemistry |  soil temperature (at 10 & 20cm)<br>max temp of warmest month<br>pH<br>Von Post Grade of Decomposition (VPG)<br>organic matter (OrM)<br>water content<br>water table level|
| Soil Nutrients  |P<br>K<br>Ca<br>Mg<br>NO3<br>NH4<br>N<br>C<br>C:N
 
### Supplementary Data
**Supplementary Data 1** Samples used in this study.

**Supplementary Data 2** Correlations between N2O emissions and the relative abundance of all genera uncovered by metagenomes.

**Supplementary Data 3** List of archaeal OTUs showing strongest correlations to N2O fluxes.

**Supplementary Data 4** Correlation between N2O fluxes and Archaeal OGs across global wetland soils.

**Supplementary Data 5** Comparison between the functional gene profiles (MetaCyc and KEGG modules) of N2O taxa (determined using PacBio metabarcoding) that showed strongest positiveand negative correlations with N2O production.

**Supplementary Data 6** List of genomes that contain genes related to ammonia oxidation from a total of 91 archaeal and 116 bacterial genomes.

**Supplementary Data 7** Analysis of MetaCyc nitrogen metabolism pathways in available Archaeal genomes in JGI as off 15-jul-2020.

**Supplementary Data 8** Characteristics of qPCR primer pairs and programs used.


## Figures

<img width="595" height="460" alt="image" src="https://github.com/user-attachments/assets/875111fc-17fe-4e56-bf92-d15f37c59af0" />

Figure 1.  Distribution of the study sites and their measured N2O emissions as well as the archaeal-nitrifier/denitrifier ratio (archaeal amoA/(nirK + nirS)). Typographical symbols (+, ×, or ✱) denote average N2O fluxes per site, the filled/open round, square, and triangle shapes represent different land-use types, and shape color shows the archaeal-nitrifier/denitrifier ratio based on the absolute abundance of gene copies determined by qPCR (n = 72 independent sites). b–d Latitudinal gradient of N2O emissions, archaeal amoA and nir (nirK + nirS). Error bars represent the standard error (SE) of the means (n = 74 independent sites). The statistical test used was two-sided.

<img width="650" height="606" alt="image" src="https://github.com/user-attachments/assets/f785a468-0c06-4fa8-845f-18febe87622d" />

Figure 2. The relative abundance data are based on the relative abundance of SSU rRNA genes (normalized by total SSU rRNA abundances per sample) as revealed by shotgun metagenomics (n = 74 independent sites). Boxes represent 25th–75th percentile of the data distribution with whiskers at 1.5 × the interquartile range and the middle line representing median. The size of circles corresponds to the partial importance based on Random Forest models (variability% of mean decrease in accuracy estimated based on out-of-bag-CV); blue and red depict negative and positive Spearman correlations, respectively (n = 74 independent sites). Archaeal and fungal phyla names are indicated in blue and red colour, respectively. The abbreviations are organic matter (OrM), pH (soil pH), C/N (carbon to nitrogen ratio), Ca (calcium), K(potassium), P (phosphorous), Mg (magnesium), and Von Post grade of decomposition (VPG).

<img width="600" height="6070" alt="image" src="https://github.com/user-attachments/assets/bf773516-779e-4694-bd40-ae35d5de1b98" />

Figure 3. a Schematic view of nitrogen cycle in soils and the key genes involved. b Relationship between site mean relative abundance of archaeal amoA and N2O emission (n = 74 independent sites). The relative abundance of archaeal amoA was determined based on the relative abundance of metagenomics reads assigned to ENOG411114F (extracted from Hellinger transformed abundance matrix of archaeal OGs). The inset numbers represent a Spearman rank correlation coefficient (r) and corrected p-value for multiple testing using Benjamini–Hochberg method (q). Error bars represent the standard errors (SE) of the site means. c Partial least-squares regression (PLS regression) plot showing the relationships among the relative abundances of prokaryotic taxonomic groups (as determined by 16S metabarcoding) and N2O emission (n = 74 independent sites). Blue lines represent archaeal phyla. The statistical test used was two-sided.

<img width="600" height="542" alt="image" src="https://github.com/user-attachments/assets/a2b2608e-7c91-49c9-b992-61ea537fd3e1" />

Figure 4. a Correlations between environmental variables, the abundance of nir, nosZ and amoA genes (quantified by qPCR) and N2O emission (n = 74). The abbreviations are archaeal amoA (arch-amoA), bacterial amoA (bac-amoA), organic matter (OrM), pH (soil pH), C/N (soil carbon to nitrogen ratio), Von Post grade of decomposition (VPG). b Structural equation modeling (SEM) showing niche differentiation between bacterial and archaeal amoA (n = 74 independent sites). The model fitness was acceptable (Fisher’s C = 8.4, p = 0.08). Line thickness corresponds to standardized regression coefficients as indicated in the legend. Dash lines indicate negative relationships. The statistical test used was two-sided. The abbreviations are mean annual temperature (MAT), pH (soil pH). c Relationship between N2O emissions and the diversity of N cycle functional genes that are directly involved in N2O dynamics, including archaeal amoA, bacterial amoA, comammox amoA, nirK, nirS, nrfA, nosZI, and nosZII. The inset numbers represent an adjusted r2 and p-value from a GAM model. Error bars represent the standard error (SE) of the means (n = 74 independent sites). The statistical test used was two-sided.

















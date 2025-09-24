---
layout: page
title: "Stage 1 – Data Diagnosis and Preparation"
permalink: /pd28/results-stage1/
---

# Stage 1 – Data Diagnosis and Preparation  

Stage 1 focused on the careful preparation and diagnosis of all datasets used in the project, including observational records, reanalysis products, and climate model simulations. To characterize the dominant patterns of variability in both total cloud cover (TCC) and sea-ice concentration (SIC), we applied **Empirical Orthogonal Function (EOF)** analysis, a powerful statistical tool widely used in climate science.

---

## EOF Analysis: Reducing Complexity, Revealing Patterns  

The **EOF method** (Lorenz, 1951) transforms correlated variables into a new set of uncorrelated variables (principal components) that optimally explain variability in the data.  
- The first EOF explains the largest share of variance in the dataset.  
- Subsequent EOFs explain progressively smaller fractions, each orthogonal to the previous ones.  

EOF analysis allows us to extract the leading spatial and temporal variability patterns, increasing the signal-to-noise ratio and providing a compact representation of the data.

---

## Dominant Modes of TCC Variability  

The first two modes of TCC variability were derived from annual cloud anomalies in ISCCP, PATMOS-x, and ERA5 datasets (Figure R1).  

- **EOF1** shows a tropical Pacific pattern with a positive anomaly band extending from the Peruvian coast into the central Pacific and negative loadings in the central, northeast, and southeast Pacific. Positive anomalies also appear over North America, Central Asia, and the North Atlantic (more pronounced in ERA5). Differences across datasets are observed mainly over Australia, northwestern South America, and the South Atlantic.  
- **EOF2** (or EOF3 for ERA5) exhibits an equatorial dipole structure with positive anomalies in the central Pacific and negative anomalies in the east, plus positive anomalies over the tropical Atlantic and northeastern South America.  

Both modes are dominated by interannual variability. The first two modes explain about 35% (ISCCP) and 32% (PATMOS-x) of total variance, while remaining variability is spread across many small-scale modes likely dominated by noise.

![Figure R1](/pd28/images/FigureR1.png)  
*Figure R1. Global modes of TCC variability (Vaideanu et al. 2023a, [source link](https://www.mdpi.com/2073-4433/14/3/456)). Left: spatial structures of EOF1 and EOF2/EOF3 from ISCCP, PATMOS-x, and ERA5 datasets. Right: associated principal component time series.*

---

## Dominant Mode of SIC Variability  

The leading mode of Arctic SIC variability (EOF1) accounts for ~34% of the total variance (Figure R2).  
- The most pronounced negative anomalies occur over the East Greenland, Barents, and Kara Seas, with weaker signals over Baffin Bay.  
- The principal component shows a marked downward trend after the 1980s, consistent with accelerated Arctic sea-ice loss.

![Figure R2](/pd28/images/FigureR2.png)  
*Figure R2. Dominant mode of Arctic SIC variability identified from annual NSIDC anomalies (Vaideanu et al. 2023b, [source link](https://doi.org/10.1371/journal.pone.0290437.g001)). Panel (a): spatial pattern of EOF1 (34% variance explained). Panel (b): associated time series.*

---

EOF analysis from Stage 1 thus provided a robust baseline of the dominant modes of global cloud and sea-ice variability, which were used as a foundation for the analyses in Stage 2.

---

<div style="display: flex; flex-wrap: wrap; gap: 15px; margin-top: 20px; justify-content: center;">
  <a class="button" href="/pd28/results/" style="padding: 10px 18px; background-color: #6c757d; color: white; border-radius: 8px; text-decoration: none; font-weight: bold;">⬅ Back to Results</a>
  <a class="button" href="/pd28/results-stage2/" style="padding: 10px 18px; background-color: #0056b3; color: white; border-radius: 8px; text-decoration: none; font-weight: bold;">Next: Stage 2 ➡</a>
  <a class="button" href="/pd28/results-stage3/" style="padding: 10px 18px; background-color: #17a2b8; color: white; border-radius: 8px; text-decoration: none; font-weight: bold;">Skip to Stage 3</a>
</div>

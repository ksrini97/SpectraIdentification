# SpectraIdentification

## 1-d CNN with reconstruction fo functional group classification <br />
Module dependencies <br />
python==3.9.12
pip==23.0.l<br />
pandas==1.5.3<br />
numpy==1.24.3<br />
rdkit==2023.3.1<br />
keras==2.9.0<br />
tensorflow==2.9.1<br />
scikit-learn==1.2.2<br />
baselineremoval==0.1.3<br />
scipy==1.10.1<br />
jcamp==1.2.2<br />


## ScrapSpectra.ipynb <br />
Scrap NIST webbook to  obtain Spectra based on CAS ID <br />
## Check Absorbance.ipynb <br />
Convert transmittance to absorbance, change wavenumbers to cm-1 <br />
## Clean Spectra.ipynb <br />
Baseline correct spectra, downsample resolution to 4cm-1
## Generate labels.ipynb <br />
Generates classification labels for each functional group <br />
## Baseline Denoise.ipynb <br />
Applies a Savitzky-golay filter and rescales spectrum between 0 and 1 <br />
## NewArch.ipynb <br />
Training neural network with reconstruction layers

## DATA<br />
Biomass_4comp_Baseline.csv - Deconvoluted data for biomass <br />
Labels_Checked_baseline.csv - Labels for each spectrum <br />
Biomass_Acid_FTIR.xlsx - Raw FTIR data of HTL of biomass in acidic conditions <br />
Biomass_Acid_HNMR.xlsx - Raw HNMR data of HTL of biomass in acidic conditions <br />
Biomass_Naoh_FTIR.xlsx - Raw FTIR data of HTL of biomass in basic conditions <br />
Biomass_Naoh_HNMR.xlsx - Raw FHNMR data of HTL of biomass in basic conditions <br />
Biomass_SCW_FTIR.xlsx - Raw FTIR data of HTL of biomass in super critical water <br />
Biomass_SCW_FTIR.xlsx - Raw HNMR data of HTL of biomass in super critical water <br />
SynData - Contains data for synthetic experiments<br />

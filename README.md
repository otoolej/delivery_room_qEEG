Quantitative Features of EEG Recorded in the Delivery Room Immediately After Birth
==================================================================================

EEG features from term infants recorded minutes after birth. To accompany publication:

`D Finn, JM O'Toole, EM Dempsey, GB Boylan, EEG for the Assessment of Neurological
Function in Newborn Infants Immediately After Birth, 2018, under review.`


Features are generated using NEURAL (version 0.3.4; [code on
github](https://github.com/otoolej/qEEG_feature_set)); see reference [1] for more details.

# Files
- `qEEG_term_newborns_delivery_suite_ANON.csv`: feature set as comma-separated
  variable file. Will open in Excel (or equivalent).
- `LICENCE.md`: terms of use.

Brief description of each feature:

| column name                  | description                                           |
| ---------------------------- | ----------------------------------------------------- |
| spectral_power__1\_          | spectral power (delta band = 0.5 to 4 Hz)             |
| spectral_power__2\_          | spectral power (theta band = 4 to 7 Hz)               |
| spectral_power__3\_          | spectral power (alpha band = 7 to 13 Hz)              |
| spectral_power__4\_          | spectral power (beta band = 13 to 30 Hz)              |
| spectral_relative_power__1\_ | relative spectral power (for each band)               |
| spectral_relative_power__2\_ |                                                       |
| spectral_relative_power__3\_ |                                                       |
| spectral_relative_power__4\_ |                                                       |
| spectral_edge_frequency      | frequency (Hz) below which 95% spectral power resides |
| FD                           | fractal dimension (using Higuchi method)              |
| rEEG_median                  | median rEEG (rEEG similar to aEEG)                    |
| rEEG_lower_margin            | lower margin (5th percentile) of rEEG                 |
| rEEG_upper_margin            | upper margin (95th percentile) of rEEG                |
| rEEG_asymmetry               | symmetry between upper, lower, and median rEEG        |



# References
1. JM O’Toole and GB Boylan (2017). NEURAL: quantitative features for newborn EEG using
Matlab. ArXiv e-prints, arXiv:[1704.05694](https://arxiv.org/abs/1704.05694).


# Contact
John M. O' Toole

Neonatal Brain Research Group,  
INFANT: Irish Centre for Fetal and Neonatal Translational Research,  
Department of Paediatrics and Child Health,  
Room 2.19 Paediatrics Bld, Cork University Hospital,  
University College Cork,  
Ireland

Email: j.otoole AT ieee. org


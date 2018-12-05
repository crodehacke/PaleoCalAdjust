PaleoCalAdjust
===================

This is the repository that accompanies the paper:

Bartlein, P. J. and Shafer, S. L.: Paleo calendar-effect adjustments in time-slice and transient climate-model simulations (PaleoCalAdjust v1.0): impact and strategies for data analysis, *Geosci. Model Dev. Discuss.*, 2018, 1-36, [https://doi.org/10.5194/gmd-2018-283](https://doi.org/10.5194/gmd-2018-283), 2018.


The programs implement an approach for adjusting for the "paleo calendar effect" -- the impact that the changes in the length of months or seasons over time (related to the changes in the eccentricity of Earth's orbit and to precession), have on the summarization of paleoclimatic model output. The key program is `cal_adjust_PMIP3.f90` (in the folder `/f90`), which applies the adjustment to CMIP5/PMIP3-formatted files, and a related program, `month_length.f90`, that can be used to produce tables of the changing length of months over time. Figures illustrating the paleo calendar effect are in the folder `/figures`, and relevant data sets for exercising the programs are in the folder `/data`.  The program `cal_adjust_PMIP3.f90` will be modified to accommodate CMIP6/PMIP4-formatted files when they become available.




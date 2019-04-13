I created a jupyter notebook which uses the random forest regressor from sklearn to predict 
chlorophyll-a (chl-a) concentrations in Indian River Lagoon (IRL) from 87 band, 380-960nm hyperspectral 
HICO satellite imagery and 10 in-situ chl-a measurements made by St. Johns River Water Management 
District (SJRWMD). 

I originally used an optimization procedure based on Gitelson et al. (2011) to estimate chl-a during 
my Master's program for the class Hyperspectral Remote Sensing (GEO4930) on 5/2/2016, this is a revisit 
of that data with acquired machine learning skills, yielding better results.

Included:
Predict_ChlA.gdb				> Geodatabase
	\insitu_chla_measures_points_
	 average_cropped_bands			> Points of in-situ chl-a measurements
	\insitu_chla_measures_points_
	 average_cropped_bands_test		> Test split of in-situ chla-measurement points
	\insitu_chla_measures_points_
	 average_cropped_bands_train		> Train split of in-situ chla-measurement points
	\IRL_Mask				> Mask of IRL
	\IRL_Predicted_ChlA			> Results of random forest regression obtained by running through
						  PredictedChlaConcentration_Revisited_RandomForest.ipynb
Predicted_ChlA.aprx				> ArcPro project used to create map displaying the data and result of
						  the random forest regression.
PredictedChlaConcentration_Revisited_
RandomForest.png				> Map displaying the data and result of the random forest regression.
PredictedChlaConcentration_Revisited_
RandomForest.ipynb				> jupyter notebook processing and analyzing the data, and implimenting 
						  the random forest regression.
PredictedChlaConcentration_Revisited_
RandomForest_jnotebook.pdf			> pdf printout of the jupyter notebook after all code has been run.


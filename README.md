# Google Earth Engine - Urban extent extraction combining Sentinel data in the optical and microwave range

Abstract — This paper deals with the idea to jointly exploit data sets in the optical and microwave range to perform a more robust extraction of urban extents than by using either one of them. The procedure is designed to automatically and effectively exploit the features of SAR and multispectral data, so that it can be safely applied to different urban environments with satisfying results. To this aim, it starts from two previously developed algorithms for urban extent extraction designed for multispectral or SAR spaceborne data. They are first adapted to use Sentinel-1 (S1) and Sentinel-2 (S2) data sets. A novel procedure merging the two processing chains is finally designed in two variants, with the objective to exploit the spectral properties of artificial materials in multispectral S2 data as well as the double bounce backscatter effect that is common to built-up areas in SAR S1 data. Experimental results in urban areas all around the world show that the proposed procedure effectively combines the two above mentioned features of the input data sets, improving the urban extent extraction results by reducing the errors of the two original techniques.

# Prepare the code

In just four easy steps:
- Access to your workspace in Google Earth Engine;
- Copy and paste the code;
- Upload the auxiliary file available in this repository, and add it to the 'cities_table' variable;
- Add a geometry in your area of interest.

# How to use it

There are three sets of parameters which can be found in the first section of the code:
- Parameters to be set --> These refers to the region of interest and the input images;
- Fixed parameters S-2 --> These are set to classify the multi-spectral optical images. Default values are already defined. 
- Fixed parameters S-1 --> These are set to classify the SAR images. Default values are already defined.

The fixed parameters could be tuned to achieve a better classification. More details about their purpose can be found within the paper. 


HAVE FUN!

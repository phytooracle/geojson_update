# Update Information in GeoJSON file

This file takes a GeoJSON and updates the "genotype" and the "year" columns based on the information for a new gantry season. For this task, this notebook requires a GeoJSON from a previous season, as well the latest Gantry FieldBook.

# Required Dependencies/Libraries
  * Pandas
  * GeoPandas

# Steps to use this Notebook

## Download a previous season's GeoJSON file
Download a previous season's GeoJSON file from cyverse. Try to find a GeoJSON for a season that had the same crop as the crop being grown in the new gantry season. The path to the file looks something like this:
```bash
/iplant/home/shared/phytooracle/season_<X>_sorghum_yr_<YEAR>/level_0/season<X>_multi_latlon_geno_updated.geojson
```

## Store the GeoJSON and the FieldBook in a directory accessible by the notebook
Store them preferably in the same directory as the notebook, and change the paths in the designated areas of the code. 

## Manually Inspection 
Go through the code and manually review any fields that seem out of place, and introduce necessary modifications. **Please Note:** PI_Accession and Genotype are different names for the same field.  

## Run and Upload
Run the code, and after a successful complete execution upload the newly created GeoJSON with the updated fields to Cyverse. 


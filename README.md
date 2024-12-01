# Visualizing fire scars through false color
*This is a homework assignment for UCSB's MEDS program EDS 220 class.*

## About
This repository contains a notebook 'hwk4-task2-fire-perimeter-Ramirez.ipynb' analyzing geographic data about fire perimeters in CA and selecting for the Thomas fire that occurred in 2017 in Montecito, CA. 
<figure>
<p align="center">
<img 
  src="/images/thomas_fire_nbcnews_Blevins.jpg" 
  width="800"
  >
  <figcaption>
Firefighters attack the Thomas Fire's north flank with backfires as they fight a massive wildfire north of Los Angeles, near Ojai, California on Dec. 9, 2017. Gene Blevins / Reuters file from [nbcnews](https://www.nbcnews.com/news/us-news/california-s-massive-thomas-fire-sparked-power-lines-fire-investigators-n983011) 
  </figcaption>
</p>
</figure>
This repository contains a notebook 'hwk4-task2-false-color-Ramirez.ipynb' analyzing true color data and joining together the fire perimeter for the Thomas fire hwk4-task2-fire-perimeter-Ramirez.ipynb' to visualize on a map. 

## Highlights

Notebook (fire-perimeter and/or false-color)
- Data read in with requests, zipfile, and os
- Data exploration with geopandas
- Looked at crs type
- Selected for specific parameter and saved new shapefile
- Eplored rgb and false color imagery
- Fixed outliers with robust
- Mapped Thomas fire with false color imagery

## Data

Some of the data for this analysis is housed in this repository and can be accessed, the Landsat C2 L2 dataset offers cloud-optimized geospatial data for a variety of use cases. The simplified collection of bands was used locally, the dataset includes fire perimeter boundaries for wildfires in California.

## References

This project uses data from the [Landsat C2 L2 dataset](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) provided by the [Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/). 

Microsoft. (n.d.). Landsat Collection 2 Level-2 (C2 L2) data [Data set]. Microsoft Planetary Computer. Retrieved November 23, 2024, from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

This project uses fire perimeter data from the [California Fire Perimeters dataset](https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436), available on [data.gov](https://data.gov). 

U.S. Government. (n.d.). California fire perimeters (ALL) [Data set]. Data.gov. Retrieved November 23, 2024, from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436

## Repository organization

```
eds220-hwk4
├── README.md
├── hwk4-task2-fire-perimeter-Ramirez.ipynb
├── hwk4-task2-false-color-Ramirez.ipynb
├── .gitignore
├── LICENSE
├── images
|   ├── thomas_fire_nbcnews_Blevins.jpg
└───data
    │   Thomas_fire_perimeter.shp
```

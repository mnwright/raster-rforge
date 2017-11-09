
## raster R package 

NOTE: this project never had a home to go to, it's now clear the raster package will be maintained by the original author. 

See the Issues for a raw list of things to fix in raster. 


The source of the 'raster' package lives on R-forge

https://r-forge.r-project.org/projects/raster/

There is a Github clone on r-forge here: https://github.com/rforge


To install the latest clone of the SVN R-forge version, use

```R
devtools::install_github("rforge/raster/pkg/raster")
```

## Why is this here?

The rforge project is again active and has several new features and bug fixes, pending CRAN release. My plan is to sift through the issues here and summarize them for the author to assess. The most important one is the tiled-extraction, that alone makes many applications slow to the point of being unusable - but it's very specific to certain data sets. 

My wishlist

- a core of gridded functions distilled from raster/sp/stars/spatstat
- a core of GDAL API functionality
- a core of PROJ4 functionality (probably lwgeom-based)
- those  cores independet of and leveraged by raster/stars and others




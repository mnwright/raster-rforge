
## raster R package 

NOTE: this project is effectively in stasis, see the Issues for a raw list of things to fix in raster, but the raster package will be maintained by the original author. 

mdsumner 2017-10-26

The rforge project is again active and has several new features and bug fixes, pending CRAN release. My plan is to sift through the issues here and summarize them for the author to assess. The most important one is the tiled-extraction, that alone makes many applications slow to the point of being unusable - but it's very specific to certain data sets. 

The source of the 'raster' package lives on R-forge

https://r-forge.r-project.org/projects/raster/

There is a Github clone on r-forge here: https://github.com/rforge

## This is a clone of the clone

Please use this repo to 

* report issues with raster and discuss workarounds and solutions
* craft PRs that fix individual issues

The hope is to provide a single place where raster can be discussed, and to provide oversight of disparate individuals working on solutions. 

I don't know what's next, but for now I don't see a problem in creating branches here that could be merged back to r-forge. Obviously it would be easier if the package was moved from r-forge, and I've asked if I can do that but got no answer. I (@mdsumner) have commit access to the r-forge repo, but there's little point in doing that if there won't be updates sent to CRAN. At some point someone will have to fork (rename) the thing, or perhaps it will get orphaned from CRAN and then someone can take over. But for now, we're in limbo more than a year or so.  


# SIMplyBee version 0.4.0 #

* 2023-MM-DD TODO

## Major changes ##

* createColony() and createMultiColony() do not have the location argument
  anymore; use setLocation() instead; by default, location is now c(0, 0) PR#500

## New features ##

* In setLocation(MultiColony) we can set one location (numeric) or multiple
  (list or data.frame) PR#500
  
* getLocation(MultiColony) got the collapse argument
  Commit#f4e629c3e8920948ad576eae3615a86b26300790

* We can now sample location of a swarm - see sampleLocation and radius
  arugments in swarm() PR#500 PR#502
  
* New function rcircle() to sample a random point within a circle with a given
  radius PR#502
  
* Removed the function createRandomCrossPlan() - that option is now included in the newly added createCrossPlan() fuction

* Added the funcionality for spatially-aware mating of honeybee colonies. The new funcionality is included in the createCrossPlan(), that allows to create the cross plan according to the colonies' locations, and in the cross() function, that crosses bees according to their location
 

## Bug fixes ##
* Bug fix - get*Haplo() functions were returning diploid drones when input was a Pop-class


*


# SIMplyBee version 0.3.0 #

* 2022-12-05 First public/CRAN version of the package

## Major changes ##

* ~2 years of work went into this first public version!

## New features ##

* Many;) See the vignettes and help pages.

## Bug fixes ##

* Many bugs and issues squashed - see https://github.com/HighlanderLab/SIMplyBee/issues.
  Please contribute to the development of this package.




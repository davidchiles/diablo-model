# Mount Diablo Model


Inspired by [Christopher Jones](https://github.com/taketime)' model of [Mount Hood](https://github.com/taketime/hood-model)


## Steps 
* Insall gdal `brew install gdal`
* Download NED Data from [The National Viewer](http://viewer.nationalmap.gov/viewer/)
* Create geo tiff `gdaldem color-relief <NED_DATA.img> colormap.txt out.tiff`
* Convert geo tiff to png
* Convert png to 3D model

### Converting geo tiff to a 3D model
* [Blender](http://www.blender.org/) using this [tutuorial](http://johnflower.org/tutorial/make-mountains-blender-height-maps) 
* [PNG23D](http://kyllikki.github.io/png23d/) 
* Let me know of any others out there



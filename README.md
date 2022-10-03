# Fiji-Napari-Dictionary

This document contains translations of typical terms, menus and simple workflows in Fiji and their counterpartts in Napari together with links to documentation, plugins and example code. Feedback is welcome as [github issue](https://github.com/haesleinhuepf/FIJI-Napari-Dictionary/issues), [contributions and suggestions can be sent as pull-request](https://github.com/haesleinhuepf/FIJI-Napari-Dictionary/pulls).

The dictionary lists things alphabetically in this form as

* ImageJ / Fiji thing (menu)
  * Napari thing (menu, plugin)
  
Use the browsers search function (CTRL+F or CMD+F) to find things.

## Dictionary

* `Analyze > Analyze Particles` (menu)
  * `Plugins > morphometrics > Measure region properties` (menu, available as [plugin](https://www.napari-hub.org/plugins/morphometrics))
  * `Tools > Measurement > Label Statistics` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant))
  * `Tools > Measurement > Measurements` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))
  * `Tools > Measurement > Regionprops` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-skimage-regionprops))

* `Analyze > Plot Profile` (menu)
  * `Tools > Measurement > Plot profile` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-plot-profile))

* `Edit > Copy to system` (menu)
  * `File > Copy Screenshot to Clipboard` (menu)
  
* `Edit > Invert` (menu)
  * `Tools > Image math > Invert image` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes), [plugin 2](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))
  
* `File > New > Script` (menu)
  * `Tools > Scripts > Script Editor` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-script-editor))

* `Image > Adjust > Brightness / contrast` (menu)
  * `Right-click on contrast slider` (popup dialog)
  * `Tools > Visualization > Brightness / contrast` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-brightness-contrast))

* `Image > Adjust > Threshold` (menu)
  * `Tools > Segmentation / Binarization > Threshold ... ` (menu, menu / button, available as [plugin 1](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant), [plugin 2](https://www.napari-hub.org/plugins/napari-skimage-regionprops), [plugin 3](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))
  * `Tools > Utilities > Assistant`, `Binarize` (menu / button, available as [plugin 1](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant), [plugin 2](https://www.napari-hub.org/plugins/napari-skimage-regionprops), [plugin 3](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))

* `Image > Color > Split Channels`
  * `Right-click on layer list > Split RGB` (popup menu)   

* `Image > Crop` (menu)
  * `Plugins > napari-nd-cropper: nd_ Cropper` (menu, availablee as [plugin](https://www.napari-hub.org/plugins/napari-nd-cropper))
  * `Tools > Utilities > Crop Region` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-crop))
  
* `Image > Duplicate` (menu)
  * `(Right-click on Layer) > Duplicate Layer` (popup menu)
  * `Tools > Utilties > Duplicate current timepoint` (https://www.napari-hub.org/plugins/napari-skimage-regionprops)

* `Image > Stacks > Stack to Hyperstack` (menu)
  * `Tools > Utilities > Convert 3D stack to 2D timelapse` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-time-slicer))

* `Image > Stacks > Tools > Reduce` (menu)
  * `Tools > Utilities > Assistant`, `Projection` (menu / button, available as [plugin](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant))

* `Image > Stacks > Plot Z-Axis-Profile` (menu)
  *  `Plugins > napari-time-series-plotter: TSPExplorer` (menu, availablee as [plugin](https://www.napari-hub.org/plugins/napari-time-series-plotter))

* `Image > Stacks > Z-Project` (menu)
  * `Plugins > napari-math > ...` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-math))
  * `Right-click on image layer > Make Projection > ...` (popup menu) 
  * `Tools > Utilities > Assistant`, `Projection` (menu / button, available as [plugin](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant))

* `Image > Transform > ...` (menu)
  * `Plugins > napari-manual-transforms: Rotation Helper` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-manual-transforms))
  * `Tools > Utilities > Assistant`, `Transform` (menu / button, available as [plugin](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant))

* `Image > Properties` (menu)
  * `Tools > Utilities > Layer Details` (menu, availabla as [plugin](https://www.napari-hub.org/plugins/napari-layer-details-display))
  * `Tools > Utilities > Set voxel size` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant))

* `Fiji` (plugin collection)
  * `devbio-napari` (plugin collection, available as [plugin](https://www.napari-hub.org/plugins/devbio-napari))

* `Lookup table / LUT` (term)
  * `Colormap` (code [example 1](https://napari.org/stable/gallery/set_colormaps.html), [example 2](https://alisterburt.github.io/napari-workshops/notebooks/custom_colormaps.html))

* `Plugins › 3DSuite › Segmentation › 3D Watershed` (menu, [plugin](https://imagej.net/plugins/3d-imagej-suite/))
  * `Plugins > Segmentation / labeling > Local minima seeded Watershed` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes))

* `Plugins > Macros > Record` (menu)
  * `Plugins > Utilities > Assistant` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-assistant), [documentation](https://github.com/haesleinhuepf/napari-assistant#code-generation))

* `Plugins > Registration > StackReg` (menu, [plugin](http://bigwww.epfl.ch/thevenaz/stackreg/))
  * `Plugins > napari-pystackreg: pystackreg` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-pystackreg))

* `Plugins > Segmentation > Trainable (Weka) Segmentation` (menu, available as [plugin](https://imagej.net/plugins/tws/))
  * `Plugins > hesperos > OneShot segmentation` (menu, available as [plugin](https://www.napari-hub.org/plugins/hesperos)) 
  * `Plugins > napari-buds > bud annotation` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-buds))
  * `Tools > Segmentation / labeling > Object Segmentation` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-accelerated-pixel-and-object-classification))

* `Process > Binary > Erode / Dilate / Open / Close` (menu)
  * `Tools > Segmentation post-processing > Binary ...` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-cupy-image-processing))
  * `Tools > Utilities > Assistant`, `Binarize` (menu / button, available as [plugin 1](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant), [plugin 2](https://www.napari-hub.org/plugins/napari-skimage-regionprops), [plugin 3](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))

* `Process > Binary > Fill holes` (menu)
  * `Tools > Segmentation post-processing > Binary Fill Holes` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))

* `Process > Binary > Skeletonize` (menu)
  * `Tools > Segmentation post-processing > Skeletonize` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes))

* `Process > Binary > Watershed` (menu)
 * `Tools > Segmentation post-processing > Split touching objects` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes))
 * `Tools > Segmentation / labeling > Touching objects labeling` (menu, [plugin 2](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing))

* `Process > Filter > Gaussian Blur / 3D` (menu)
  * `Tools > Filtering / noise removal > Gaussian` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes), [plugin 2](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing), [plugin 3](https://www.napari-hub.org/plugins/napari-cupy-image-processing))

* `Process > Filter > Median / 3D` (menu)
  * `Tools > Filtering / noise removal > Median` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes),  [plugin 2](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing), [plugin 3](https://www.napari-hub.org/plugins/napari-cupy-image-processing))

* `Process > Find Maxima...` (menu)
  * `Plugins > napari-blob-detection > Detect blobs on images` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-blob-detection)) 

* `Process > Find Edges...` (menu)
  * `Tools > Filtering / edge enhancement > ...` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes), [plugin 2](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing), [plugin 3](https://www.napari-hub.org/plugins/napari-cupy-image-processing))

* `Process > Image Calculator` (menu)
  * `Plugins > napari-math > ...` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-math)) 
  * `Tools > Image math > ... ` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes)  
  * `Tools > Utilities > Assistant`, `Combine` (menu / button, available as [plugin](https://www.napari-hub.org/plugins/napari-pyclesperanto-assistant))

* `Process > Subtract background` (menu)
  * `Tools > Filtering / background removal > Rolling ball` (menu, available as [plugin](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes))
  * `Tools > Filtering / background removal > Black / white top hat` (menu, available as [plugin 1](https://www.napari-hub.org/plugins/napari-segment-blobs-and-things-with-membranes), [plugin 2](https://www.napari-hub.org/plugins/napari-simpleitk-image-processing), [plugin 3](https://www.napari-hub.org/plugins/napari-cupy-image-processing))


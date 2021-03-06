# anskuelse

Visualisation of large images with multiple sub-areas of interest.

Work is published at 
https://labs.statsbiblioteket.dk/anskuelse/adams_history/

## Adams Illustrated Panorama of History, 1878

Working with this requires a tile package, which is currently not part of this repository as there are too many files. It can be generated by downloading one of the single-image versions of the piece from [about Adams](https://labs.statsbiblioteket.dk/anskuelse/adams_history/about.html) and running the tool `vips` in the `anskuelse/adams_history`-folder with

```
vips dzsave 18068_Adams_Illustrated_Panorama_of_History_1878_* 18068
```

This should generate the folder `18068_files` and the file `18068.dzi`. Open `anskuelse/adams_history/index.html` in a browser to see the result.

## Ideas

* Automatic zooming and panning when the user is inactive
* Annotation-display using overlays. Currently a proof of concept can be seen at the globe in the lower left corner on the dmeo page
* Annotation-additions using an edit-mode or similar

- Royal Danish Library

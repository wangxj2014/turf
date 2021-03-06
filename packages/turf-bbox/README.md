# @turf/bbox

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

## bbox

Takes a set of features, calculates the bbox of all input features, and returns a bounding box.

**Parameters**

-   `geojson` **([FeatureCollection](http://geojson.org/geojson-spec.html#feature-collection-objects) \| [Feature](http://geojson.org/geojson-spec.html#feature-objects)&lt;any>)** input features

**Examples**

```javascript
var line = turf.lineString([[-74, 40], [-78, 42], [-82, 35]]);
var bbox = turf.bbox(line);
var bboxPolygon = turf.bboxPolygon(bbox);

//addToMap
var addToMap = [line, bboxPolygon]
```

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** bbox extent in [minX, minY, maxX, maxY] order

<!-- This file is automatically generated. Please don't edit it directly:
if you find an error, edit the source file (likely index.js), and re-run
./scripts/generate-readmes in the turf project. -->

---

This module is part of the [Turfjs project](http://turfjs.org/), an open source
module collection dedicated to geographic algorithms. It is maintained in the
[Turfjs/turf](https://github.com/Turfjs/turf) repository, where you can create
PRs and issues.

### Installation

Install this module individually:

```sh
$ npm install @turf/bbox
```

Or install the Turf module that includes it as a function:

```sh
$ npm install @turf/turf
```

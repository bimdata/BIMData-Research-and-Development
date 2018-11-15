# [BIMData](http://www.bimdata.io/en/bim-data-en/) R&D

| <img src="assets/icons/IFC.jpeg" height="50" border="10"/> | <img src="assets/icons/GLTF.png" height="50" border="10"/> | <img src="assets/icons/python.png" height="50" border="10"/> | <img src="assets/icons/scipy.png" height="50" border="10"/> |
| ---- | ---- | ---- | ---- |

---

* [BIMData IFC Engine](#bimdata-ifc-engine)
* [BIMData Checker](#bimdata-checker)
	* [BVH Tree for Spatial Querying](./pages/OBB_BVH_Tree.md)
* [BIMData Optimizer](#bimdata-optimizer)
	* [GLTF Optimization](./pages/GLTF_Optimization.md)
	* [IFC Optimization](./pages/IFC_Optimization.md)
* [Open Models](#open-models)
	* [IFC Files](./pages/IFC_FILES.md)

---

|**Overview**|**Timeline**|
|:-----|-----:|
| The **R&D efforts at BIMData** are oriented towards the handling of<br>BIM assets in an efficient manner.<br>The **Industry Foundation Classes (IFC)** standard from [buildingsmart](http://www.buildingsmart-tech.org/specifications/ifc-overview)<br>is at the core of our R&D. We use IFC files as a starting point for all<br>the tools that we develop at BIMData.<br>Because we are a web-based solution we need to use the smallest<br>assets possible. That is why we use the **glTF 2.0** format from [Khronos](https://www.khronos.org/gltf/)<br>for our 3D visualization.<br>We code in [Python](https://www.python.org/) with numerical calculations (mostly geometrical<br>methods) using the [Scipy](https://www.scipy.org/) stack. | ...<br>IFC Optimization - Duplicate geometries<br>GLTF Optimization - Duplicate data&geometries<br>IFC Optimisation - Duplicate instances<br>Export in the BIMData IFC Engine<br>BIMData IFC Engine development<br>**2018**<br>Start of quantities calculation and OBBs/BVH <br>Implementation of the BIMData Checker<br>GLTF and SVG conversion<br>Start of the BIMData IFC Engine development<br>**2017** |


### BIMData IFC Engine

We developed an IFC engine for BIMData  to manipulate IFC2X3 and IFC4 files.
From an IFC file, the engine **extracts and transforms data for the BIMData
API** to be used in tools like the
[BIMData Information Manager](https://www.bimdata.io/en/information-manager/)  or the [BIMData Viewer](https://www.bimdata.io/en/bim-viewer-en/) for instance. Right now the
engine can:

* Extract
	* Structure
	* Attributes, Properties
	* Zones, Systems, Classifications
	* Materials
* Calculate
	* Quantities
* Convert
	* IFC to GLTF (for the BIMData Viewer)
	* IFC to SVG (for the BIMData Zones Editor)
* Export
	* (optimized) IFC (selection) with updated data
	* (optimized) GLTF (selection)

### BIMData Checker

We also offer the possibility to test a model against a set of rules with the
[BIMData Checker](https://www.bimdata.io/en/bim-checker-2/). The checker can
perform **alphanumeric checks** on what is extracted and calculated by the
engine. We also developed **geometric checks**<br>(collision, proximity tests) and we
made a POC with Socotec for **accessibility checks**.

We implemented a Bounding Box Hierarchy (BVH) Tree to improve the geometric checks
with fast spatial querying.<br>See [BVH Tree for Spatial Querying](./pages/OBB_BVH_Tree.md) to learn more about it.

### BIMData Optimizer

Because we offer a web-based solution, our principal concern at BIMData was to
provide the best user experience on the most complex BIM models. We use
optimization to **reduce the sizes of IFC and GLTF files** to offer the best
interaction with the BIMData IFC Engine and the BIMData Viewer.

We optimize everything for you with the **BIMData Optimizer** (coming soon),
we work both on IFC and GLTF data to provide you with the smallest assets
possible. See our work on [GLTF Optimization](./pages/GLTF_Optimization.md)
and [IFC Optimization](./pages/IFC_Optimization.md) to know more about what's
happening under the hood.

### Open Models

All those tools are tested on **103 IFC files** (IFC2X3 and/or IFC4 versions) of various types
(Architectural, MEP, HVAC, etc..).<br>See [IFC Files](./pages/IFC_FILES.md) for a
curated list with sources.

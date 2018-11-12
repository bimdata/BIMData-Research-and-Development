# BIMData R&D

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

### BIMData IFC Engine

We developed the BIMData IFC Engine to manipulate IFC2X3 and IFC4 files. From
an IFC file, the engine extracts and transforms data for the BIMData API. Right
now the engine can:

* Extract
	* Structure
	* Attributes
	* Properties
	* Zones
	* Systems
	* Materials
	* Classifications
* Calculate
	* Quantities
* Convert
	* IFC to GLTF (for the BIMData Viewer)
	* IFC to SVG (for the BIMData Zones Editor)
* Export
	* (optimized) IFC (selection) with updated Structure/Properties/Zones/Systems/Materials/Classifications
	* (optimized) GLTF (selection)

### BIMData Checker

We also offer the possibility to test a model against a set of rules with the
BIMData Checker. The checker can perform alpha-numeric checks on what is
extracted and calculated by the engine. We also developed geometric checks
(collision, proximity tests) and we made a POC with Socotec for accessibility checks.

We implemented a Bounding Box Hierarchy (BVH) Tree to improve the geometric checks
with fast spatial querying. See [BVH Tree for Spatial Querying](./pages/OBB_BVH_Tree.md) to learn more about it.

### BIMData Optimizer

Because we offer a web-based solution, our principal concern at BIMData was to
provide the best user experience on the most complex BIM models. We use
optimization to reduce the sizes of IFC and GLTF files to offer the best
interaction with the BIMData IFC Engine and the BIMData Viewer.

We optimize everything for you with the BIMData Optimizer, we work both on IFC
and GLTF data to provide you with the smallest assets possible. See our work
on [GLTF Optimization](./pages/GLTF_Optimization.md) and
[IFC Optimization](./pages/IFC_Optimization.md) to know more about what's happening under
the hood.

### Open Models

All those tools are tested on 60[TOUPDATE] IFC2X3/IFC4 files of various types
(Architectural, MEP, HVAC, etc..).<br>See [IFC Files](./pages/IFC_FILES.md) for a
curated list with sources.

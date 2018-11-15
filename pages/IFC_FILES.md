# [BIMData R&D](../README.md) - IFC Files

To conduct and test our researches we collected a set of **38 BIM models**.
Those models come from different sources:

* http://duraark.eu/data-repository/
* http://openifcmodel.cs.auckland.ac.nz/Model/Download
* https://www.bimcollab.com/en/support/support/downloads/examples-templates
* https://github.com/openBIMstandards/DataSetSchependomlaan/releases
* http://cgcad.thss.tsinghua.edu.cn/liuyushen/IFCCompressor/index.html
* https://www.nibs.org/page/bsa_commonbimfiles
* http://www.markusplassen.no/?p=987

<!---
* (https://bimvision.eu/en/download/) ?
--->

They consist of **103 IFC files (4 GB) of different types (Architecture,
Plumbing, etc..).** Below you will find a sorted list of the IFC files with
corresponding **links to download the source files.** For now the images are
screenshots from the [glTF Viewer](https://gltf-viewer.donmccurdy.com/), in
the future they will be pictures from the [BIMDataViewer](https://www.bimdata.io/en/bim-viewer-en/).
 No image means we haven't
succeeded to convert to GLTF. If not specified, the files are in the IFC2X3
schema and often architectural. We use a naming convention to explicit the type of
BIM asset, you will find a [list of abbreviations](#list-of-abbreviations) at
the end of this page.


|Images|Files|Size<br>(MB)|    |
|----|:----|:----:|:----:|
|<img src="../assets/screenshots/MedicalClinic_Combined.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_MedicalClinic_Arch.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_MedicalClinic_MEP.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_MedicalClinic_MEPOpti.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_MedicalClinic_HVAC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_MedicalClinic_ELE.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_MedicalClinic_Struct.png" width="228" height="136" border="0"/> | **NBU_MedicalClinic** <br> MedicalClinic_Combined.ifc <br> NBU_MedicalClinic_Arch.ifc <br> NBU_MedicalClinic_MEP.ifc <br> NBU_MedicalClinic_MEPOpti.ifc <br> NBU_MedicalClinic_HVAC.ifc <br> NBU_MedicalClinic_ELE.ifc <br> NBU_MedicalClinic_Struct.ifc  | **522.6** <br> 112.6 <br> 18.1 <br> 207.3 <br> 125.8 <br> 27.4 <br> 12.0 <br> 19.4 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NBU_MedicalClinic_ifc.zip) |
|<img src="../assets/screenshots/NVW_DCR_LOD300_ARC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NVW_DCR_LOD300_STR.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NVW_DCR_LOD300_HVAC.png" width="228" height="136" border="0"/> | **NVW_DCR_LOD300** <br> NVW_DCR_LOD300_ARC.ifc <br> NVW_DCR_LOD300_STR.ifc <br> NVW_DCR_LOD300_HVAC.ifc | **323.3** <br> 288.1 <br> 11.1 <br> 24.1 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NVW_DCR-LOD_ifc.zip) |
|<img src="../assets/screenshots/SGD_BODO_Arch.png" width="228" height="136" border="0"/><img src="../assets/screenshots/SGD_BODO_PLB.png" width="228" height="136" border="0"/><img src="../assets/screenshots/SGD_BODO_VENT.png" width="228" height="136" border="0"/> | **SGD_BODO** <br> SGD_BODO_Arch.ifc <br> SGD_BODO_PLB.ifc <br> SGD_BODO_VENT.ifc | **182.4** <br> 64.1 <br> 72.8 <br> 47.2 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/SGD_BODO_ifc.zip) |
|<img src="../assets/screenshots/Holter_Tower.png" width="515" height="272" border="0"/> | **Holter_Tower** <br> Holter_Tower_10.ifc | **177.5** <br> 177.5 | [source](https://www.dropbox.com/s/ybocflzyt33ilg5/Holter_Tower_10.ifc?dl=0) |
|<img src="../assets/screenshots/FOJAB_Landsarkivet.png" width="515" height="272" border="0"/> | **FOJAB_Landsarkivet** <br> FOJAB_Landsarkivet.ifc | **177.5** <br> 177.5| [source](https://tib.eu/data/duraark/BuildingData/03_IFC_E57/FOJAB_Landsarkivet_IFC.zip) |
| <img src="../assets/screenshots/BIMCollab_ARC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_STR.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_MEP.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_Elevatorshaft.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_HollowCoreSlabs.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_LimestoneWalls.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_StructuralSteel.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_VENT.png" width="228" height="136" border="0"/><img src="../assets/screenshots/BIMCollab_HEAT_PLB.png" width="228" height="136" border="0"/> | **BIMCollab** <br> BIMCollab_ARC.ifc <br> BIMCollab_STR.ifc <br> BIMCollab_MEP.ifc <br> BIMCollab_Elevatorshaft.ifc <br> BIMCollab_HollowCoreSlabs.ifc <br> BIMCollab_LimestoneWalls.ifc <br> BIMCollab_Structural Steel.ifc <br> BIMCollab_VENT.ifc <br> BIMCollab_HEAT_PLB.ifc | **175.6** <br> 26.0 <br> 0.6 <br> 45.0 <br> 1.4 <br> 14.7 <br> 0.2 <br> 0.3 <br> 32.8 <br> 54.6 | [source](https://www.bimcollab.com/Files/Example-Projects/BIMcollab_ifc_models.aspx) |
|<img src="../assets/screenshots/Autodesk_210King.png" width="515" height="272" border="0"/> | **Autodesk_210King** <br> Autodesk_210King.ifc | **155.1** <br> 155.1 | [source](https://tib.eu/data/duraark/BuildingData/03_IFC_E57/Autodesk_210-King_ifc.zip) |
|<img src="../assets/screenshots/Trapelo_IFC2X3_ARC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/Trapelo_IFC2X3_MEP.png" width="228" height="136" border="0"/><img src="../assets/screenshots/Trapelo_IFC2X3_STR.png" width="228" height="136" border="0"/> | **Trapelo** <br> Trapelo_IFC2X3_ARC.ifc <br> Trapelo_IFC2X3_MEP.ifc <br> Trapelo_IFC2X3_STR.ifc  <br> Trapelo_IFC4_ARC.ifc <br> Trapelo_IFC4_MEP.ifc <br> Trapelo_IFC4_STR.ifc | <br> 27.2 <br> 65.3 <br> 3.6 <br> 22.4 <br> 67.8 <br> 3.5 | <br>  [source](http://openifcmodel.cs.auckland.ac.nz/Model/Details/302) <br>  <br>  <br> [source](http://openifcmodel.cs.auckland.ac.nz/Model/Details/303) |
|<img src="../assets/screenshots/NBU_OfficeBuilding_Arch.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_OfficeBuilding_MEP.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_OfficeBuilding_HVAC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_OfficeBuilding_ELE.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_OfficeBuilding_Struct.png" width="228" height="136" border="0"/> | **NBU_OfficeBuilding** <br> NBU_OfficeBuilding_Arch.ifc <br> NBU_OfficeBuilding_MEP.ifc <br> NBU_OfficeBuilding_HVAC.ifc <br> NBU_OfficeBuilding_ELE.ifc <br> NBU_OfficeBuilding_Struct.ifc  | **91.6** <br> 4.1 <br> 4.1 <br> 65.8 <br> 6.5 <br> 11.1 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NBU_MedicalClinic_ifc.zip) |
|<img src="../assets/screenshots/SGD_HiTOS_Arch.png" width="228" height="136" border="0"/><img src="../assets/screenshots/SGD_HiTOS_ELE.png" width="228" height="136" border="0"/><img src="../assets/screenshots/SGD_HiTOS_HVAC.png" width="228" height="136" border="0"/> | **SGD_HiTOS** <br> SGD_HiTOS_Arch.ifc <br> SGD_HiTOS_ELE.ifc <br> SGD_HiTOS_HVAC.ifc | **78.9** <br> 52.9 <br> 7.5 <br> 18.5 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/SGD_HiTOS_ifc.zip) |
|<img src="../assets/screenshots/Hospital_IFC2X3_ELE.png" width="228" height="136" border="0"/><img src="../assets/screenshots/Hospital_IFC2X3_FIRE.png" width="228" height="136" border="0"/><img src="../assets/screenshots/Hospital_IFC2X3_PLB.png" width="228" height="136" border="0"/><img src="../assets/screenshots/Hospital_IFC2X3_SPR.png" width="228" height="136" border="0"/><img src="../assets/screenshots/Hospital_IFC2X3_STR.png" width="228" height="136" border="0"/> | **Hospital** <br> Hospital_IFC2X3_ELE.ifc <br> Hospital_IFC2X3_FIRE.ifc <br> Hospital_IFC2X3_PLB.ifc <br> Hospital_IFC2X3_SPR.ifc <br> Hospital_IFC2X3_STR.ifc <br> Hospital_IFC4_ELE.ifc <br> Hospital_IFC4_FIRE.ifc <br> Hospital_IFC4_PLB.ifc <br> Hospital_IFC4_SPR.ifc <br> Hospital_IFC4_STR.ifc  | <br> 4.7 <br> 0.9 <br> 25.0 <br> 35.7 <br> 6.4 <br> 4.4 <br> 0.9 <br> 23.8 <br> 34.0 <br> 6.5 | [source](http://openifcmodel.cs.auckland.ac.nz/Model/Details/305)<br><br><br><br>[source](http://openifcmodel.cs.auckland.ac.nz/Model/Details/308) |
|<img src="../assets/screenshots/OTC_ConfCenter_IFC4.png" width="515" height="272" border="0"/> | **OTC_ConfCenter** <br> OTC_ConfCenter_IFC4.ifc <br> OTC_ConfCenter_IFC2X3.ifc |  <br> 71.7 <br> 70.3 | <br> [source](http://openifcmodel.cs.auckland.ac.nz/_models/20160125OTC-Conference%20Center%20-%20IFC4.ifc) <br> [source](http://openifcmodel.cs.auckland.ac.nz/_models/20160124OTC-Conference%20Center.ifc) |
|<img src="../assets/screenshots/NVW_DCR_LOD200_ARC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NVW_DCR_LOD200_STR.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NVW_DCR_LOD200_HVAC.png" width="228" height="136" border="0"/> | **NVW_DCR_LOD200** <br> NVW_DCR_LOD200_ARC.ifc <br> NVW_DCR_LOD200_STR.ifc <br> NVW_DCR_LOD200_HVAC.ifc | **67.9** <br> 25.3 <br> 9.4 <br> 33.2 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NVW_DCR-LOD_ifc.zip) |
|<img src="../assets/screenshots/IfcCompressor_M1.png" width="515" height="272" border="0"/> | **IfcCompressor** <br> IfcCompressor_M1.ifc | **58.5** <br> 58.5 | [source](http://cgcad.thss.tsinghua.edu.cn/liuyushen/IFCCompressor/index.html) |
|<img src="../assets/screenshots/SGD_BARD_Arch.png" width="228" height="136" border="0"/><img src="../assets/screenshots/SGD_BARD_Merged.png" width="228" height="136" border="0"/> | **SGD_BARD** <br> SGD_BARD_Arch.ifc <br> SGD_BARD_Merged.ifc | **55.3** <br> 11.5 <br> 43.8 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/SGD_BARD_ifc.zip) |
|<img src="../assets/screenshots/NBU_Duplex_Arch.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_Duplex_MEP.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_Duplex_HVAC.png" width="228" height="136" border="0"/><img src="../assets/screenshots/NBU_Duplex_MEP1.png" width="228" height="136" border="0"/> | **NBU_Duplex** <br> NBU_Duplex_Arch.ifc <br> NBU_Duplex_MEP.ifc <br> NBU_Duplex_HVAC.ifc <br> NBU_Duplex_MEP1.ifc | **54.4** <br> 2.4 <br> 32.1 <br> 18.2 <br> 1.6 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NBU_Duplex_ifc.zip) |
|<img src="../assets/screenshots/Schependomlaan.png" width="515" height="272" border="0"/> | **Schependomlaan** <br> Schependomlaan.ifc | **49.3** <br> 49.3 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/KIT_Institute_ifc.zip) |
|<img src="../assets/screenshots/NBS_Lakeside.png" width="515" height="272" border="0"/> | **NBS_Lakeside** <br> NBS_LakesideAC01.ifc | **42.3** <br> 42.3 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NBS_Lakeside_ifc.zip) |
|<img src="../assets/screenshots/Autodesk_Advanced.png" width="515" height="272" border="0"/> | **Autodesk_Advanced** <br> Autodesk_Advanced.ifc | **38.1** <br> 38.1 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/Academic_Autodesk_ifc.zip) |
|<img src="../assets/screenshots/Ettenheim.png" width="515" height="272" border="0"/> | **Ettenheim** <br> Ettenheim.ifc | **31.1** <br> 31.1 | [source](http://openifcmodel.cs.auckland.ac.nz/_models/261110Ettenheim-GIS-05-11-2006_optimized.ifc) |
|<img src="../assets/screenshots/Staal_Saxion_STR.png" width="515" height="272" border="0"/> | **Staal_Saxion_STR** <br> Staal_Saxion_STR.ifc | **25.3** <br> 25.3 | [source](http://openifcmodel.cs.auckland.ac.nz/_models/20161025ifc%20saxion%2028-09-2016.ifc) |
|<img src="../assets/screenshots/Dubal_Herrera_limpio.png" width="515" height="272" border="0"/> | **Dubal_Herrera_limpio** <br> Dubal_Herrera_limpio.ifc | **24.4** <br> 24.4 | [source](http://openifcmodel.cs.auckland.ac.nz/_models/20180731Dubal%20Herrera%20limpio.ifc) |
|<img src="../assets/screenshots/Plan3D_Haus30.png" width="515" height="272" border="0"/> | **Plan3D_Haus30** <br> Plan3D_Haus30.ifc | **20.2** <br> 20.2 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/KIT_Smiley-West_ifc.zip) |
|<img src="../assets/screenshots/FZK_HausNem.png" width="515" height="272" border="0"/> | **FZK_HausNem** <br> FZK_HausNem.ifc | **10.4** <br> 10.4 | [source]() |
|<img src="../assets/screenshots/FZK_HausEliteCAD.png" width="515" height="272" border="0"/> | **FZK_HausEliteCAD** <br> FZK_HausEliteCAD.ifc | **7.4** <br> 7.4 | [source]() |
|<img src="../assets/screenshots/Autodesk_Basic.png" width="515" height="272" border="0"/> | **Autodesk_Basic** <br> Autodesk_Basic.ifc | **5.4** <br> 5.4 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/Academic_Autodesk_ifc.zip) |
|<img src="../assets/screenshots/HospitalGarage_IFC4.png" width="515" height="272" border="0"/> | **HospitalGarage** <br> HospitalGarage_IFC4.ifc <br> HospitalGarage_IFC2X3.ifc |  <br> 6.5 <br> 6.4 | <br> [source](http://openifcmodel.cs.auckland.ac.nz/_models/20160125Autodesk_Hospital_Parking%20Garage_2015%20-%20IFC4.ifc) <br> [source](http://openifcmodel.cs.auckland.ac.nz/_models/20160125Autodesk_Hospital_Parking%20Garage_2015.ifc) |
|<img src="../assets/screenshots/FZK_Haus.png" width="515" height="272" border="0"/> | **FZK_Haus** <br> FZK_Haus.ifc | **4.1** <br> 4.1 | [source](http://openifcmodel.cs.auckland.ac.nz/_models/231110AC11-FZK-Haus-IFC.ifc) |
|<img src="../assets/screenshots/KIT_SmileyWest.png" width="515" height="272" border="0"/> | **KIT_SmileyWest** <br> KIT_SmileyWest.ifc | **3.4** <br> 3.4 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/KIT_Smiley-West_ifc.zip) |
|<img src="../assets/screenshots/KIT_Institute.png" width="515" height="272" border="0"/> | **KIT_Institute** <br> KIT_Institute.ifc | **2.8** <br> 2.8 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/KIT_Institute_ifc.zip) |
|<img src="../assets/screenshots/NVW_DCR_LOD100_ARC.png" width="515" height="272" border="0"/> | **NVW_DCR_LOD100** <br> NVW_DCR_LOD100_ARC.ifc | **0.2** <br> 0.2 | [source](https://tib.eu/data/duraark/BuildingData/01_IFC/NVW_DCR-LOD_ifc.zip) |




### List of abbreviations

**ARC** : Architecture <br>
**STR** : Structure <br>
**HEAT** : Heating <br>
**VENT** : Venting <br>
**HVAC** : Heating, Ventilating, and Air Conditioning <br>
**ELE** : Electrical <br>
**PLB** : Plumbing <br>
**MEP** : Mechanical Electrical Plumbing <br>
**FIRE**: Fire <br>
**SPR** : Sprinkle <br>

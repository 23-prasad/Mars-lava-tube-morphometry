**Project Title**

Geospatial and Morphometric Characterization of Lava Tubes in Arsia Mons Region, Mars

**Description**:

This project presents a morphometric and geospatial analysis of Martian lava tubes, with a focus on structural characteristics and collapse behaviour. Lava tubes are key targets for future planetary exploration due to their potential as natural shelters for human missions and preservation of geological records.

The study integrates remote sensing data, GIS-based feature extraction, and statistical analysis to evaluate relationships between lava tube geometry and collapse patterns.

**Objective**

Quantify lava tube geometry using GIS-derived attributes
Analyse collapse ratios along lava tubes
Study pit morphometry-Characterize pit morphometry using bounding box parameters
Investigate relationships between:
Tube length and collapse behaviour
Pit dimensions and morphological classification
Derive insights relevant to subsurface stability and exploration suitability

**Study Area & Data**
Region: Arsia Mons, Tharsis volcanic province, Mars
Data Source: Mars Global Cave Candidate Catalog
Data Type:
Lava tube polylines
Pit locations and geometries
Derived bounding box attributes

**Methods**
Highlights-
  QGIS spatial analysis
  Bounding box extraction
  Excel statistical plots
  
**1. Data Preparation**
Import and preprocess shapefiles in GIS
Validate geometry and attribute consistency
**2. Morphometric Analysis**
Extraction of:
  Total tube length
  Collapsed vs non-collapsed segments
  Collapse ratio
Generation of pit bounding boxes:
  Width
  Length
  Aspect ratio
**3. Spatial Analysis**
  Mapping lava tube networks
  Identifying clustering of collapse features
**4. Statistical Analysis**
Scatter plots:
 - Tube Length vs Collapse Ratio
Box-and-whisker plots:
  - Pit Width vs Pit Type
Distribution analysis of pit dimensions

**Key Results & Insights**
  1. Collapse Behaviour:
    (Collapse ratio trends) Preliminary analysis suggests a trend of increasing collapse ratio with tube length, indicating potential structural limits in longer lava tubes.
2. Pit Morphometry:
  (Pit size distribution)Distinct variations in pit width distributions across pit types suggest different formation or collapse mechanisms.
3. Structural Implications:
  (Box plot interpretation)Morphometric parameters provide proxies for assessing subsurface stability, relevant for landing site selection and habitat planning.

**Tools Used**
  1. GIS - QGIS
  2. Data Analysis: Microsoft Excel
  3. Version Control: GitHub

**Future Work**
  Integration with high-resolution DEMs (e.g., HiRISE)
  Automated pit detection using image processing / ML
  3D modelling of lava tube subsurface geometry
  Comparative analysis with terrestrial analogues

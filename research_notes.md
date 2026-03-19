## GeoPandas Analysis

GeoPandas is a Python library for working with geospatial data.

### Key Features:
- Extends pandas DataFrames with geometry columns
- Supports spatial operations and projections
- Integrates with Shapely, Fiona, and PROJ

### Common Issues Found:
- ENH: label plot axes based on CRS information
- BUG: overlay with empty input handles keep geom dtype gracefully
- BUG: inserting rows into empty geodataframe should preserve CRS

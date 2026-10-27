# Description provenance

Provenance of the schema descriptions in `standard/openapi/ogcapi-coverages-1.yaml`: every description was authored from the standard's own requirements classes and prose — none imported.

| Schema | Source | Description (first sentence) |
|---|---|---|
| `2DBoundingBox` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A two-dimensional bounding box: lower-left and upper-right corners with the coordinate reference system. |
| `2DPoint` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A two-dimensional point with x and y coordinates. |
| `all-collections` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A list of all collections available on this API, across all collection types. |
| `collectionDesc` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A description of a collection that hosts the results or data of the API. |
| `collections` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A list of the collections available on this API, with their titles, descriptions and links. |
| `confClasses` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The conformance classes the deployment implements, per the OGC API conformance declaration. |
| `coverage-collections` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A list of the coverage collections available on this API. |
| `coverageSchema` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The schema constraining a coverage: its domain set, range set and metadata per the CIS standard. |
| `crs` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The coordinate reference systems supported for spatial inputs and outputs. |
| `dataType` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A data type declaration for an input or output value. |
| `enumeration` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | An input whose value must be one of an enumerated set of literals. |
| `exception` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | An exception report describing why a request failed, per the OGC API exception convention. |
| `extent` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The spatial and temporal extent of a collection or deployment. |
| `extent-uad` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | An extent with unknown, unlimited or multi-dimensional axes, per the OGC Unbounded Axis Description extension. |
| `landingPage` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The landing page of the API: links to the conformance declaration, collections and other resources. |
| `link` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A hyperlink with its relation type, per the OGC API link conventions. |
| `numberMatched` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The number of items matching the selection criteria, if the server can determine it. |
| `numberReturned` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The number of items returned in this response. |
| `schema` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The schema constraining the values of an input or output of the coverage API. |
| `tileMatrixLimits` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The limits of a tile matrix: the tile row and column ranges available for a collection. |
| `tileMatrixSets` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A list of the tile matrix sets supported by this API, per the OGC Two-Dimensional Tile Matrix Set standard. |
| `tileSet` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | A tileset: a set of tiles of a collection in a specific tile matrix set and media type. |
| `tileSet-item` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | One tileset of a collection, with its tile matrix set reference, media type and template link. |
| `timeStamp` | OGC 19-087 (Coverages) requirements classes; tileset family per OGC 21-030; shared building blocks per OGC 19-072 | The timestamp of the response, per RFC 3339. |

These descriptions are offered upstream as part of the model-based publication program (metanorma-ogc#153); corrections by the editors are welcome and will be tracked here.

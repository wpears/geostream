A transform stream that accepts GeoJSON and emits atomic members as stringified objects.

This is only interesting for types of FeatureCollection and GeometryCollection.
For other types, it will just pass through the entire object.

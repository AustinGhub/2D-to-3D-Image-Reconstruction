# 2D-to-3D-Image-Reconstruction

This project focuses on the reconstruction of a 3D model from a 2D image using computer vision techniques. By analyzing data points extracted from an image of a teapot, the project aims to generate corresponding 2D arrays and transform them into polygon meshes. The triangulation and pruning techniques are utilized to construct accurate meshes, which are then used to manually recreate a 3D model of the teapot using software like Meshlab.

# Algorithm Overview
The 2D to 3D Image Reconstruction project involves the following key steps:

Data Point Extraction: Image analysis techniques are employed to extract data points from the teapot image. These data points represent the features and structure of the teapot.

2D Array Generation: The extracted data points are transformed into 2D arrays, where each element represents a specific attribute or property of the teapot at a particular position.

Polygon Mesh Construction: Triangulation techniques are used to connect the data points in the 2D arrays and form polygon meshes. Pruning techniques are applied to remove unnecessary or irrelevant polygons, ensuring the accuracy and efficiency of the mesh construction.

Manual 3D Model Recreation: The generated meshes are exported and loaded into software like Meshlab. In Meshlab, the 3D model of the teapot can be manually reconstructed by manipulating the meshes and adjusting their properties.

# InscribedTriangles

See the demonstration [here](https://demonstrations.wolfram.com/InscribedTrianglesInPolygons/).

![alt text](/img/demo3.png)


This Demonstration shows all possible triangles that can be inscribed in a polygon of `n` sides  and counts the number of noncongruent kinds of triangles.

The function `IntegerPartitions[]` is able to accurately calculate the number of possible noncongruent triangles that can be inscribed in a polygon with `n` sides. Example:

    IntegerPartitions[n, {3}]

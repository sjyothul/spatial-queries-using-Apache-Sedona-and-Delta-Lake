# spatial-queries-using-Apache-Sedona-and-Delta-Lake
Input Data: The point dataset (testpoint.csv) consists of coordinates (x,y) of various points while the polygon dataset (testenvelope.csv) consists of coordinates of two diagonal points(x1, y1, x2, y2) of rectangles.

1. Read the given testpoint.csv file in csv format. Write the points whose two attributes are all larger than 500 in delta format and save it named firstpointdata i.e., firstPointQuery()
2. Read the firstpointdata in delta format. Print the total count of the points i.e., secondPointQuery()
3. Read the given testenvelope.csv in csv format. Write the polygons whose four attributes are all larger than 900 in delta format and save it named firstpolydata i.e., firstPloygonQuery()
4. Read the firstpolydata in delta format. Print the total count of the polygon i.e., secondPolygonQuery()
5. Read the firstpointdata and firstpolydata in delta format. Find the total count for point pairs where the distance between the points within a pair is less than 2, and both points are within some rectangles from firstpolydata. Note the two points do not need to be in the same rectangle i.e., JoinQuery()

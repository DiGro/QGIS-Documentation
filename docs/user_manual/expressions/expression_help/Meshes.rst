:orphan:

.. DO NOT EDIT THIS FILE DIRECTLY. It is generated automatically by
   populate_expressions_list.py in the scripts folder.
   Changes should be made in the function help files
   in the resources/function_help/json/ folder in the
   qgis/QGIS repository.

.. _expression_function_Meshes_$face_area:

$face_area
..........

Returns the area of the current mesh face. The area calculated by this function respects both the current project's ellipsoid setting and area unit settings. For example, if an ellipsoid has been set for the project then the calculated area will be ellipsoidal, and if no ellipsoid is set then the calculated area will be planimetric.

.. list-table::
   :widths: 15 85

   * - Syntax
     - $face_area
   * - Examples
     - * ``$face_area`` → 42


.. end_$face_area_section

.. _expression_function_Meshes_$face_index:

$face_index
...........

Returns the index of the current mesh face. 

.. list-table::
   :widths: 15 85

   * - Syntax
     - $face_index
   * - Examples
     - * ``$face_index`` → 4581


.. end_$face_index_section

.. _expression_function_Meshes_$vertex_as_point:

$vertex_as_point
................

Returns the current vertex as a point geometry.

.. list-table::
   :widths: 15 85

   * - Syntax
     - $vertex_as_point
   * - Examples
     - * ``geom_to_wkt( $vertex_as_point )`` → 'POINT(800 1500 41)'


.. end_$vertex_as_point_section

.. _expression_function_Meshes_$vertex_index:

$vertex_index
.............

Returns the index of the current mesh vertex.

.. list-table::
   :widths: 15 85

   * - Syntax
     - $vertex_index
   * - Examples
     - * ``$vertex_index`` → 9874


.. end_$vertex_index_section

.. _expression_function_Meshes_$vertex_x:

$vertex_x
.........

Returns the X coordinate of the current mesh vertex.

.. list-table::
   :widths: 15 85

   * - Syntax
     - $vertex_x
   * - Examples
     - * ``$vertex_x`` → 42.12


.. end_$vertex_x_section

.. _expression_function_Meshes_$vertex_y:

$vertex_y
.........

Returns the Y coordinate of the current mesh vertex.

.. list-table::
   :widths: 15 85

   * - Syntax
     - $vertex_y
   * - Examples
     - * ``$vertex_y`` → 12.24


.. end_$vertex_y_section

.. _expression_function_Meshes_$vertex_z:

$vertex_z
.........

Returns the Z value of the current mesh vertex.

.. list-table::
   :widths: 15 85

   * - Syntax
     - $vertex_z
   * - Examples
     - * ``$vertex_z`` → 42


.. end_$vertex_z_section


# Free body diagrams

## Theory

```{index} Free body diagram
```
A free body diagram includes a complete or part of a model, with all [loads](loads) acting on that part, including [support reactions](supports). It can also include dimensions and [coordinate system(s)](coordinate).

```{index} Free body diagram ; of an entire model
```
### Free body diagram of entire model
A free body diagram of an entire model doesn't show [internal forces](internal forces).

An example model is shown in {numref}`model`.

```{figure} ./FBD_data/model.png
:name: model
:width: 400px
:align: center

Example model
```

The free body diagram of the entire example model is shown in {numref}`FBD`.

```{figure} ./FBD_data/FBD_full_structure.png
:name: FBD
:width: 400px
:align: center

Free body diagram of the entire example model
```

```{index} Free body diagram ; of a hinged part of a model
```
### Free body diagram of a hinged part of a model
In the free body diagram of a hinged part of a model, a cut is made at the hinge, showing the [(potential) interaction forces at the hinge](hinges). 

The free body diagram of the right hinged part of the example model is shown in {numref}`FBD_hinged`.

```{figure} ./FBD_data/FBD_hinged_part_of_structure_NV.png
:name: FBD_hinged
:width: 400px
:align: center

Free body diagram of the right hinged part of the example model
```

```{index} Free body diagram ; of a part of a model
```
### Free body diagram of a part of a model
In the free body diagram of a part of a model, a cut is made at the any arbitrary point, showing the (potential) [internal forces](internal_forces) in the elements.

The free body diagram to the right of a cut just left of point $\text{C}$ of the example model is shown in {numref}`FBD_part`.

```{figure} ./FBD_data/FBD_part_of_structure.png
:name: FBD_part
:width: 400px
:align: center

Free body diagram to the right of a cut just left of point $\text{C}$ of the example model
```

```{index} Free body diagram ; of a point in the model
```
A cut can also be made such that only a single point is left. In that case you can draw the free body diagram of this single point.

The free body diagram of point $\text{B}$ of the example model is shown in {numref}`FBD_point`

```{figure} ./FBD_data/FBD_point_in_structure.png
:name: FBD_point
:width: 400px
:align: center

Free body diagram of point $\text{B}$ of the example model
```
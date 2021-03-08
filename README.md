## Create your very own generative art! ##
This notebook allows you to create your own art by adjusting the inputs. If you are interested in the algorithm and how it works/draws, then the first few cells break it down into steps and displays the outputs at every step for a given set of inputs. However, if you just want to make some cool art then you can just adjust the inputs in the very last cell. These were made using the ipywidgets library. \n
### Inputs ### 
`n`  - number of polygons generated \n

`n_fill_lines` - number of lines inside the polygons\n

`col1, col2, col3` - colours of polygons\n

`min_scalar` - size of centre \n

`function` - function that alters the location of the polygons

`period` - refers specifically to the period of the sine function. Will not make changes if sine is not chosen

`adj_magnitude` - amount polygons are adjusted by function

`min_vertices` - removes all polygons that have the same or lower amount of vertices than the number chosen

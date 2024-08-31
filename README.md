# Bachelor-Thesis

This thesis elaborates on the application of parallel programming to generate fractals. Fractals, due to their recursive nature, present a computational challenge for higher iterations, making them ideal candidates for parallel processing. Using NVIDIA's CUDA platform with cooperative groups, calculations are significantly accelerated compared to traditional sequential methods. The OpenGL library is used to visualize fractals, and CUDA-OpenGL interoperability is used to allow GPU-accelerated calculations to be rendered directly in OpenGL without the need to transfer data to CPU.

Check each submodules on this repository too see in detail the implementation of the each fractal. 

## Koch Snowflake
<p>
   <img src="Latex/koch_7.png">
</p>

<p>
   <img src="Latex/koch_8.png">
</p>

## Fractal Tree
<p>
   <img src="Latex/tree_7.png">
</p>

## Sierpniski Triangle
<p>
   <img src="Latex/triangle_8.png">
</p>

## Mandelbrot Set
<p>
   <img src="Latex/mandelbrot_2.png">
</p>


## Screen-Space VPL Propagation for indirect diffuse illumination (Msc Thesis)

Github: https://github.com/KareshiKraise/GI/tree/SSVP
Paper published at:  https://ieeexplore.ieee.org/document/9265972/ (best paper award)

The project took approximately 3 years and I developed my take on a screen-space indirect lighting algorithm for diffuse inter-reflections.<br /> The project itself is composed of many different algorithms<br /> implemented from other famous papers and consists of multiple passes over the GPU rasterization pipeline.

- Shadow Maps 
- Reflective Shadow Maps,  importance sampled in a view adaptive manner based on Ritschel, 2009 
- Compute Shader Based K-means clustering of Virtual Point Lights
- Paraboloid Shadow Maps computed with geometry Shaders
- A general tone-mapping operator (Reinhart, 2012)
collection: portfolio

---

## Vulkan Studies to learn the API while experimenting with possible 3D Renderer Designs using it.

Github: https://github.com/KareshiKraise/Vulkan_Studies
- Studies and experiments still in progress, based on SaschaWillems code samples, vulkan-tutorial and Graham Sellers’ Official Vulkan Programming Guide.
- Currently designing a material system and experimenting with descriptors layout configuration.
- Eventually to becomea full port of my thesis (top of this document) to the Vulkan API.
collection: portfolio
---

## During my career, I implemented many state-of-the-art and well established CG techniques from research papers and industry references:

---

## Deep G-Buffer

### From the paper: “Deep G-Buffer for stable global illumination approximation” (Mara, McGuire 2016)

Github: https://github.com/KareshiKraise/DeepGBuffer

- Implemented the layered buffers using Geometry Shaders
- Implemented the Screen-Space Ambient Occlusion method proposed by the paper as well, for further comparisons between SSAO techniques.
collection: portfolio
---

## Order-Independent-Transparency

###- Prototype based on the paper “Memory-Efficient Order-Independent Transparency with Dynamic Fragment Buffer”:

- Github: https://github.com/KareshiKraise/Order-Independent-Transparency/tree/main
- Made use of CUDA and OpenGL interoperability.
collection: portfolio
---

## Mesh-Colors
### Prototype based on the paper: “Mesh Colors” from Cem Youksel 2008

- url: http://www.cemyuksel.com/research/meshcolors/meshcolors_techreport.pdf
- Github: https://github.com/KareshiKraise/MeshColors
collection: portfolio
---

## Parametric Curves based Modelling Prototype

- Github: https://github.com/KareshiKraise/Prototype3DModelling
- Developed a prototype 3D mesh modeling application based on bezier curves and solids of revolution in OpenGL.
collection: portfolio
---

## CPU RayTracer
- Github: https://github.com/KareshiKraise/CPURayTracer
- Implementation of basic ray-tracing algorithms and experimented with several optimization techniques.
- The algorithm was re-engineered to run on compute shaders.
collection: portfolio
---

### Several rendering techniques 

-  Normal-mapping
-  Parallax Occlusion Mapping 
-  Relief-mapping
-  Non photo-realistic rendering (cel shading and hatching) 
-  Subdivision Surfaces with tessellation shaders and CGAL.

-  Cel-Shading, POM and Relief Mapping at:
https://github.com/KareshiKraise/CartoonRendering
collection: portfolio
---

## Image Processing and Computer Vision

- implemented the paper:  “Image Abstraction by Structure Adaptive Filtering” Kyprianidis 2008.
- url: https://www.kyprianidis.com/p/tpcg2008/
- Github: https://github.com/KareshiKraise/StructuredAdaptiveFiltering
- In C++ with the OpenCV library
collection: portfolio
---






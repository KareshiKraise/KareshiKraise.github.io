---
Real-Time indirect illumination project developed for my Masters in Computer Graphics

I was awarded the Best Paper Award for publishing the technique:
“Screen-Space VPL Propagation for indirect diffuse illumination”

Github: https://github.com/KareshiKraise/GI/tree/SSVP
Paper published at:  https://ieeexplore.ieee.org/document/9265972/

The project took approximately 3 years where I developed my take on a screen-space indirect lighting algorithm for diffuse inter-reflections. The project itself is composed of many different algorithms implemented from other famous papers and consists of multiple passes over the GPU rasterization pipeline.

- Shadow Maps 
- Reflective Shadow Maps,  importance sampled in a view adaptive manner based on Ritschel, 2009 
- Compute Shader Based K-means clustering of Virtual Point Lights
- Paraboloid Shadow Maps computed with geometry Shaders
- A general tone-mapping operator (Reinhart, 2012)
---







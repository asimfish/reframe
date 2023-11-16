# reframe
Neural Radiance Fields (NeRF) have demonstrated realistic synthesis in 3D reconstruction. However, NeRF struggles to reconstruct scenes with complex reflective appearances. In the meantime, methods that excel in modeling reflective appearances face challenges in achieving real-time rendering. On the other hand, existing real-time rendering methods, especially those based on meshes, often have subpar performance in modeling surfaces with rich view-dependent appearances. To address these limitations, we propose REFRAME, a pipeline that combines real-time rendering with accurate modeling of lighting. Our key idea lies in leveraging meshes for rendering acceleration while incorporating a novel approach to parameterize view-dependent information. Our experiments demonstrate that our method achieves comparable reconstruction quality for highly reflective surfaces compared to existing methods, while also efficiently enabling real-time rendering on edge devices such as smartphones.

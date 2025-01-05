# Light-Field-Frame-Translation

Extended Abstract— In this project, we implement an algorithm for light field frame translation, a technique that focuses on translating frames within a light field to achieve optimization of depth resolution of light field images of a given 3D scene. By translating the frame of reference for a light field image of a 3D scene, the 3D scene can often be imaged at a similar level of detail but with a light field image with a much lower directional resolution.The algorithm is based on 4D representation of a light field and ray tracing techniques to translate the frames and shift the depth range of the captured images. We calculated the ray direction and the perspective intersection point on the introduced frame while adjusting for the frame’s changes in size, focal length, directional resolution and preserving the image quality.  
The proposed method is then tested on synthetic graphics that are pre-rendered into a light field image and tentatively on real-world light field images captured of a static scene using a controlled camera. We employ a simulator developed based on ray tracing techniques to visualize the images to evaluate the effectiveness and accuracy of our methods in producing high-quality light field frames applicable to virtual reality, augmented reality, and computational photography. The suggested solution aims to maintain the quality and realism of the translated frames while enhancing computational efficiency. This can further extend to more complex non-planar 4D representations of light fields and shifting the respective frames to achieve maximum optimization.  



Keywords: Light Field, Frame Translation, Ray tracing, Visual computing  
Anahita Nik aien: anikaien@mun.ca  
Nicholas Wells: nwwells@mun.ca  
Matthew Hamilton: mhamilton@mun.ca  
Department of Computer Science, Memorial University of Newfoundland   

  
  
References:
[1] Marc Levoy and Pat Hanrahan. Light field rendering. In Proceedings of the 23rd Annual Conference on Computer Graphics and Interactive Techniques, SIG-GRAPH ’96, page 31–42, New York, NY, USA, 1996. Association for Computing Machinery.
[2] Nicholas William Wells. Real-time ray traced cinematic quality light field viewer, 2021. Honours thesis, Memorial University of Newfoundland, Department of Computer Science.

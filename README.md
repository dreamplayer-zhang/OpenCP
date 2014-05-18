OpenCP
======
library for computational photography

Todo
----
* update type of the destination of the SLIC. mean image? mesh? 
* port various filters from my library.

Filter
------
###implemented and parallerized
######filter   
  Gaussian IIR filter  

######edge preserving filter  
  *bilateral filter and its fast implimentations or variants*  
      *sepalable filter  
      *bilateral grid  
      *realtime O(1) birateral filter  
      *joint bilateral filter  
      *trilateral filter  
      *dual bilateral filter  
      *weighted (joint) bilateral filter  
    
  *cost volume filters*
   *3D birateral filter  
   *3D guided filter    
  
  trilateral filter  
  non-local means filter  
  shiftable DXT thresholding filter  
  guided filter  
  domain transform filter  
  weighted mode filter  
  constant time median filter  
  joint nearest filter
######segmentation  
  SLIC  (forked from VLFeat(http://www.vlfeat.org/). The code, which is optimized by SSE and Intel TBB, is more efficient than the VLFeat.)
######upsample
  joint bilateral upsample  
  guided upsample  
  hqx  
  
**implimented but not optimized**  

*filter*
  L0 Smoothing  
  adaptive maniforld  


**Application**
-----------
  +denoise  
  +flash/non flash  
  +up sample  
  +HDR  
  +Haze remove  
  +depth map refinement  
  +optical flow refinement    

References
----------
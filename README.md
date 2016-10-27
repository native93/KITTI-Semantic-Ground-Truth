# KITTI-Semantic-Ground-Truth

Authors = {Nazrul Haque, Dinesh Reddy and K. Madhava Krishna}
Robotics Research Center, IIIT Hyderabad, India. - http://robotics.iiit.ac.in/

The repository contains semantic Ground Truth annotations for 200 images from KITTI Tracking dataset[Geigar].

The zip file contains two directories.
annotated-dataset
|--RGB  - Contains RGB images from KITTI Tracking dataset (Geigar)
|--GT - Contains pixel-wise Ground Truth annotations for 11 semantic classes.

The Ground Truth label spectrum is given below:

        **Class**       **Colour**    **R    G    B**
 
         Building         Red          128  0    0
         Vegetation       Yellow       128  128  0 
         Sky              Grey         128  128  128
         Car              Purple       64   0    128
         Sign             Salmon       192  128  128 
         Road             Pink         128  64   128
         Pedestrian       Red          64   64   0
         Fence            Grey-Purple  64   64   128 
         Pole             Light-Yellow 192  192  128
         Sidewalk         Blue         0    0    192
         Cyclist          Light-Blue   0    128  192
         
         
 References:
 
 [1] A. Geiger, P. Lenz, and R. Urtasun, “Are we ready for autonomous driving? the KITTI vision benchmark suite”, CVPR, 2012      Link - http://www.cvlibs.net/datasets/kitti/
 
 [2] G. Ros and S. Ramos and M. Granados and A. Bakhtiary and D. Vazquez and A.M. Lopez, "Vision-based Offline-Online Perception Paradigm for Autonomous Driving". Link - http://adas.cvc.uab.es/s2uad/

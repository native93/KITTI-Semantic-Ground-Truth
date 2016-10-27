# KITTI-Semantic-Ground-Truth

Authors = {Nazrul Haque, Dinesh Reddy and K. Madhava Krishna}
Robotics Research Center, IIIT Hyderabad, India. - http://robotics.iiit.ac.in/

The repository contains semantic Ground Truth annotations for 200 images from KITTI Tracking dataset[Geigar].

The zip file contains two directories.<br>
annotated-dataset <br/>
|--RGB  - Contains RGB images from KITTI Tracking dataset (Geigar) <br/>
|--GT - Contains pixel-wise Ground Truth annotations for 11 semantic classes. <br/>

The Ground Truth label spectrum is given below:
<table>
       <thead>
              <tr>
              <th>Class</th>
              <th>Colour</th>
              <th>R</th>
              <th>G</th>
              <th>B</th>
              </tr>
       </thead>
       <tbody>
              <tr>
              <td>Building</td>
              <td>Red</td>
              <td>128</td>
              <td>0</td>
              <td>0</td>
              </tr>
              <tr>
              <td>Vegetation</td>
              <td>Yellow</td>
              <td>128</td>
              <td>128</td>
              <td>0</td>
              </tr>
              <tr>
              <td>Sky</td>
              <td>Grey</td>
              <td>128</td>
              <td>128</td>
              <td>128</td>
              </tr>
              <tr>
              <td>Car</td>
              <td>Purple</td>
              <td>64</td>
              <td>0</td>
              <td>128</td>
              </tr>
              <tr>
              <td>Sign</td>
              <td>Salmon</td>
              <td>192</td>
              <td>128</td>
              <td>128</td>
              </tr>
              <tr>
              <td>Road</td>
              <td>Pink</td>
              <td>128</td>
              <td>64</td>
              <td>128</td>
              </tr>
              <tr>
              <td>Pedestrian</td>
              <td>Yellow-Brown</td>
              <td>64</td>
              <td>64</td>
              <td>0</td>
              </tr>
              <tr>
              <td>Fence</td>
              <td>Grey-Purple</td>
              <td>64</td>
              <td>64</td>
              <td>128</td>
              </tr>
              <tr>
              <td>Pole</td>
              <td>Light-Yellow</td>
              <td>192</td>
              <td>192</td>
              <td>128</td>
              </tr>
              <tr>
              <td>Sidewalk</td>
              <td>Blue</td>
              <td>0</td>
              <td>0</td>
              <td>192</td>
              </tr>
              <tr>
              <td>Cyclist</td>
              <td>Light-Blue</td>
              <td>0</td>
              <td>128</td>
              <td>192</td>
              </tr>
        </tbody>
       </table>
         
         
 References:
 
 [1] A. Geiger, P. Lenz, and R. Urtasun, “Are we ready for autonomous driving? the KITTI vision benchmark suite”, CVPR, 2012      Link - http://www.cvlibs.net/datasets/kitti/
 
 [2] G. Ros and S. Ramos and M. Granados and A. Bakhtiary and D. Vazquez and A.M. Lopez, "Vision-based Offline-Online Perception Paradigm for Autonomous Driving". Link - http://adas.cvc.uab.es/s2uad/

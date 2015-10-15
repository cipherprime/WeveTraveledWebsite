/*
Title: The Light Booth
*/

# The Light Booth
*Auditorium Duet*, more than anything else, is meant to bring people together. We wanted to reflect that by putting you in the experience.

The [Leap Motion] device you are holding was originally designed to track hand motions for computer input. It houses two infrared (IR) sensors that detect the distance to objects in its field of view. By repurposing those sensors, we are able to generate a three-dimensional representation of the real world within *Duet*. Watch the beams of light ebb and flow around your face—and most importantly, have fun!




## The Process

![Raw Depth Input](/content/images/process/01%20Raw%20Depth%20Input%20-%20scaled.png)
### 01 Raw Depth Input
The Leap Motion houses two infrared (IR) cameras to detect depth. This is what it sees.

![Surface Mapping](/content/images/process/02%20Surface%20Mapping%20-%20scaled.png)
### 02 Surface Mapping
A Sobel filter is applied to generated a normal map that will be used to add more detail to the displacement later.

![Particle System](/content/images/process/03%20Particle%20System.png)
### 03 Particle System
Auditorium Duet's particle system, Rho, uses generated meshes to represent simulated particles a ribbons of light.

![Texture and Color](/content/images/process/04%20Texture%20and%20Color.png)
### 04 Texture and Color
Combining the last three passes yields this result.

![Threshold](/content/images/process/05%20Threshold.png)
### 05 Threshold
With a basic threshold, we can remove objects that are too far from the camera.

![Depth Displacement](/content/images/process/06%20Depth%20Displacement.png)
### 06 Depth Displacement
Using the depth image and the normal map, we distort the particle system to flow across the subject.

![Camera Bloom](/content/images/process/07%20Camera%20Bloom.png)
### 07 Camera Bloom
Using [Sonic Ether's package][Sonic Ether], we generate light from the particles, simulating the interactions that take place in a real camera lens.

![Depth Masking](/content/images/process/08%20Depth%20Masking.png)
### 08 Depth Masking
Now, with our virtual camera, we detect distance and use that generate a new depth mask.

![Final](/content/images/process/10%20Final.png)
### 09 Depth of Field
Finally, we apply a Depth of Field effect, simulating the focal depth of a real camera. This is the final result.



[Leap Motion]: http://www.leapmotion.com/
[Sonic Ether]: http://google.com
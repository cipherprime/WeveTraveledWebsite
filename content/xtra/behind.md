/*
Title: Behind the Scenes
Author: Cipher Prime
*/

### Find out more about
* [The Light Selfie Booth](#selfie_booth)




# How to Make a Selfie Light Booth
*** 


1. ![Raw Depth Input]
2. ![Surface Mapping]
3. ![Particle System]


### 01 Raw Depth Input
The Leap Motion uses two infrared (IR) cameras to detect depth. This is what it sees.

### 02 Surface Mapping
A Sobel filter is applied to generated a normal map that will be used to add more detail to the displacement later.

### 03 Particle System
Auditorium Duet's particle system, Rho, uses a dynamically-generated mesh to represent simulated particles as ribbons of light.

# *

1. ![Texture and Color]
2. ![Threshold]
3. ![Depth Displacement]


### 04 Texture and Color Correction
Combining the last three passes yields this result.

### 05 Threshold
With a basic threshold, we can remove objects that are too far from the camera.

### 06 Depth Displacement
Using the depth image and the normal map, we distort the particle system to flow across the subject in three dimensions.

# *
<div id="#selfie_booth"></div>
1. ![Camera Bloom]
2. ![Depth Masking]
3. ![Final]


### 07 Camera Bloom
Using [Sonic Ether's bloom tech][Sonic Ether], we generate light from the particles, simulating the interactions that take place in a real camera lens.

### 08 Depth Masking
Now, with our virtual camera, we detect distance and use that generate a new depth mask.

### 09 Depth of Field
Finally, we apply a Depth of Field effect, simulating the focal depth of a real camera. This is the final result.

# *

<p>
<iframe src="//player.vimeo.com/video/143423100?autoplay=1&loop=1" width="800" height="1200" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</p>

## 10 Put it Together in Real Time
All of this is done in real time, yielding an effect unlike any you've seen.

***

![Image 1]
# Reception

***

![Image 11]
![Image 12]
![Image 13]
# Unity3d and Print Testing

![Image 2]
# Duality

***

![Image 3]
![Image 5]
![Image 14]
# Sigilis

***

![Image 4]
![Image 15]
# PostCard

***

![Image 6]
![Image 7]
![Image 8]
# Booth Construction

***

![Image 9]
![Image 10]

# Selfie Sleeves

***

![Violin 1]
![Violin 2]
![Violin 3]
![Violin 4]
![Violin 5]
# Light Violins

[Raw Depth Input]: /content/img/behind_the_scenes/booth_process/01%20Raw%20Depth%20Input%20-%20scaled.png
[Surface Mapping]: /content/img/behind_the_scenes/booth_process/02%20Surface%20Mapping%20-%20scaled.png
[Particle System]: /content/img/behind_the_scenes/booth_process/03%20Particle%20System.png
[Texture and Color]: /content/img/behind_the_scenes/booth_process/04%20Texture%20and%20Color.png
[Threshold]: /content/img/behind_the_scenes/booth_process/05%20Threshold.png
[Depth Displacement]: /content/img/behind_the_scenes/booth_process/06%20Depth%20Displacement.png
[Camera Bloom]: /content/img/behind_the_scenes/booth_process/07%20Camera%20Bloom.png
[Depth Masking]: /content/img/behind_the_scenes/booth_process/08%20Depth%20Masking.png
[Final]: /content/img/behind_the_scenes/booth_process/10%20Final.png


[Leap Motion]: http://www.leapmotion.com/
[Sonic Ether]: https://www.assetstore.unity3d.com/en/#!/content/17324



[Image 1]: /content/img/behind_the_scenes/city%20paper%20october%205th%202015.jpg
[Image 2]: /content/img/behind_the_scenes/duality.jpg
[Image 3]: /content/img/behind_the_scenes/IMG_0266.JPG
[Image 4]: /content/img/behind_the_scenes/IMG_0392.JPG
[Image 5]: /content/img/behind_the_scenes/IMG_0411.JPG
[Image 6]: /content/img/behind_the_scenes/IMG_0501.JPG
[Image 7]: /content/img/behind_the_scenes/IMG_0526.JPG
[Image 8]: /content/img/behind_the_scenes/IMG_0549.JPG
[Image 9]: /content/img/behind_the_scenes/IMG_0579.JPG
[Image 10]: /content/img/behind_the_scenes/IMG_0580.JPG
[Image 11]: /content/img/behind_the_scenes/IMG_0585.JPG
[Image 12]: /content/img/behind_the_scenes/IMG_2145.JPG
[Image 13]: /content/img/behind_the_scenes/IMG_2175.JPG
[Image 14]: /content/img/behind_the_scenes/IMG_2196.JPG
[Image 15]: /content/img/behind_the_scenes/postcard_front_printready.png

[Violin 1]: /content/img/behind_the_scenes/violins/IMG_2154.JPG
[Violin 2]: /content/img/behind_the_scenes/violins/IMG_2155.JPG
[Violin 3]: /content/img/behind_the_scenes/violins/IMG_2156.JPG
[Violin 4]: /content/img/behind_the_scenes/violins/IMG_2157.JPG
[Violin 5]: /content/img/behind_the_scenes/violins/IMG_2158.JPG
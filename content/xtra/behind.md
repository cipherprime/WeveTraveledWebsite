/*
Title: Behind the Scenes
Author: Cipher Prime
*/

![Large Piece Overview]

### Find out more
With any kind of art show, there are so many things that happen behind the curtain. We really wanted to pull that back a little. Here are some general sections of good stuff.


1. [Selfie Booth Digital Construction Process](#)
2. [Selfie Booth User Testing](#)
3. [Selfie Booth Construction](#)
4. [Light and Dark Compositions](#)
5. [Sigils and Painting](#)
6. [Original Concept Art](#)
7. [Postcard](#)
8. [Light Violins](#)

*** 

# How to Make a Selfie Light Booth

# *

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
<iframe src="//player.vimeo.com/video/143423100?autoplay=1&loop=1" width="400" height="600" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</p>

## 10 Put it Together in Real Time
All of this is done in real time, yielding an effect unlike anything you've ever seen.

# *

![Selfie Booth in Unity3d]

2. ![Selfie Booth Screenshot Test]
3. ![Selfie Booth Print Test]

# Software and Print Testing
We created the Selife Light Booth using a popular game engine we're farmiliar with called *Unity3d*. The beams of light were originally created for *Auditorium Duet*, the sequal to our very first game *Auditorium*.

One of our biggest concerns in this whole process was having beauitful, fast, and affordable prints. After quite a few printer tests, we settled on using a *Canon Selphie*. Here is our very first print test on this printer. [Above Right]

# *

![Selfie Booth User Test]

# Full User Testing
We spent quite awhile talking about what the process of printing would look like. What was the kind of experience we wanted someone to have when they walked up and played with the booth? How many photos could they take? Ultimately, we decided to use a piece of iPad software called *Lite Booth* to handle these needs. After some extensive testing, we were able to get the process down flawlessly.

# *

![Selfie Booth Electronic]

# Hardware
We used *Arduino* to interface with our Light Selfie Booth Application. We used a glowing white button for taking your selfie with two knobs used to control hue and saturation. We have a lot of fun variables to with, but ultimatly went with this simple interface. It might be cool to add controls for things like turbulence in the future.

# *

1. ![Selfie Booth Construction]
2. ![Selfie Booth Without Top]

# Booth Construction
It's sort of ridiculous how hard it was to find a cheap white presentation platform. Searching online yielded few affordable options, so we opted to create out own. The entire process of creating the booth took around 3 days. We also created our own square tool from scrap timbler we had laying around.

# *

1. ![Sigil Rubber Block]
2. ![Stamped Wax Paper Sleeves]

# Selfie Sleeves
Art is all about the experience, so we created Wax Paper Sleeves by carving the Auditorium Duet Logo into a Rubber Block and hand stamping them. This was a very lengthly process, but yield a nice simple and sexy result.

***

![Light and Dark Compositions]

# Showing Duality Between the Past and the Future
From the moment we had accepted the challenge of creating this show, we knew we wanted to offer at least 3 scales of pieces. But more important, we also knew we wanted the medium and large pieces to mirror each other. A lot of care and craftsmanship went into making sure we could portay both worlds with the exact same content.

***

![Original Concept Art]

# Original Concept Art
The world of Auditorium is quite flat. At some point we came up with the idea of using the background of the game as a horizon line to create unique compositions. With the thought of creating a brand new rendered in mind, this was the final concept design that was created before development of this new rendering technique was kicked off.

***

1. ![Sigil Sketches]
2. ![Typtic Painting in Progress]

# Sigils and Painting
Each large pieces was printed with archival ink then hand-embelished with their respective sigil's. These sigil's represent the mood and spirit of each world these game elements are encountered in *Auditorium Duet*. Here you can see Sean Marorana from Indy Hall Arts taking a look at our tryptic during it's initial painting process.

***

1. ![First Draft Postcard]
2. ![Print Ready Postcard]

# PostCard
This was our very first art show! Of course we made some baller postcards to celebrate. Our initial concept used the title *Auditorium Duet* before we had completely finalized the show name *We've Traveled So Far*.

***

![Light Violin]

# Light Violins
Not everything makes it into a show. Here was the very first draft of our Light Vilions we were going to use for the window display. 




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

[Light and Dark Compositions]: /content/img/behind_the_scenes/duality.jpg

[Original Concept Art]: /content/img/behind_the_scenes/duet_concept_art.jpg

[First Draft Postcard]: /content/img/behind_the_scenes/postcard_first_draft.jpg
[Print Ready Postcard]: /content/img/behind_the_scenes/postcard_front_printready.png

[Sigil Sketches]: /content/img/behind_the_scenes/sigil_sketches.jpg
[Typtic Painting in Progress]: /content/img/behind_the_scenes/typtic_painting_progress.jpg

[Selfie Booth Electronic]: /content/img/behind_the_scenes/selfie_booth_electronics.jpg
[Selfie Booth Construction]: /content/img/behind_the_scenes/selfie_booth_contruction.jpg
[Selfie Booth Without Top]: /content/img/behind_the_scenes/selfie_booth_raw.jpg

[Sigil Rubber Block]: /content/img/behind_the_scenes/sigil_rubber_block.jpg
[Stamped Wax Paper Sleeves]: /content/img/behind_the_scenes/stamped_wax_paper_sleeves.jpg

[Selfie Booth Screenshot Test]: /content/img/behind_the_scenes/selfie_booth_unity3d.jpg
[Selfie Booth Print Test]: /content/img/behind_the_scenes/selfie_booth_first_print.jpg
[Selfie Booth in Unity3d]: /content/img/behind_the_scenes/selfie_booth_unity3d.png

[Selfie Booth User Test]: /content/img/behind_the_scenes/selfie_booth_user_test.jpg

[Large Piece Overview]: /content/img/large/overview_pieces_ground.jpg

[Light Violin]: /content/img/behind_the_scenes/violins/light_violin.jpg
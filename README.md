Synesthesizer-II
================

An artistic interface for musical expression. A musical instrument that sonifies drawings made using colored pencils on a canvas/drawing sheet.

The concept is to map colors and shapes to music through Russell's Circumplex Emotion Model. 

Performance on this instrument requires a USB camera, Max MSP Runtime or the full version and Ablteon Live.

Emotional descriptors are mapped to different scales from Carnatic Music. Markov chains are used as the generative music process, controlling pitch, velocity and rhythm. Weighted distribution of the colors is used to control the timbre.

To setup, place the canvas/drawing sheets horizontally on a surface or on the floor. Place the camera vertically above the canvas, suspended by a stand. Adjust the height of the stand until the entire canvas can be viewed. Download the mxf file and run it using Max MSP runtime. Download the 'Synthesis' Ableton Project and run it using Ableton Live 8 or above. Both Max MSP and Ableton Live must be running simultaneously. In the Max Patch, adjust the camera settings until colors are seen brightly and the background is completely white. Click on the square button to start the instrument. Click on "Live Camera" to start the camera. Click on the circular button or press space bar to update the drawing as you progress through the drawing process.

The GUI:
	The four colored circles represent the current scale playing. The rate at which it blinks is the tempo. The bigger rectangular bar is the scale probability distribution based on the area of the color on the drawing. The four smaller rectangular bars represent the octave range of the scale that the Synesthesizer will play. The small grey rectangles above the small circles represent the current rhythm pattern.
 
Alternatively, static images of size 320x240px can be generated using Photoshop or Paint (JPEG or PNG) and sonified. Click on 'Image File' for this mode.

  
If you want to view the source, additionally, download the Max patch and the folders "Rhythm" and "ScalesNew". Place the folders in Applications/Max6/patches/templates/'New Folder Name'.

Video demonstrating its features will be added soon.



Note: Emotional Descriptors (in Sanskrit, ancient Indian language) used are-

Happy (Yellow): Hasya

Serene (Green): Shringara

Gloom (Blue): Bhibatsya

Anger (Red): Roudra 

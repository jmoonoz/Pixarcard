# Pixar Ray Tracing card
Pixar ray tracing code!

This card was handed to me at a Pixar seminar, held at CSUEB.
The back of the card contains a bunch of crunched up code that seems almost illegible to read.
Upon further investigation it is actually base off a famous coding technique called "raytracing", with one of the most well-known created by Andrew Kensler (aek).

Took me a while to figure out how to get it working, but the process is fairly simple. Here are the steps I took:

1. Write the code out from the image and onto a text file. 
2. Once the code is written out from the image (and well structured) be sure to save it as a .cpp (recommended saving it as “pixar.cpp”)
3. Open up a terminal and locate the files current directory
4. Once in the correct file location write out in the terminal
 	'c++ -O3 -o card pixar.cpp'
(wait shouldn’t be long)
  	Then write out
'./card > pixar.ppm'
the process from here will take some time, about a minute or two.
what is happening is the pixar.cpp file was converted to another file now named card, which translated the code within into an image code. Then after the “card” file was converted into a .ppm file called pixar, which will create the image effect. 

5. Once the terminal finishes processing the file go within your actually systems directory where your files are at and you’ll find the newly create pixar.ppm file. For Mac is should open up fairly easy, widows you might need an application to open the file. Once the file is open an image will appear rending what the code has created, That is the magic of Raytracing!!

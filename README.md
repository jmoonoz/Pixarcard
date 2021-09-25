# Pixar Ray Tracing card
Pixar ray tracing code!

This card was handed to me at a Pixar seminar, held at CSUEB.
The back of the card contains a bunch of crunched up code that seems almost illegible to read.
Upon further investigation it is actually base off a famous coding technique called "Raytracing"

Took me a while to figure out how to get it working, but the process is fairly simple. Here are the steps I took:

1. Write the code out from the image and onto a text file. 
2. Once the code is typed out onto a text file from the image (and well structured) be sure to save it as a .cpp (recommended saving it as “Pixar.cpp”).
3. Open up a terminal and locate the files current directory.
4. Once in the correct file directory type in the terminal 'c++ -O3 -o card Pixar.cpp' and press enter (wait shouldn’t be long).
5. Then type in the terminal './card > Pixar.ppm' and press enter. the process from here will take some time, about a minute or two. During which your terminal will show that its running a process, its converting the card file into the Pixar.ppm file format.
6. Once the process is complete locate the directory where your files are located an youll see a newly added file Pixar.ppm. click on that file and an image will redner!(depending on your operating system you may need to utalize an application like photoshop to view the file, I used a macbook pro and it worked fine with preview)



# The Watershed Project
**Jarrett Philips, Liam McDonald**

### Objective
The objective of this computer science project was to map out watershed and flow in a given location. We both knew that we wanted to do something having to do with the outdoors, as we both love being outside, but we weren’t sure what kind of project we wanted to do. Eventually we decided that a program that models the waterflow in a specific area would be the best combination of computer science and the outdoors that we love. although the object of our program is to show the way in which water flows in a certain area, our main objective of the project was to create a functioning program that both shows what we have learned in this computer science class, and what we ourselves are interested in. 

### Description
To create this program we had to use heightmaps, grayscale maps within a color range of 0 to 255. The grayscale represents the elevation in the maps. The reason we used heightmaps was their capability to show elevation and accessibility with programming. After starting up the project, the user is taken to a GUI that we created. This GUI has four panes, one for controls, input, info, and help. The input panel has text fields where the user can enter in the amount of rainfall in centimeters, the amount of snowfall in centimeters, and the saturation percent. The saturation is the percent of water absorbed by each pixel in each tick of time. It also has a setup button which is clicked after entering all the inputs to up the map and simulation. The control panel has two buttons, cycle and reset. They cycle button uses the algorithm we created to make the water flow for one tick of time. It will then update the map, and shows the water on the map with blue. The reset button will clear the map and set up the simulation so it is ready to start again. The info panel shows how much water, the elevation, and the groundwater for the pixel clicked with the cursor. The help panel explains how to run the program. Once we got into the project we realized how complicated the algorithms and equations for waterflow were. We decided that because this was a computer science project, not a hydrology project, we would create our own basic algorithm for waterflow. Each pixel will parse out water to it’s surrounding pixels based on the change in elevation. If the pixel next to the one parsing water has a greater elevation than the original, then no water will be parsed to that pixel. More water flows to the surrounding pixels with a greater change in elevation. 

### Testing
We did many things to test our project. The main thing we had difficulty with and had to test many many times was the algorithm for the waterflow. We did these tests in many different ways. One of the most efficient tests was creating our own custom images with prearranged elevations. We made these images small so we could print out the matrix of information onto the console. To test we would print out the elevation, depth, depth after the flow, and every step of the flow process. We made images with varying heights and widths, and varying elevations to make sure that our algorithm worked with any map given to it. 

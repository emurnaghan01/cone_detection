# QUB Cone Detection Project

In this project, the SSD MobilNet V1 model was trained on cone images and then applied to video footage from the QUB Formula Student Entry for 2018.

Using Pandas, OpenCV and Numpy libraries, the traffic cone detections were then extracted from the model, located in space and used to plot a predicted trajectory for the vehicle.

A feedback response could then be relayed to the vehicle, but this is yet to be explored.

Train and test labels can be found in the /data directory. 

Trained model can be found in the /cone_graph directory

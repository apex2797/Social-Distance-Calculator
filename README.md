# Social-Distance-Calculator
## By Siraj
Calculating Distance between Two Box ( human ) using OpenCV and Smart Nueral Netowrk<br/>

Used Eagle Eye(view) technique 
1.	Loop and detect the shape using openCv and calculation the confidence value same as mask detection.<br/>
2.	Detecting the bounding box and using the Kmeans Clustering to cluster all the detected bounding boxes and their co-ordinates.and draw a square box around the detected humans and use calcDistance method to calculate the distance <br/>
3.	After that again I’m looping through all the dictionary [positions] that has been stored and again loop through the position keys this is for medium risk (j) and high-risk(i) variations. Now using Python math method and use sqrt, pow method to calculate the distance of bounding boxes.<br/>
Mathematical cals : - if distance of bounding boxes is smaller than 150 cm then it values are added to sets – high-risk.<br/>
				- if distance of bounding boxes is smaller than 200 cm and below 150 cm then its values are added to sets – med-risk
And then adding frame text in screen using putText method and updating all values to the frames.<br/>



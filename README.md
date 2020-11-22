# Using-Video-Images-to-ID-Heartrate
This Project will test different computation methods of identify human heart-rate/pulse, from video images of vascular areas, like face, hands, feet and eyes.
Detecting heart rate in video consists of at least three steps: (1) identifying a Region of Interest (ROI) containing heart rate/pulse information [Modernly, 
resources employ opensource facial detection and recognition libraries, like dlib Python/C++ (See Also OpenCV)]; (2) extracting photoplethysmographic signals 
from the ROI, and (3) analyzing changes in pixel colors within those signals, over a sample period, to determine prominent changes responding to the 
heart rate range (30 - 240 beats per minute). Essentially, the computational model looks for any pixelation color changes, within RBG model, 
that correspond to heatbeats. (But see Linda Null & Julie Lobur, The Essentials of Computer Organization and Architecture (third edition), 2003/2014 
(pg439–440 in 1st edition, pg 658 in 3rd edition): a neural network trained to detect tanks which instead learned to distinguish between sunny and cloudy days.
 

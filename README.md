introduction
----------------------------------------------------

TBD


prerequisites
----------------------------------------------------

1. python 2.7 (might work also with python 3.x though we haven't tested it)
2. theano
3. python packages: cPickle, gzip, numpy, scipy, cv2



counting live from camera
----------------------------------------------------

This script operates our live counting system using a webcam as input.
make sure you have webcam connected  
1. connect a web cam  
2. go to live_count folder and run:
> python live_rep.py 


Alternatively, You can stream from file using:  
live_count/live_rep.py -i "file_name"  
You can try as an input our captured long live video, located at data/cam. i.e: 
> python live_rep.py -i ../data/cam/live.avi


running YTIO benchmark
----------------------------------------------------

download YTIO benchmark videos from "..."
run "live_rep_YTIO.py -i "folderName" where folderName contains the YTIO videos
example:
> python live_rep_YTIO.py -i "/home/olevy/rep/ytio_vids/"



running segmented benchmark with online entropy
----------------------------------------------------





running segmented benchmark with offline entropy
----------------------------------------------------




create a synthetic training data set and classifier
----------------------------------------------------


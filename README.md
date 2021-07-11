Used cv2 (OpenCV module) used for reading and writing images and to input a video stream,
KNN algorithm , Haar Cascades classifier

● Generating Training Data: captured images from your webcam video stream
and extracted faces using haar cascades. The largest face was gray scaled and the
info of faces was stored in numpy arrays.

● Building The Face Classifier: Read a video stream using opencv and extracted
faces out of it, used KNN algorithm to predict the name and display a label with
corresponding name. ( y- labels stored against the x- numpy arrays i.e loaded
training data)

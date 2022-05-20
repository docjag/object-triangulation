# Object Triangulation using stereo camera and epipolar geometry
Determine the pose (orientation and transformation) of an object from two different perspectives. At each of the two locations, the camera detects the centroid of the object. The goal of this task is to find the XYZ coordinates of the object. The details are as follows:
* The XYZ locations of the camera center are labeled as p1 and p2.
* The heading of the drone is given by angles θ1 and θ2 in degrees from the Y axis.
* The drone is hovering level with the XY plane (and assume it does not have a gimbal).
* The XY pixel coordinates of the detections are labeled as d1 and d2. They are close but not exact.
* The camera is an exact linear pinhole camera with a focal length of 270 pixels and resolution 640x480 pixels. You can assume pixels are square.
* Pixel coordinates (0, 0) are the top left of the image.
* The world Z axis is out of the screen.
* The object is stationary between the two views.


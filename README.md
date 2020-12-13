# Camera_calibration
Camera calibration involves obtaining the extrinsic and intrinsic parameters of a camera. Intrinsic parameters of a camera are concerned with the camera’s internal features such as the focal length, the optical center (also known as the principal point), and the skew coefficient. The extrinsic parameters relate to the orientation of the camera with respect to the world coordinate system.

Calibration can be achieved with the planar and non-planar methods. We use the non-planar method to calibrate the camera and this involves using a single view of the calibration target to obtain the 3-D points needed for calibration. A projection matrix is calculated given the corresponding pairs of points and the camera parameters are obtained by decomposing the projection matrix and using some orthogonal and orthonormal properties of the camera’s rotation matrix.

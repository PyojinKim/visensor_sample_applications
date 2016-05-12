visensor_sample_applications
===================

This repo contains a few sample standalone applications for the VI-Sensor.
(Note: PyojinKim rolls back to the previous version, especially before the "update to new calibration API". Up-to-date "visensor_sample_applications" is not compatible with the current libvisensor library https://github.com/ethz-asl/libvisensor)

* **vi_sensor_interface**: A very basic interface to the VI-Sensor. Receives images and IMU messages and displays it using openCV.

* **vi_sensor_save_stereo_image**: Save the current left and right images and display them using openCV.

* **vi_sensor_stereo_block_matcher**: Applies rectification to Vi-Sensor images and subsequently computes the disparity image using standard openCV block matcher. Intrinsic & extrinsic calibration parameters for rectification are downloaded from VI-Sensor.

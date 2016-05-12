vi_sensor_save_stereo_image
===================

Simple example on how to save the VI-Sensor stereo images using openCV

Build instructions
==================
Download libvisensor and install it if you have not done that before

<pre><code>
git clone https://github.com/ethz-asl/libvisensor.git
cd libvisensor
./install_libvisensor.sh
</code></pre>

Now, were building the interface

<pre><code>
cd vi_sensor_save_stereo_image
mkdir build
cd build
cmake ..
make
cd ../bin
./vi_sensor_save_stereo_image
</code></pre>


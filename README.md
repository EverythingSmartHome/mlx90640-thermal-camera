# mlx90640-thermal-camera
A python script for an MLX90640/MLX90641 thermal imaging camera on the Raspberry Pi.

# Requirements
There are a few libraries that this project requires:
* python-matplotlib, python-scipy, python-numpy, python-smbus through apt/dnf or pip
* RPI.GPIO, adafruit-blinka, adafruit-circuitpython-mlx90640 through pip

# Guide
Full guide is available [here](https://everythingsmarthome.co.uk)

# How to use
With the above requirements set, you need to make sure the i2c interface is set in the Raspberry Pi's config.txt file, along with the baudrate set to 400kbits/s. After this, simply run one of the two scripts to start the camera. You may use the --mirror switch when starting from the command line in order to flip the image if you have the camera front facing. Rear facing camera does not require this switch.

# Credits
This code was adapted from MakersPortal guide [here](https://makersportal.com/blog/2020/6/8/high-resolution-thermal-camera-with-raspberry-pi-and-mlx90640)

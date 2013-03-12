#libraspcam

The Raspberry Pi Camera Library allows you to use to program with the camera module quickly and
easily. This library can be used in a variety of programming languages including Python. 

##Features

libraspcam allows the following features:

* Take a photo
* Take a photo after a delay
* Take X photos at intervals of Y
* Record a video
* Record a video for a specified period of time
* Apply filters to the photo
* Convert the photo to a specific format (GIF, JPEG, BMP)
* Add EXIF information such as GPS using Adafruit's GPS addon or a GeoIP service
* Verify device connectivity
* Send photos via Email
* Upload video to YouTube

##Getting Started

Getting started with libraspcam is easy. You'll need to install libraspicam for your 
preferred programming language first. For example to install libraspicam for Python 
support, you can run the following command under Raspbian:

sudo apt-get install libraspcam-python

###If you would like to build from source:

git clone https://github.com/samnazarko/libraspcam.git
cd libraspcam

Install build dependencies:

sudo apt-get update
sudo apt-get install python-dev swig libcurl-dev build-essential

To build with Python support:

make python
make install

Now, you can use this library to develop using the Raspberry Pi camera

##Examples and Documentation

Full examples and documentation are available in examples/ and doc/ respectively. 

You can also see this YouTube video for a quick introduction which shows you how to get started with
the library:

TBC

##Special thanks to

The Raspberry Pi Foundation, with special thanks to:

	Dom Cobley
	Gordon Hollingworth

You, for using this!

##Help and support

For support you can speak to other users on the Stm Labs forums at http://forum.stmlabs.com. The community
is bustling and always eager to help!

##Contributions

Patches and contributions are always welcome. Just fork and create a pull request!

Happy Snapping!

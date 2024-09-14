# TouchDesigner interface for a VUDial

This is a TOX file which acts as an interface for the [VUDial](https://vudials.com/). 

## Installation Instructions

- Install the [VU Server](https://github.com/SasaKaranovic/VU-Server) using the instructions in the Git Repo. 
- Create and copy a new API Key.
- Copy the UID of the VU Dial.
- In your TouchDesigner file, import the TOX file.
- Paste the Key and UID into the properties of the VUDial TOX. 

## Operation Instructions

- Connect a CHOP of data to the inValue connector on the VU Dial TOX. The example in the TOE file uses a Perform CHOP with FPS turned on. 
- In the VUDial TOX properties, set the Value Range to a low and high value that corresponds with the range you want your VU Dial to display. 
- Set the Color of the LEDs using the color picker. 
- To adjust the image, change the label to suit the data you are displaying. Press Save Image, then press Upload Image. The VUDial screen should flicker and the new image will display. If the CRC of the image is the same as a previous image, the Textport will display an error message. 
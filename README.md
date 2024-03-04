GutterCam2

This is an updated version of GutterCam I made. The updated version has a simple web interafce to turn on/off the flash on the ESP Webcam board.
The original code used the camera code available in the library pack that supports the ESP webcam baord. For my use there were too many variables to play with. 
The GutterCam was designed for a friend who can no longer climb ladders to check out his guttters on a 2 story house. He has leafguard installed, but still
likes to check they are working and the lcoal wild life haven't build new condos up there (Squirrels!).
The original code was  accessed via the home WiFi to the webserver on the board. From a browser you had to start the video stream. This new code is an AP 
and my friend just has to point his smart phone/tablet/PC to GutterCam2 and a browser browser to 192.168.4.1.  Much easier for him to use. There is also a single button to turn on/off the flash LED. 

The code was a modification of the code used in this project:


3D Printed SMart Steam Train with intergarted live view camera, water based steameffect and working lantern all controlled from
your mobile phone via WiFi with the ESP32.

Find out more at https://www.diymachines.co.uk 

Also many thanks go to :
Rui Santos ( https://RandomNerdTutorials.com/esp32-cam-projects-ebook/ )

Simone (https://eloquentarduino.com) 

for all their excellent tutorials and code examples.

I have also posted the 3d files I created to make the GutterCam2. The camera case is WIP, but does work. You just need to add or design a fixing
mechanism to attach  the GutterCam2 to a pole you might use. I used duct tape for the test! My friend has an elegant threaded attachment. See the Pole fix pictures in the image folder.

I also added a USB charger for the 18650 battery I used to power the it. Here's an example from Amazon:

https://www.amazon.com/HiLetgo-Lithium-Charging-Protection-Functions/dp/B07PKND8KG/ref=sr_1_4?crid=26L1JI3AIRO5G&dib=eyJ2IjoiMSJ9._qL6QZtDt3sucrXrLABF7_GGsjMfr4irGzi6uFnnGfJFeqio0uUiPAogrbM8MHuctjbjHJhhKvWgtgrEFV6fl3aVnK3Vjwpx-9VnYGnxW1DSw9dADh9InDDZqgp1rEScyb_yUYa2DYu45prRgCbGkfQQ6BEWWCIXQl6GcKAKqOUVH3e328FnNxMMGdAdX5c7qhH9D1eWcQrSR-dMkAAvBTExrWK3MH0BjlsBnLb7xa0.02JL7DArn6bR-tqz5FLYtrb0AILK6MhW2mDUoZ9aPsY&dib_tag=se&keywords=usb+lipo+charger+board&qid=1708818753&sprefix=usb+lipro+charger+baord%2Caps%2C164&sr=8-4


# Code

To train the AI nose, I recommend following this excellent tutorial by Shawn Hymel, he has the Python and Arduino scripts to collect, clean, and use the data to train the ML model. However, in Shawn's tutorial he uses several different sensors to train his model. If you're following this Instructable, you'll need to download the zip file included in this step as the python and .ino files are edited by me to handle the data obtained by one multi-channel sensor.

The "wio_terminal_artificial_nose_live_inference.ino" file is where you'll change how the Wio Terminal visualizes the classification. As you can see in lines 176, 182, 188 in Figure 1, I trained my model on creed, ambient, and eucalyptus smells. you'll need to change/add/remove those to whatever smells you used when training your classifier. You can also change what colors are visualized by changing the "TFT_COLOR" reference to whatever you want.

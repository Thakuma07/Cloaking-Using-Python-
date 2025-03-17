
# Invisible CLoak Effect Using NumPy and OpenCV

This code implements an "invisibility cloak" effect using OpenCV and NumPy. The idea is to make a specific colored object (like a blue cloak) disappear by replacing it with the captured background.


## Install Dependencies



To deploy this project run

```bash
  pip install opencv-python numpy
```

If you want OpenCV with extra functionalities (like GUI support), install:

```bash
  pip install opencv-python-headless numpy
```


## Connect a Webcam

Ensure that your webcam is working since the code captures video frames.
##  Run the Script

Open a terminal or command prompt in the folder where you saved main.py

Run the script using:

```bash
 python main.py
```

## Follow the On-Screen Instructions

Move out of the frame while the background is being captured.

Once the background is captured, wear a blue cloth (or any object of the specified color).

The blue part will disappear and show the captured background instead.
## Stop the Program

Press 'q' on your keyboard to exit.
## Possible Issues and Fixes

1.Issue: "Error: Could not open camera." 

1.Solution: Ensure your webcam is connected and not being used by another application.

2.Issue: "Error: Could not read frame."	

2.Solution: Restart the script and check your webcam connection.

3.Issue: The cloak is not disappearing properly	

3.Solution: Adjust the lower_blue and upper_blue values in the script to match the exact shade of blue you're using.



## Feedback

Let me know if you face any issues! 🚀


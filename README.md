# Cool-Real-Time-Videos

The goal for this project is to make a simple GUI that can add some widget on your faces and replace the background of the real-time video. 

Users can press ‘g’ on their keyboard to start or stop wearing sunglasses, press ‘r’ to start or stop replacing the background into beach, and press ‘q’ to quit.

The effect should look as if you are wearing sunglasses on a beach, although you are just sitting at home recording a video or having an online meeting! 

The sunglasses part is achieved through face landmark detecter. For the beach background part, first Canny Edge Detector is used to get the contours of the human body, then the mask based on the contours is smoothed, blurred and pasted into the new background.

For more details, please see report.pdf.

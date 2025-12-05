# invisible-cloak
 Invisible Cloak Project – OpenCV &amp; Python  This project is a real-time Invisibility Cloak effect created using OpenCV and NumPy. It detects a specific color in the video frame (Yellow in this version) and replaces that region with the previously captured background — generating the illusion of invisibility.
Features ->
Works in real-time using webcam
HSV color detection for accurate masking
Background capture for realistic cloak effect
Clean mask generation using morphological operations
Fully customizable color range

Tech Stack->
Python
OpenCV
NumPy
Webcam video capture
Image processing (HSV, masks, dilation, bitwise operations)
How It Work->
Capture background for a few seconds
Detect cloak color using HSV thresholds
Create binary mask
Replace masked area with background
Overlay the rest of the frame normally
Display final output with invisibility effect

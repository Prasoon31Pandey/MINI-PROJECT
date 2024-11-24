Virtual Mouse Using Hand Gesture

This Virtual Mouse project enables users to control their computer mouse using hand gestures detected via a webcam. Built using Python, OpenCV, and Mediapipe, it leverages advanced hand-tracking algorithms to provide a seamless and touch-free interface.

Features
Hand Tracking: Detects and tracks hand gestures in real-time.
Gesture Control:
Move Cursor: Move your hand to control the mouse pointer.
Click Actions: Perform left and right mouse clicks using predefined gestures.
Scroll Actions: Scroll pages up or down with gestures.
Customizability: Easy to configure gestures and actions.
Technology Stack
Programming Language: Python
Libraries:
OpenCV: For video processing.
Mediapipe: For hand detection and tracking.
PyAutoGUI: For simulating mouse actions.
How It Works
Hand Detection:

Uses Mediapipe's hand tracking model to detect hand landmarks in the webcam feed.
Gesture Recognition:

Maps hand gestures (e.g., specific finger positions) to mouse actions like movement, clicking, or scrolling.
Mouse Control:

Employs PyAutoGUI to simulate mouse actions based on the detected gestures.

# Hand Gesture-Based AWS EC2 Instance Launcher

This script leverages computer vision and AWS SDK (Boto3) to launch EC2 instances based on specific hand gestures detected through a webcam. It combines the power of **OpenCV**, **cvzone**, and **AWS** for a unique automation solution.

---

## Features

### Launch AWS EC2 Instances with Hand Gestures:
- **All Fingers Up**: Launches 5 EC2 instances.
- **Index Finger Up**: Launches 1 EC2 instance.
- **Index and Middle Fingers Up**: Launches 2 EC2 instances.
- **Other Gestures**: Prints "idk" for undefined gestures.

### Real-time Hand Gesture Recognition:
- Detects hand gestures using the webcam and the `cvzone.HandTrackingModule`.



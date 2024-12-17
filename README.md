***Face Detection & Intruder Notification System***

Overview
This project is a Face Detection System that identifies faces in images or live video feeds and sends real-time notifications if an intruder is detected. The system uses Pushbullet to send alerts to your mobile or desktop device, along with the intruder's picture for verification.

Features
Face Detection: Detects faces in images and live video streams.
Intruder Notification: Sends Pushbullet notifications with the image of the detected intruder.
Real-time Alerts: Instant notifications on your device when an intruder is detected.
Customizable Detection: Configurable detection sensitivity and detection source (image, video, or live webcam).

Technologies Used
Python
OpenCV (for face detection)
Pushbullet API (for sending notifications and images)
Haar Cascades or DNN Models (for face detection)

Sample Output
Face Detection: Bounding boxes around detected faces.
Pushbullet Notification: A real-time push notification on your mobile or desktop with the intruder’s image.

Future Improvements
Implement facial recognition to identify specific intruders.
Improve accuracy using deep learning models like MTCNN or DLIB.
Add support for multiple face detection in video feeds.
Integrate with other notification platforms like Twilio for SMS alerts.

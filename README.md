# edgeAI
Voice Command Recognition using Edge ML

Project Overview:
This project demonstrates a voice command recognition system built using Edge Impulse and deployed on the Arduino Nano 33 BLE Sense. The model is designed to recognize simple voice commands, including "Yes," "No," "Unknown," and background "Noise."

Features:
Model Training: The model was trained using hours of labeled audio data.
Model Labels: The categories recognized by the model are:
Yes
No
Unknown
Noise

Model Accuracy: The trained model achieved an accuracy of 91% on the test dataset.
Edge Deployment: The model was deployed on the Arduino Nano 33 BLE Sense for real-time voice command recognition at the edge.

Getting Started:
Prerequisites:
Arduino Nano 33 BLE Sense board.
Edge Impulse account and tools.
Arduino IDE installed on your system.
Hardware Setup
Connect the Arduino Nano 33 BLE Sense to your computer via USB.
Ensure the microphone on the Arduino board is functioning, as it will be used for capturing voice input.

Software Setup:
Train the Model on Edge Impulse:

Use Edge Impulse Studio to upload and label your audio data.
Train the model on the labeled data (Yes, No, Unknown, Noise).
After achieving satisfactory accuracy (91% in our case), download the Arduino Library from Edge Impulse.

Deploy the Model:

Install the downloaded Arduino library into the Arduino IDE.
Use the pre-built example code from the library to load the model onto the Arduino Nano 33 BLE Sense.
Upload the code to the board and begin real-time voice recognition.

Model Details:
Training Data: Hours of labeled audio data.
Model Accuracy: 91%.
Deployment: Model runs in real-time on the Arduino Nano 33 BLE Sense using its onboard microphone.

Future Improvements
Extend the model to recognize additional commands.
Enhance noise handling for better accuracy in noisy environments.
Optimize the model for even lower latency and faster response times.

Conclusion:
This project highlights the potential of Edge ML to bring powerful voice recognition capabilities directly to embedded devices, enabling offline and real-time operations. By leveraging the tools provided by Edge Impulse and the power of Arduino Nano 33 BLE Sense, we can build robust edge AI solutions for a wide variety of applications.

🥤 Bottle Detection App

Real-time bottle detection powered by TensorFlow Lite and SwiftUI.
The model runs entirely on-device, offering fast, offline, privacy-friendly inference.


🚀 Features
	•	⚡ Real-time detection using the iPhone camera
	•	🤖 Custom TensorFlow Lite model trained to detect water bottles
	•	🔒 100% on-device — no internet, no data sharing
	•	🧠 Uses MobileNetV2 feature extractor + custom classification head
	•	📱 Smooth integration with SwiftUI + AVFoundation
	•	🔄 Optimized preprocessing pipeline for accurate TFLite inference
	•	🛠 Easy to retrain and extend with your own dataset

🧪 Tech Stack
	•	TensorFlow / Keras (model training)
	•	TensorFlow Lite (inference)
	•	Swift / SwiftUI (UI + camera)
	•	AVFoundation (live camera frames)
	•	CoreVideo + Accelerate (fast pixel buffer processing)


📸 How It Works
	1.	The camera captures each frame
	2.	Frame is resized & normalized
	3.	Preprocessed tensor is passed to the TFLite model
	4.	Model outputs probability of “bottle present”
	5.	UI updates the detection label live


🧠 Model Training

The model was trained using:
	•	MobileNetV2 backbone
	•	Custom binary classifier head
	•	Image augmentation (flip, zoom, rotate)
	•	Preprocessing: (x / 127.5) - 1.0
	•	Exported using TFLiteConverter

# 🥤 Bottle Detection App

Real-time **water bottle detection** for iOS, powered by **TensorFlow Lite** and built with **SwiftUI**.  
The entire model runs **on-device** — fast, offline, and completely private.

https://github.com/user/BottleDetectionApp/assets/demo.gif

## 🚀 Features

- ⚡ Real-time detection using the iPhone camera
- 🤖 Custom TensorFlow Lite model trained specifically to detect water bottles
- 🔒 100% on-device inference — no internet required, no data ever leaves the device
- 🧠 MobileNetV2 feature extractor + lightweight custom classification head
- 📱 Native SwiftUI interface with smooth AVFoundation camera integration
- 🔄 Highly optimized preprocessing pipeline for maximum accuracy and speed
- 🛠 Easy to retrain or extend with your own dataset

## 📸 Demo

![Demo](assets/demo.gif)

## 🧪 Tech Stack

- **Model Training**: TensorFlow / Keras (Python)
- **Inference**: TensorFlow Lite
- **iOS Frontend**: Swift 5 + SwiftUI
- **Camera**: AVFoundation
- **Performance**: CoreVideo + Accelerate framework for fast pixel buffer processing
- **Dependency Management**: CocoaPods

## 🚀 Getting Started

### Prerequisites

- iOS 16.0+
- Xcode 15 or later
- CocoaPods (`sudo gem install cocoapods`)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/BottleDetectionApp.git
   cd BottleDetectionApp

2. Install dependencies via CocoaPods
   pod install

3. Open the .xcworkspace file (not the .xcodeproj)
4. Build and run on a real device (recommended for best camera + Neural Engine performance)

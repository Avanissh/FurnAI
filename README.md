# FurnAI
AI-Powered Virtual Home Renovation Assistant
This repository contains the codebase and assets for an AI-powered Furniture Recommendation System with Augmented Reality (AR) Integration. The system enables users to upload images of furniture or empty interior spaces and get visually similar furniture recommendations using a custom-trained CNN model based on VGG16 for feature extraction. Users can then visualize the recommended furniture in their actual environment using AR.
Features:
    Upload furniture or room images for analysis
    Content-based recommendation using deep learning (CNN + VGG16)
    Similar furniture suggestions based on visual features
    AR visualization via Unity and AR Foundation
    Seamless preview of furniture in real-time environment
    Cross-platform support for AR-capable devices

Technologies & Tools:
    Python – For AI model and backend logic
    TensorFlow/Keras – For training and deploying VGG16-based CNN
    OpenCV – Image processing and enhancement
    Unity + AR Foundation – AR user interface and visualization
    Meta Quest / ARKit / ARCore – For immersive deployment
    (Optional) YOLOv11 – Object detection and spatial placement

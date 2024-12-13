
Background Information
Tomatoes are one of the most important agricultural products worldwide, and maintaining their freshness while preventing spoilage is crucial. However, it can be challenging to accurately determine the state of a tomato with the naked eye. Incorrect judgments can lead to unnecessary waste or food safety issues. This is where technology can play a vital role. Using AI-powered video analysis, we can quickly and accurately detect whether a tomato is fresh or spoiled. This contributes significantly to improving productivity and quality in agriculture and the food industry.

General Description of the Project
This project leverages the YOLOv7-tiny model to develop a system that automatically detects whether a tomato is fresh or spoiled. YOLOv7-tiny, a lightweight version of YOLOv7, is highly efficient even in resource-constrained environments. The system is designed to operate on various platforms, such as smartphones and farm cameras, providing fast, real-time assessments of tomato conditions.

Proposed Ideas for Improving the Project
Enhancing Performance in Diverse Environments

Expand the training dataset to include diverse lighting conditions (e.g., bright outdoor, dim indoor) and backgrounds.
Improve the model by incorporating various tomato varieties and sizes in the dataset.
Detailed State Detection

Go beyond simple "fresh/at risk/rotten" detection to include classifications such as "partially spoiled" or "fully spoiled."
IoT Integration

Integrate with agricultural IoT sensors to analyze environmental conditions (temperature, humidity) alongside spoilage states.
Add smartphone notification features for remote monitoring of data.
Value and Importance of the Project
Reducing Food Waste: By selectively discarding only non-fresh tomatoes, unnecessary waste can be minimized.
Improving Agricultural Efficiency: Farmers can easily monitor the state of their tomatoes and ensure freshness.
Enhancing Quality of Life: Providing consumers with safe and fresh produce helps address food safety concerns.
Current Limitations
Limited Data

The current dataset is restricted to specific environments and tomato varieties, making it difficult to generalize the system.
Accuracy Constraints of YOLOv7-tiny

While YOLOv7-tiny is fast and lightweight, additional optimization and enhancements are needed to achieve higher accuracy.
Hardware Dependency

Technical challenges remain in ensuring reliable performance on low-spec devices.
Literature Review
Comparison of YOLOv7 and YOLOv7-tiny

Studies indicate that YOLOv7-tiny, while suitable for lightweight applications, has slightly reduced accuracy compared to the full YOLOv7 model.
Applications of Object Detection in Agricultural Quality Assessment

YOLO models have been widely used for assessing the size and quality of agricultural products, supporting the applicability of this project.
Spoilage Detection Algorithms

Research on algorithms for detecting spoilage features (e.g., color changes, surface damage) can contribute to improving the data processing methods of this project.
This project goes beyond solving a technical challenge to enhance the sustainability of agriculture and the food industry, offering significant social value. By further improving the system's accuracy and efficiency, it has the potential to become an essential tool for quality management in agricultural products.

The source of the images used for detection is Rotating Tomatoes images on the YouTube Temponaut Timelapse channel.
https://youtu.be/N23i12IbyAs?si=5bC52h0ro_E2059X

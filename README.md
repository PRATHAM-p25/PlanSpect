# PlanSpect

## Overview

PlanSpect is designed to detect and label architectural elements in floor plans using the YOLOv8 model. Trained to recognize key components like walls, columns, doors, and windows, the system processes input floor plan images and accurately identifies these structural elements.

## Technology Stack

* **YOLOv8:** Backbone architecture for object detection, enabling precise recognition of floor plan elements.

* **PyTorch:** Deep learning framework used for training and inference.

* **YAML:** Configures dataset organization and model parameters.

* **torchvision:** Handles image transformations and dataset preprocessing.

* **Streamlit:** Powers the web-based user interface for seamless interaction.

## Use Cases

* **Architectural Design:** Enables architects and designers to automatically analyze floor plans, identifying key elements for enhanced design efficiency.

* **Construction Planning:** Assists construction firms in automating floor plan analysis, optimizing resource allocation and project execution.

* **Real Estate:** Helps real estate agencies quickly assess and classify properties based on structural features, improving property management and sales processes.

## Benefits

* **Efficiency:** Automates object detection, significantly reducing manual effort and time spent analyzing floor plans.

* **Accuracy:** Leverages the YOLOv8 model to ensure precise detection and classification of architectural elements.

* **Scalability:** The system is designed to scale effortlessly, accommodating large datasets and enabling real-time floor plan image processing.

## Dependencies
* Streamlit
* Pillow
* Ultralytics

## Acknowledgements
* YOLOv8: [Ultralytics YOLO](https://github.com/ultralytics/yolov5)
* Streamlit: [Streamlit Documentation](https://docs.streamlit.io/)
* PIL: [Pillow Documentation](https://pillow.readthedocs.io/en/stable/)

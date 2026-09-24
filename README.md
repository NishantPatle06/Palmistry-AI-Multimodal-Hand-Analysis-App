# Palmistry-AI-Multimodal-Hand-Analysis-App

## About the Project
This is a multimodal GenAI application that interprets palm images, enabling **100% offline predictions** with real-time results under **2s latency**. 

### Key Features & Technologies
- **Computer Vision (YOLOv8)**: Integrated YOLOv8 CV to detect palm lines (head, heart, life) with **95%+ detection accuracy** on 1K+ test images. (The YOLO model is sourced from Roboflow: https://universe.roboflow.com/palmistry-2klz8/palmistry-g45zz)
- **Generative AI (RAG + LLaMA-2)**: Created a **5K+ knowledge base** from ancient Indian scriptures (Samudrik Shastra) and applied **RAG pipelines** for semantic retrieval.
- **End-to-End Pipeline**: The application processes palm images using YOLOv8, converts the detected features into a structured JSON format, and feeds them into the LLaMA-2 model to provide personalized interpretations based on the retrieved palmistry knowledge base.

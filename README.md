# Palmistry-AI-Multimodal-Hand-Analysis-App

## About the Project
This project is an AI-powered, multimodal application designed to perform traditional Indian palmistry analysis (Samudrik Shastra) using computer vision and large language models (LLMs).

It uses a two-step pipeline:
1. **Computer Vision (YOLOv8)**: Extracts key features (lines, mounts, shapes) from images of human palms using a fine-tuned object detection model.
2. **Generative AI (RAG + LLM)**: The extracted features are converted into a structured JSON format and fed into an LLM. Using Retrieval-Augmented Generation (RAG) over traditional Indian palmistry texts, the LLM provides personalized interpretations and readings.

The YOLO Model is taken from Roboflow which is https://universe.roboflow.com/palmistry-2klz8/palmistry-g45zz 
The model takes the images through this model and converts the data into json format which is fed into LLM model for its interpretation via traditional Indian palmistry text ( via RAG )

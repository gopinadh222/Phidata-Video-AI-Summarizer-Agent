# Phidata Video AI Summarizer Agent

## Overview:

The **Phidata Video AI Summarizer Agent** is a powerful Streamlit-based web application designed to facilitate video analysis using advanced multimodal AI models. This tool allows users to upload video files and receive actionable insights extracted from the content, combining visual analysis with natural language processing.

## Features:

- **Multimodal AI Integration**: Leverages the **Gemini 2.0 Flash Exp** model to perform advanced video analysis.
- **Video File Upload**: Users can upload video files in supported formats (`.mp4`, `.mov`, `.avi`) for processing.
- **Real-time Video Processing**: Processes uploaded videos in real-time and extracts insights.
- **Interactive Query System**: Allows users to input specific queries to gain context, analyze content, and obtain actionable responses.
- **Results Display**: Insights are displayed in a user-friendly format, making the results easy to understand and actionable.
- **Customizable Interface**: The application includes CSS customization to adjust video display dimensions and text areas for a more personalized user experience.
- **Error Handling**: The system provides appropriate feedback and error messages to ensure a seamless user experience.

## Technologies Used:

- **Streamlit**: For creating interactive web applications and embedding multimedia elements.
- **Phi-Agent**: Integrates advanced multimodal AI capabilities for video analysis.
- **Gemini 2.0 Flash Exp**: A cutting-edge generative AI model used for text and video content understanding.
- **DuckDuckGo**: Built-in tool for accessing supplementary web research if needed.
- **Tempfile**: Handles temporary file storage during video processing.
- **Google Generative AI**: Used for video uploads and processing.
- **Python**: Core scripting language, combined with Streamlit’s interactive components.
- **CSS**: Customization for styling the interface, especially for video dimensions and layout.

## Installation:

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Jayanth-sanku/Phidata-Video-AI-Summarizer-Agent.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   ```bash
    streamlit run app.py
   ```

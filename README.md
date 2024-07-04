# Personal-Image-Analysis-with-Google-Gemini-AI-LLM-and-Streamlit

## Harsha's Personal Google Gemini AI Image App

## Project Description

This project is an innovative web application built using Streamlit that integrates with Google Gemini AI to provide image analysis and description generation. Users can upload an image and optionally provide a text prompt. The AI model processes the input and generates detailed content about the image. The application showcases the seamless integration of cutting-edge AI technology with a user-friendly interface.

## Features

- **Image Upload**: Upload images in various formats (jpg, jpeg, png) for analysis.
- **Text Prompt**: Optionally provide a text prompt to get more specific responses.
- **AI-Powered Analysis**: Utilizes Google Gemini AI for generating descriptive content about the image.
- **Interactive Interface**: Built with Streamlit, ensuring an intuitive and responsive user experience.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.7+
- pip (Python package installer)

### Steps

1. **Clone the repository**:

   ```sh
   git clone https://github.com/yourusername/image-creation-google-gemini.git
   cd image-creation-google-gemini
   ```

2. **Install required libraries**:

   ```sh
   pip install streamlit google-generativeai pillow
   ```

3. **Set up Google Gemini API key**:

   - Obtain your API key from Google Gemini.
   - Set the API key as an environment variable:

     ```sh
     export GEMINI_API_KEY='your_api_key'
     ```

## Usage

1. **Run the Streamlit app**:

   ```sh
   streamlit run app.py
   ```

2. **Interact with the app**:

   - Open your web browser and go to `http://localhost:8501`.
   - You will see the app's interface with options to upload an image and enter a text prompt.
   - After uploading an image and optionally providing a text prompt, click the "Explain me about the image" button to get the AI-generated response.

## Project Structure

- `app.py`: The main script to run the Streamlit application.
- `README.md`: This readme file.

## Code Explanation

### Libraries and Modules

- **Streamlit**: Used for building the web application interface.
- **Google Generative AI**: Provides the AI model for image content generation.
- **Pillow**: Used for image processing.

### Functionality

1. **Environment Setup**:
   - Set the Google Gemini API key as an environment variable.

2. **Initialize Streamlit App**:
   - Configure the page title and header.

3. **Input and Image Upload**:
   - Text input for the prompt and file uploader for images.

4. **Get AI Response**:
   - The `get_gemini_response` function sends the input and image to the AI model and retrieves the generated content.

5. **Display Results**:
   - Display the uploaded image and the AI-generated content in the Streamlit app.

## Future Enhancements

- **Image Editing**: Add functionality for basic image editing before analysis.
- **Advanced Options**: Provide advanced options for more detailed or specific AI-generated content.
- **User Authentication**: Implement user authentication for personalized experiences.

## Credits

- **Google Gemini AI**: For the powerful AI models used in this project.
- **Streamlit**: For the easy-to-use web application framework.
- **Pillow**: For image processing capabilities.

## Contact

For any queries or contributions, please reach out to Harsha at [challaharsha214@gmail.com].

---

Feel free to customize this readme file further based on your specific requirements and preferences.

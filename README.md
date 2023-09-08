## YouTube Video to Recipe Generator

![Portfolio Screenshot](https://github.com/MeghanaNalla/My-Portfolio/blob/main/src/Assets/Projects/recipeGenerator.png)

## Description

The YouTube Video to Recipe Generator is a versatile application that streamlines the process of transforming YouTube cooking videos into easily readable and printable recipes. With the integration of powerful technologies, this tool extracts video and audio content from a YouTube video URL, processes the audio to generate a transcript, and then utilizes OpenAI's text-davinci-003 model to create a detailed recipe.

## Technology Stack

- Streamlit: The user-friendly interface is built using Streamlit, making it accessible and intuitive for users to interact with the application.

- PyTube: PyTube is employed to extract video and audio content from the provided YouTube video URL. It allows seamless handling of YouTube videos.

- OpenAI's text-davinci-003 Model: This advanced AI model is utilized to generate detailed recipes based on the extracted video content and audio transcripts.

- OpenAI Whisper-1: The Whisper-1 model is used to process the audio file and obtain an accurate transcript, which forms the basis for generating the recipe.

## How It Works

- Video Extraction: The application takes a YouTube video URL as input and uses PyTube to extract both video and audio components from the URL.

- Transcription: The audio file extracted is processed through OpenAI's Whisper-1 model to obtain a highly accurate transcript of the spoken content in the video.

- Recipe Generation: Leveraging the obtained transcript, the text-davinci-003 model from OpenAI generates a detailed recipe. This includes ingredient lists, preparation steps and cooking instructions.

## Usage

- Enter a YouTube video URL of a cooking tutorial or recipe demonstration.

- Click the "Generate Recipe" button.

- The application will extract the video and audio, transcribe the audio, and present you with a complete recipe based on the video content.

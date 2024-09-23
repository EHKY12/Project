# Emotion-based Text and Image Generation using Gemma Model and Stable Diffusion

## This project aims to analyze emotions from a user's input text and generate images that match those emotions using the Gemma model and Stable Diffusion. The goal is to provide visual feedback that corresponds to the user's emotional state

Features
Emotion Analysis: Uses the Gemma 2 model to extract emotions from text.
Image Generation: Generates images with Stable Diffusion based on the extracted emotions.
User Interaction: Takes user input in the form of a sentence describing their current emotional state.
Multi-GPU Support: Allows the selection of specific GPU(s) for model training and inference.


## Installation
To run this project, you need to set up the required dependencies.

### git clone https://github.com/your-username/emotion-image-generation.git
### cd emotion-image-generation

Create a virtual environment and activate it:

### python3 -m venv venv
### source venv/bin/activate  # On Windows: venv\Scripts\activate

Run the training script (if you want to fine-tune the Gemma 2 model): 
### python second.py ## this one is training python file :)

Run the inference script to generate images based on user input
### python third.py ## this one is generating image python file 

## Example 
"I feel a bit stressed after a long day at work."

## Results
The generated images are saved in the working directory. After running the image generation script, you will find the output images saved as sd_generated_image.png.  

## License
This project is licensed under the MIT License.

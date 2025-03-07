# Stable Diffusion Image Generation with Hugging Face API

This project demonstrates how to use the Hugging Face API to generate images using the **Stable Diffusion XL Base 1.0** model. It generates images based on a text prompt and saves them to a local directory.


#Table of Contents:
1. [Setup Instructions](#setup-instructions)
2. [Approach](#approach)
3. [Challenges and Assumptions](#challenges-and-assumptions)
4. [Generated Images](#generated-images)
5. [Showcase Generated Images](#showcase-generated-images)


## Setup Instructions

1. Install the `requests` library:
   pip install requests
   
2. Sign up for a Hugging Face account at [huggingface.co](https://huggingface.co/) and generate an API token.
3. Replace the `API_TOKEN` variable in the script with your Hugging Face API token.


## Approach

- The script uses the Hugging Face API to interact with the Stable Diffusion XL Base 1.0 model.
- A text prompt is sent to the API, and the model generates an image based on the prompt.
- The script generates 3 images and saves them in the `generated_images` directory.
- Error handling ensures the script handles API failures gracefully.


# Challenges and Assumptions

### Challenges
- API Rate Limits: Free-tier Hugging Face API usage may have rate limits.
- Image Quality: The quality of generated images depends on the prompt and the model's capabilities.

### Assumptions
- The Hugging Face API token is valid and has access to the Stable Diffusion XL Base 1.0 model.
- The prompt provided is descriptive enough to generate meaningful images.


# Generated Images

- The script generates 3 images based on the provided prompt.
- Images are saved in the `generated_images` directory with filenames like `serene_sunset_futuristic_city_1.png`.

# Showcase Generated Images
![image](https://github.com/user-attachments/assets/e7a89522-6f7d-442e-97ef-ea093ca75e8e)


# Food Identification and Nutrition Info

This project uses a Vision Transformer (ViT) model to identify food items from images and provides nutritional information using the API NINJAS service.

Deployed Link: https://huggingface.co/spaces/Npps/Food_Indentification_and_Nutrition_Info

## Features

- **Food Identification:** Utilizes the Vision Transformer (ViT) model from the `transformers` library to classify food items from images.
- **Nutritional Information:** Fetches and formats nutritional data, including calories, fat, protein, and more, using API NINJAS.
- **Real-Time Interface:** Provides a user-friendly interface for real-time food classification and nutritional insights with Gradio.

## Tech Stack

- **Python**
- **Transformers**
- **Gradio**
- **PIL (Python Imaging Library)**
- **Requests**

## How It Works

1. **Food Identification:** Upload an image, and the model classifies the food item using ViT.
2. **Nutritional Data:** Retrieves nutritional information from API NINJAS and formats it into an HTML table.
3. **Interface:** Deploys the solution using Gradio, allowing users to interact with the model and view results in real time.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Npps1997/FOOD-IDENTIFICATION-AND-NUTRITION-INFO-USING-GENAI.git

2. Navigate to the project directory:
   ```bash
   cd FOOD-IDENTIFICATION-AND-NUTRITION-INFO-USING-GENAI

3. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Usage
Run the application:
- app.py

Visit the provided local URL in your browser to upload images and view nutritional information.

## API Key
You will need an API key for API NINJAS. Replace the placeholder in the app.py file with your own API key.

## Requirements
- Python 3.7+
- Gradio
- Transformers
- PIL
- Requests

## License
This project is licensed under the MIT License.

Feel free to adjust any specifics if needed!

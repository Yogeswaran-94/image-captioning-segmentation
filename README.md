## Image Captioning and Segmentation App
A Streamlit-based web application that performs Image Captioning and Segmentation using Hugging Face Transformers and PyTorch.

## Author
Yogeswaran S
(yogeswaran00794@gmail.com)

## Features
📷 Upload an image and get an AI-generated caption.
🎨 Perform segmentation to highlight objects within the image.
🧠 Powered by Hugging Face pre-trained models.
⚡ Built with Streamlit for a simple and interactive UI.

📂 Project Structure
image-captioning-and-segmentation/
│── imagecaption.py                # Streamlit app entry point
│── requirements.txt       # Dependencies
│── utils/                 # Helper functions (optional)
│── outputs/               # Generated captions & segmented images
│── data/                  # Sample test images

## Installation
1️⃣ Clone the Repository
git clone https://github.com/Yogeswaran-94/Image-captioning-and-segmentation.git
cd image-captioning-and-segmentation

2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate     

3️⃣ Install Dependencies
pip install -r requirements.txt

▶️ Run the Application
streamlit run main.py

## Requirements
Main libraries used:
streamlit
torch
transformers
Pillow
numpy

🖼️ Example Output
Input Image:

Generated Caption:
"A cat sitting on a sofa."

Segmentation Output:
(Objects in the image highlighted with masks.)

## License
This project is licensed under the MIT License – feel free to use and modify.
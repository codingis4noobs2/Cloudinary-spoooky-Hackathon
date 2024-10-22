# Spooky Pet Image App

**Spooky Pet Image App** is a fun platform that transforms ordinary pet images into spooky, Halloween-themed creations. Whether you're looking to give your cat a spooky makeover or place any pet in a chilling Halloween setting, this app has everything you need for a spooky transformation!

## Features

- **Spooky Pet Background Generator**: Upload any pet image and replace the background with a foggy, eerie Halloween scene featuring twisted trees, pumpkins, a haunted house, and more.
- **Spooky Cat Face Transformer**: Specifically for cats, this feature transforms your cat into a spooky, demonic version with glowing red eyes, sharp fangs, bat wings, and dark mist.

## Installation

### Prerequisites

- Python 3.8 or later
- Cloudinary account
- `pip` (Python package installer)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/codingis4noobs2/Cloudinary-spoooky-Hackathon
   cd spooky-pet-image-app
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Cloudinary credentials**:
   - Inside the root directory of the project, rename `.env.example` to `.env`.
   - Open the `.env` file and fill in your Cloudinary credentials:
     ```
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     ```

4. **Run the app**:
   ```bash
   streamlit run app.py
   ```

5. **Open the app**:
   After running the command, the app should automatically open in your browser. If not, open the browser and go to:
   ```
   http://localhost:8501
   ```

## Usage

- On the homepage, learn more about the app’s features.
- Use the **Spooky Pet Background Generator** to add a spooky Halloween background to your pet images.
- Use the **Spooky Cat Face Transformer** to transform your cat’s face into a spooky, demonic creature.

## Technologies Used

- **Streamlit**: For building the interactive web application.
- **Cloudinary Python SDK**: For image processing and generative AI transformations.
- **Python**: The core programming language used.

---

### Notes

- Ensure that your image files are no larger than 5 MB.
- You can modify the transformation prompts for both the background and the cat face transformer to customize the spooky effects.

Enjoy transforming your pets for Halloween!

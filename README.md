# AI Image Generation with ComfyUI and FastAPI

Generate AI images from text prompts using ComfyUI, served through a web interface powered by FastAPI and made accessible via ngrok.

## 🌟 Features

- **Text-to-Image Generation**: Convert text descriptions into images using the FLUX model
- **Web API**: Easy-to-use REST API built with FastAPI
- **Public Access**: Expose your local instance to the internet using ngrok
- **Customizable**: Adjust generation parameters like steps, CFG, and sampling method
- **Negative Prompts**: Support for negative prompts to refine generation results

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- ComfyUI installed with FLUX model
- ngrok account (free tier works fine)



The application will print a public URL that you can use to access the API.

## 📝 API Usage

### Generate an Image

**Endpoint:** `POST /generate`


## 📋 Dependencies

- FastAPI
- uvicorn
- pyngrok
- Pillow
- requests
- python-dotenv




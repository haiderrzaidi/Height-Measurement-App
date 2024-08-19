# Measure Heights from Images with Our AI-Powered App!

Have you ever wondered how tall something is in a picture? Whether it's a mountain, a building, or any object, our app makes it simple to find out! Using cutting-edge AI technology, we've created a tool that measures the height of objects in images with incredible accuracy.

## Why This App?
Imagine being able to upload any image and get instant height measurements without the need for fancy equipment. Whether you're a photographer, architect, or just curious, this app is designed to be both fun and practical.

### What Can You Do?
- **Accurate Height Estimation**: Our app leverages advanced depth estimation models to calculate the height of objects in meters.
- **User-Friendly Interface**: With an intuitive design, measuring heights is as easy as a few clicks.
- **Quick Results**: Get instant feedback, no waiting around.

## How It Works
1. **Upload Your Image**: Simply drag and drop or select an image from your device.
2. **Mark the Object**: Draw a bounding box around the object whose height you want to measure.
3. **Get the Height**: The app will calculate and display the height in meters.

## Quick Start Guide

### Prerequisites
- Python 3.8+ is required to run the app.
- Install the necessary libraries:
  ```bash
  pip install -r requirements.txt
  ```

### Running the App
To launch the app, run the following command:
```bash
python app/main.py
```
This will open up the Gradio interface in your browser, where you can start measuring heights right away!

## Technical Details
For those interested in the nitty-gritty:
- The app uses depth estimation models like ZoeDepth to analyze the image and estimate the distance between different points.
- The height is then calculated based on the pixel measurements and depth information.
- The app is built using Gradio, a Python library that creates easy-to-use web interfaces.

## Repository Structure

- `app/`: Contains the main code for the Gradio app.
- `data/`: Sample images you can use to test the app.
- `models/`: Pretrained models for depth estimation.
- `utils/`: Helper scripts for processing images.
- `tests/`: Unit tests to ensure everything works as expected.

## Ready to Measure?

Dive into the world of AI-powered measurements and discover how easy it is to calculate heights from any image. Whether for work or play, this app has you covered!


# Bilateral Filter for Image Smoothing

This project implements a **bilateral filter** for image smoothing using JavaScript. The bilateral filter preserves edges while reducing noise, making it ideal for tasks like photo editing and preprocessing.

## Live Demo
- https://muhammedshahid.github.io/bilateral-filter/

## Key Features
- **Image Upload**: Users can upload their own images for processing.
- **Interactive Parameters**: Adjust `sigmaSpace` and `sigmaColor` parameters to fine-tune the smoothing effect.
  - **sigmaSpace**: Controls the influence of spatial distance on smoothing.
  - **sigmaColor**: Determines how much the color difference affects the smoothing.
- **Real-time Preview**: Observe the effects of parameter changes instantly.

## How It Works
1. **Input**: Users upload an image.
2. **Parameter Adjustment**: Users modify the `sigmaSpace` and `sigmaColor` sliders to customize the smoothing.
3. **Output**: The smoothed image is displayed for comparison with the original.
4. **Note**: For faster implementation, used `.width` & `.height` in function `drawImgOnCanvas`  

## Technologies Used
- **JavaScript**: For implementing the bilateral filter algorithm.
- **Canvas API**: For rendering and processing the image data.

## How to Use
- Clone the repository:
   ```bash
   git clone https://github.com/muhammedshahid/bilateral-filter.git
- Open index.html in a browser.
- Upload an image using the upload button.
- Adjust the sigmaSpace and sigmaColor sliders to see the effect on the image.
## Future Improvements
- Add support for real-time webcam processing.
- Enable downloading of the smoothed image.
- Extend to other filters for comparison (e.g., Gaussian, median filters).
## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

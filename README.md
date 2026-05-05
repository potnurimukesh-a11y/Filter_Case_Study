Filter Case Study (Image Processing in Python)

📌 Overview

This project is a case study focused on applying color filters to images using Python.
It demonstrates how pixel-level manipulation can be used to transform the visual appearance of an image.

The program modifies RGB values of each pixel to create a stylized filter effect.

---

🎯 Objectives

- To understand image processing using Python
- To apply color transformations using RGB channels
- To explore pixel-level manipulation
- To enhance images using custom filter logic

---

⚙️ Features

- Loads an image file
- Applies a custom color filter
- Adjusts RGB intensity values:
  - Increases red and blue channels
  - Reduces green channel
- Displays original and filtered images

---

🛠️ Technologies Used

- Python
- Pillow (PIL)
- Custom "SimpleImage" library

---

🧠 Concepts Applied

- RGB color model
- Pixel manipulation
- Image transformation
- Iteration over image pixels
- Arithmetic operations on color channels

---

📂 Project Structure

Filter_Case_Study/
│
├── Gitam-Python.py     # Main program (filter logic)
├── simpleimage.py      # Image handling utility
├── gate.jpg            # Sample input image
├── README.md

---

▶️ How It Works

- The image is loaded using "SimpleImage"
- Each pixel is accessed using a loop
- RGB values are modified:
  - Red = Red × 1.5
  - Green = Green × 0.7
  - Blue = Blue × 1.5
- The transformed image is displayed

---

▶️ How to Run

1. Install required library:

pip install pillow

2. Run the program:

python Gitam-Python.py

---

📷 Output

- Displays the original image
- Displays the filtered image with enhanced color tones

---

📚 Example Effect

- Image appears more vibrant
- Warmer tone due to increased red and blue
- Reduced green creates a stylized color balance

---

📚 Conclusion

This project demonstrates how simple mathematical operations on pixel values can significantly change the visual appearance of an image. It highlights the power of image processing using basic programming concepts.

---

👨‍🏫 Acknowledgement

This case study was developed based on concepts and guidance provided during classroom sessions by the instructor.

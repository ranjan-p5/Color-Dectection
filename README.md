# Color-Dectection
This project is an interactive Computer Vision application that identifies colors in images or real-time video feeds. By utilizing OpenCV for image processing and Pandas for data handling, the application calculates the RGB values of a specific pixel and maps them to the nearest color name from a dataset of over 800 colors.
# Color Detection Project 🎨

This project is a Python-based application that detects the names of colors within an image. It uses a CSV-based dataset of color names and their corresponding RGB values to find the closest match to the pixel you select.

## 🚀 How it Works
1. The user **double-clicks** on any point in the image.
2. The application extracts the **RGB** values of that specific pixel.
3. It calculates the "distance" between the selected color and all colors in the dataset using the formula:
   $$d = |R - R_i| + |G - G_i| + |B - B_i|$$
4. The color with the minimum distance is displayed as the result.

## 🛠️ Built With
* **Python** - Core language
* **OpenCV** - Image processing and GUI
* **Pandas** - Data manipulation (loading the color dataset)

 

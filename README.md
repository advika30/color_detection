# COLOUR ECOGNITION ASSISTANCE
This Python script utilizes the OpenCV library to detect the color of any pixel in an image. It provides a graphical interface where users can double-click on a pixel, and the script will display the name of the detected color along with its RGB values. Additionally, it draws a colored rectangle on the image to visually represent the detected color.

## Key Features:
Interactive Interface: Users can interact with the image by double-clicking on any pixel to detect its color.
Color Name Recognition: The script matches the RGB values of the selected pixel with predefined colors stored in a CSV file to determine the closest color name.
RGB Values Display: Along with the color name, the script displays the RGB values of the detected color.
Visual Representation: A colored rectangle is drawn on the image to visually represent the detected color.


## How it Works:
The script loads an image file and waits for user interaction.
When a user double-clicks on a pixel, the script captures the RGB values of that pixel.
It then compares these RGB values with those stored in a CSV file containing color names and corresponding RGB values.
The script determines the closest color match and displays the color name, along with the RGB values, on the image.
If the total RGB value of the detected color is high (indicating a light color), the text is displayed in black for better visibility.
Users can continue to interact with the image until they exit the program.


## Potential Use Cases:
Graphic Design: Quickly identify colors from images for graphic design projects.
Web Development: Determine the color palette of images for web design.
Education: Understand color theory by visually exploring colors in images.
Computer Vision Research: Utilize color detection as a component in more complex computer vision systems.


## Requirements:
Python 3.x
OpenCV library (opencv-python)
Pandas library (pandas)


## License:
This project is licensed under the MIT License. See the LICENSE file for details.

Contributions:
Contributions, suggestions, and improvements are welcome! Feel free to open an issue or create a pull request on GitHub.


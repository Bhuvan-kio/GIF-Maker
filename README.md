# 🖼️ PNG Sequence to GIF Converter

A simple Python script to create an animated GIF from a sequence of PNG images. This tool ensures that images named numerically (e.g., `frame1.png`, `frame2.png`, `frame10.png`) are sorted correctly for a smooth animation.

---
## 🚀 Demo

![GIF Maker Demo](https://raw.githubusercontent.com/Bhuvan-kio/GIF-Maker/refs/heads/main/Output.gif)

---
## ✨ Features


-   **Converts PNG Images**: Reads all `.png` files from a specified folder.
-   **Natural Sorting**: Correctly sorts frames to ensure proper animation sequence.
-   **Custom FPS**: Easily configure the frames per second (FPS) for the output GIF.
-   **Looping**: Creates an infinitely looping GIF by default.

---

## 🛠️ Prerequisites

Before you run the script, make sure you have Python 3 and the necessary libraries installed.

1.  **Python 3**: [Download Python](https://www.python.org/downloads/)
2.  **Required Libraries**: Install `imageio` and `natsort` using pip. The `imageio[ffmpeg]` extra is recommended for broader file support.
    ```bash
    pip install imageio natsort imageio[ffmpeg]
    ```

---

## 🚀 How to Use

1.  **Add Images**: Place all your `.png` image files into a single directory.

2.  **Configure the Script**: Open the Python script and modify the configuration variables at the top of the file to match your setup.

    ```python
    # --- Configuration ---
    # Set the path to the directory containing the source PNG images.
    img_dir = "D:\\path\\to\\your\\images"

    # Set the path and filename for the final output GIF.
    output = "D:\\path\\to\\save\\your_animation.gif"

    # Set the desired frames per second (FPS) for the animation.
    fps = 10
    # ---------------------
    ```

3.  **Run the Script**: Execute the script from your terminal.

    ```bash
    python your_script_name.py
    ```

The script will find the images, create the GIF, and save it to your specified output path.

---
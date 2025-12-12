# Image Converter (PNG to PDF)

A lightweight and simple Graphical User Interface (GUI) application built with Python that allows users to easily convert PNG images into PDF format. This tool utilizes the `tkinter` library for the interface and `Pillow` (PIL) for image processing.

## 📋 Features

* **Simple GUI:** Clean and easy-to-use interface.
* **File Selection:** Browse and select PNG files from your local directory.
* **Conversion:** One-click conversion from PNG to PDF.
* **Save Dialog:** Choose where to save the specific output PDF file.

## 🛠️ Built With

* [Python](https://www.python.org/) - The programming language used.
* [Tkinter](https://docs.python.org/3/library/tkinter.html) - Standard Python interface to the Tk GUI toolkit.
* [Pillow (PIL)](https://python-pillow.org/) - The friendly Python Image Library.

## ⚙️ Prerequisites

Before you begin, ensure you have Python installed on your system. You will also need to install the `Pillow` library, as `tkinter` is included with standard Python installations.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/image-converter.git](https://github.com/your-username/image-converter.git)
    cd image-converter
    ```

2.  **Install the required package:**
    ```bash
    pip install Pillow
    ```

## 🚀 Usage

1.  Run the Python script:
    ```bash
    python main.py
    ```
    *(Note: Replace `main.py` with the actual name of your python file)*

2.  A window titled **Image Converter** will appear.

3.  Click the **"Select PNG file"** button to browse and open the image you want to convert.

4.  Click the **"Convert PNG to PDF"** button. A save dialog will open; enter your desired filename and click save.

## 📄 Code Structure

The application consists of a single script that handles:
* **UI Layout:** Canvas, Labels, and Buttons using Tkinter.
* **Event Handling:** Functions to handle file imports (`getPNG`) and conversion/saving (`convert`).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/image-converter/issues).

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

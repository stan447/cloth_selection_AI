# Fashion Cloth Classification AI

This repository contains a Jupyter Notebook demonstrating an image classification task using the Fashion MNIST dataset. The goal is to build and train an AI model capable of identifying different articles of clothing from images.

## Project Description

The project uses the **Fashion MNIST** dataset, a collection of 70,000 grayscale images of 10 categories of clothing items (like t-shirts, trousers, dresses, coats, sandals, sneakers, etc.). The notebook (`fashion_cloth_AI.ipynb`) walks through the process of:

* Loading and exploring the dataset.
* Preprocessing the image data.
* Building a neural network model using **TensorFlow** and **Keras**.
* Training the model on the dataset.
* Evaluating the model's performance.
* Making predictions on new images.

This project serves as a basic example of applying deep learning techniques to image classification problems.

## Getting Started

To run this project locally, follow these steps:

1.  **Clone the repository:**
    If you haven't cloned it already (you already have the files locally, but for someone else cloning):
    ```bash
    git clone git@github.com:stan447/cloth_selection_AI.git
    # OR if using HTTPS
    # git clone [https://github.com/stan447/cloth_selection_AI.git](https://github.com/stan447/cloth_selection_AI.git)
    ```
    Navigate into the cloned directory:
    ```bash
    cd cloth_selection_AI
    ```

2.  **Set up a Python environment:**
    It's recommended to use a virtual environment.
    ```bash
    # Create a virtual environment (example using venv)
    python -m venv venv
    # Activate the environment
    # On Windows:
    # .\venv\Scripts\activate
    # On macOS/Linux:
    # source venv/bin/activate
    ```

3.  **Install dependencies:**
    You will need TensorFlow, NumPy, Matplotlib, and Jupyter. You can install them using pip:
    ```bash
    pip install tensorflow numpy matplotlib jupyter
    ```
    *(Note: The notebook might have an initial cell `!pip install tensorflow numpy matplotlib`. Running this within the notebook can also install them, but installing them in your environment beforehand is generally cleaner).*

4.  **Run the Jupyter Notebook:**
    Start the Jupyter Notebook server in the project directory:
    ```bash
    jupyter notebook
    ```
    This will open a tab in your web browser. Click on `fashion_cloth_AI.ipynb` to open and run the notebook cells.

## Files

* `fashion_cloth_AI.ipynb`: The main Jupyter Notebook containing the code for data loading, model building, training, and evaluation.
* `README.md`: This file.

## Contributing

If you have suggestions for improvements or find issues, feel free to open an issue or submit a pull request.

## License

*(Consider adding a license, like MIT or Apache 2.0, to specify how others can use your code. You can add a LICENSE file and mention it here. If you don't add a license, standard copyright applies.)*

This project is currently unlicensed.

## Contact

You can reach the repository owner (stan447) via their GitHub profile.
# Sign Language Recognition

This project provides scripts for collecting images, creating datasets, training a classifier, and running inference.

## Project Structure

- `collect_imgs.py` — Script to collect images.
- `create_dataset.py` — Script to create a dataset from collected images.
- `train_classifier.py` — Script to train an image classifier.
- `inference_classifier.py` — Script to run inference using the trained classifier.
- `model.p` — Saved model file.
- `data.pickle` — Pickled dataset information.
- `requirements.txt` — Python dependencies.
- `data/` — Directory containing image data, organized by class.

## Setup

1. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

2. Collect images:
    ```sh
    python collect_imgs.py
    ```

3. Create the dataset:
    ```sh
    python create_dataset.py
    ```

4. Train the classifier:
    ```sh
    python train_classifier.py
    ```

5. Run inference:
    ```sh
    python inference_classifier.py
    ```

## Data Organization

Images are stored in `data/`, with each subfolder representing a class (e.g., `data/0/`, `data/1/`, etc.).

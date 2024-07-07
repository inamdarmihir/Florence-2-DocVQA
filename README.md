# Florence-2-DocVQA

## Overview
This repository contains the code and resources for fine-tuning the Florence-2 model on the DocVQA dataset. The Florence-2 model is a state-of-the-art vision-language model designed for various visual understanding tasks. The DocVQA dataset consists of images of documents with corresponding questions and answers, aimed at evaluating the visual question answering capabilities on document images.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [Requirements](#requirements)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
This project focuses on fine-tuning the Florence-2 model on the DocVQA dataset to improve its performance in visual question answering tasks specifically related to document images. The fine-tuned model aims to accurately answer questions based on the content of the documents provided in the dataset.

## Dataset
The DocVQA dataset is a large-scale dataset specifically designed for document visual question answering. It contains:
- Document images
- Questions related to the content of these documents
- Answers to the questions

The dataset is publicly available and can be downloaded from the official DocVQA website or repository.

## Model Architecture
Florence-2 is a sophisticated vision-language model that leverages advanced techniques in both computer vision and natural language processing. It uses a transformer-based architecture to process and understand the visual content of images and the associated textual information.

## Training
The training process involves fine-tuning the pre-trained Florence-2 model on the DocVQA dataset. Key steps include:
1. Preparing the dataset: Preprocessing the document images and associated QA pairs.
2. Setting up the training environment: Configuring the necessary libraries and dependencies.
3. Fine-tuning the model: Using the training data to adjust the model parameters for improved performance on the DocVQA task.

## Evaluation
The model is evaluated on a separate validation set from the DocVQA dataset. Key metrics for evaluation include:
- Accuracy: The percentage of correctly answered questions.
- F1 Score: A measure of the model's precision and recall.
- Mean Reciprocal Rank (MRR): Evaluates the rank of the correct answer.

## Results
The fine-tuned Florence-2 model achieves state-of-the-art results on the DocVQA dataset, demonstrating significant improvements in accuracy and other evaluation metrics compared to baseline models.

## Usage
To use the fine-tuned model for inference on new document images, follow these steps:
1. Clone this repository.
2. Install the required dependencies.
3. Prepare your input document images.
4. Run the inference script to get answers to your questions based on the document images.

Example:
```bash
git clone https://github.com/inamdarmihir/Florence-2-DocVQA.git
cd Florence-2-DocVQA
pip install -r requirements.txt
python inference.py --input_image_path <path_to_image> --question <your_question>
```

## Requirements
- Python 3.8+
- PyTorch
- Transformers
- OpenCV
- Other dependencies listed in `requirements.txt`

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/inamdarmihir/Florence-2-DocVQA.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Florence-2-DocVQA
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Contributing
Contributions are welcome! If you have any improvements, bug fixes, or new features to add, please submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any questions or inquiries, please contact:

Mihir Inamdar  
[GitHub: inamdarmihir]

Thank you for using the Florence-2-DocVQA repository! We hope this project helps you achieve your visual question answering goals on document images.

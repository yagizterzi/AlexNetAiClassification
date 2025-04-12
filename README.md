# REAL/FAKE Image Classification using AlexNet

## Description

This project uses a modified AlexNet model to classify images as either real or fake (AI-generated). It leverages the CIFake dataset, which contains both real and synthetic images. The model is trained to distinguish between these two categories.

## Dataset

The project uses the CIFake dataset available on Kaggle: [CIFake - Real and AI-Generated Synthetic Images](link_to_dataset).

## Model

The core of this project is a modified AlexNet model, a convolutional neural network architecture known for its image classification capabilities. Adaptations have been made to accommodate the 32x32 image size of the CIFake dataset.

## Usage

1. **Download the dataset:** The dataset is automatically downloaded using `kagglehub` library. Ensure you have the library installed and configured to access Kaggle datasets.
2. **Preprocessing:** The images are normalized to a range of 0-1.
3. **Training:** The AlexNet model is trained on the training data, utilizing an Adam optimizer and binary cross-entropy loss function.
4. **Evaluation:** The trained model is evaluated on the validation data, reporting metrics such as accuracy, precision, recall, and AUC.

## Results

The results of the model's performance on the validation data are displayed after training. These include the loss, accuracy, precision, recall, and AUC.

## Requirements

The necessary Python packages are listed in the `requirements.txt` file. You can install them using:
bash pip install -r requirements.txt

## Contributing

Feel free to contribute to this project by suggesting improvements, reporting issues, or adding new features.

## License

This project is licensed under the [MIT] license.

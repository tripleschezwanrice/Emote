# emote.io

## Features
- **Real-time face detection and emotion recognition**.
- **Uses a trained deep learning model** for accurate emotion predictions.
- **Simple integration with OpenCV** for video capture.

## Dataset
The model is trained on the **Face Expression Recognition Dataset** from Kaggle, which consists of **35 thousand images** with labeled emotions.

## Model Training
The model was trained for **100 epochs**, and the final epoch's metrics are as follows:
- **Training loss**: 0.7405
- **Training accuracy**: 73.07%
- **Validation loss**: 1.0369
- **Validation accuracy**: 63.08%

The training process took a total of **6 hours and 34 minutes** on a 2020 M1 MacBook Air.

## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/tripleschezwanrice/Emote.git
    ```
2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Execute the `realtime.ipynb` file.
4. Press 'Q' to end the program.

## License
This project is licensed under the **MIT License**.

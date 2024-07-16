# Chatbot with CNN

Welcome to the Chatbot with CNN project! This repository contains a Python implementation of a chatbot that uses a Convolutional Neural Network (CNN) to train on a JSON file of intents, which contains predefined questions and answers. The chatbot leverages this training to provide accurate responses to user queries.

## Features

- **JSON-based Intents**: The chatbot uses a JSON file (`intents.json`) that contains pairs of questions and answers, organized into different intents.
- **CNN Model**: The chatbot is powered by a Convolutional Neural Network (CNN) that is trained on the data provided in the `intents.json` file.
- **Interactive Responses**: The trained model enables the chatbot to provide accurate and relevant responses based on user input.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

- Python 3.x
- TensorFlow
- Numpy
- NLTK (Natural Language Toolkit)
- JSON

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mali-98/Chatbot-Using-Python.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Chatbot-Using-Python
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

### Training the Model

1. **Prepare the Data**:
   - Ensure the `intents.json` file is correctly formatted and placed in the project directory.

### Using the Chatbot

1. **Run the Chatbot**:
   ```bash
   python main.py
   ```

2. **Interact with the Chatbot**:
   - Start a conversation with the chatbot and it will respond based on the training it received from the `intents.json` file.

## Project Structure

- `train_chatbot.py`: Script to train the CNN model on the intents data.
- `chatbot.py`: Script to run the chatbot and handle user interactions.
- `intents.json`: JSON file containing the questions and answers for different intents.
- `requirements.txt`: List of dependencies for the project.

## How It Works

1. **Data Preprocessing**: The intents data is preprocessed, including tokenization and vectorization of the text.
2. **Model Training**: The CNN model is trained on the preprocessed data, learning to associate user inputs with appropriate responses.
3. **Prediction**: The trained model predicts the best response for a given user input by analyzing the input text and matching it with the closest intent.

## Contributing

We welcome contributions to enhance this project. Feel free to open issues or submit pull requests with improvements, bug fixes, or new features.
Feel free to customize the content to better fit your project's specifics and your preferences.

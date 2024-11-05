# Sentiment Analysis with Caikit and Hugging Face 🎉

[![Caikit Badge](https://img.shields.io/badge/Caikit-v0.9.2-brightgreen)](https://caikit.ai) [![Hugging Face Badge](https://img.shields.io/badge/Hugging%20Face-Model%20Serving-blue)](https://huggingface.co) [![OS Badge](https://img.shields.io/badge/OS-Linux%20%2F%20MacOS%20x86_64-lightgray)](https://www.linux.org/) [![Python Badge](https://img.shields.io/badge/Python-v3.8%2B-blue)](https://www.python.org/) [![pip Badge](https://img.shields.io/badge/pip-v23.0%2B-orange)](https://pip.pypa.io/en/stable/)

## Prerequisites ⚙️
- **Operating System**: Linux/MacOS x86_64 
- **Caikit Version**: v0.9.2 
- **Python Version**: v3.8+ 
- **pip Version**: v23.0+ 

## Overview 📚
This project implements a sentiment analysis application using the **Caikit** framework and **Hugging Face's** model serving capabilities. The goal is to perform text sentiment analysis by configuring the Caikit runtime and an AI model, followed by testing it through a client application.

## Procedure 🛠️
Complete the following tasks to configure the Caikit runtime and the AI model, and then test them from a client application:

1. **Create the Project**: 
   - Set up the necessary directories and files for your project.
   
2. **Create the Data Model Specification**: 
   - Define the data format used by the Caikit module.
   
3. **Create the Model Wrapper**: 
   - Implement a wrapper that integrates the AI model with the Caikit framework.
   
4. **Include the Module and Package Dependencies**: 
   - Specify any necessary dependencies in your project configuration.
   
5. **Start the Caikit Runtime**: 
   - Launch the Caikit runtime to serve the model for inference.
   
6. **Test the Sentiment Analysis**: 
   - Run tests to validate the functionality of the sentiment analysis model through a client application.

## Installation 🚀

1. **Install `virtualenv`**:
   ```bash
   pip install --user virtualenv

2. **Create a virtual environment**:
   ```bash
   virtualenv -p python3 env

3. **Activate the virtual environment**:
   ```bash
  source env/bin/activate

4. **Install requirements**:
   ```bash
 pip install -r requirements.txt

5. **Start the Caikit Runtime:**:
   ```bash
   python start_runtime.py

6. **Start the Client**:
   ```bash
   python client.py
   
## Usage 💻
Follow the steps outlined in the Procedure section to run the sentiment analysis application.

## Contributing 🤝
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

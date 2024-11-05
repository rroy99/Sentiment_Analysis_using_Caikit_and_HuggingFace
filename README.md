<p align="center">
  <h1>Sentiment Analysis with Caikit and Hugging Face 🎉</h1>
</p>

<p align="center">
  <a href="https://caikit.ai">
    <img src="https://img.shields.io/badge/Caikit-v0.9.2-brightgreen" alt="Caikit Badge"/>
  </a>
  <a href="https://huggingface.co">
    <img src="https://img.shields.io/badge/Hugging%20Face-Model%20Serving-blue" alt="Hugging Face Badge"/>
  </a>
  <a href="https://www.linux.org/">
    <img src="https://img.shields.io/badge/OS-Linux%20%2F%20MacOS%20x86_64-lightgray" alt="OS Badge"/>
  </a>
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-v3.8%2B-blue" alt="Python Badge"/>
  </a>
  <a href="https://pip.pypa.io/en/stable/">
    <img src="https://img.shields.io/badge/pip-v23.0%2B-orange" alt="pip Badge"/>
  </a>
</p>

## Prerequisites ⚙️
- **Operating System**: Linux/MacOS x86_64 
- **Caikit Version**: v0.9.2 
- **Python Version**: v3.8+ 
- **pip Version**: v23.0+ 

## Overview 📚
<p align="justify">
This project implements a sentiment analysis application using the <strong>Caikit</strong> framework and <strong>Hugging Face's</strong> model serving capabilities. The goal is to perform text sentiment analysis by configuring the Caikit runtime and an AI model, followed by testing it through a client application.
</p>

## Procedure 🛠️
<p align="justify">
Complete the following tasks to configure the Caikit runtime and the AI model, and then test them from a client application:
</p>

1. **Create the Project**: 
   - Set up the necessary directories and files for your project.
     ```bash
     pip install --user virtualenv  
     mkdir -p /home/project/text-sentiment/text_sentiment  
     cd /home/project/text-sentiment/text_sentiment
     ```

2. **Create the Data Model Specification**: 
   - Define the data format used by the Caikit module.
     ```bash
     mkdir data_model
     cd data_model
     touch classification.py
     ```

3. **Create the Model Wrapper**: 
   - Implement a wrapper that integrates the AI model with the Caikit framework.
     ```bash
     mkdir -p models/text_sentiment
     cd models/text_sentiment
     touch config.yml
     mkdir runtime_model
     cd runtime_model
     touch hf_module.py
     touch __init__.py
     cd ../../..  # Kembali ke direktori proyek
     ```

4. **Include the Module and Package Dependencies**: 
   - Specify any necessary dependencies in your project configuration.
     ```bash
     touch requirements.txt
     virtualenv -p python3 env
     source env/bin/activate
     pip install -r requirements.txt
     ```

5. **Start the Caikit Runtime**: 
   - Launch the Caikit runtime to serve the model for inference.
     ```bash
     touch start_runtime.py
     python start_runtime.py
     ```

6. **Test the Sentiment Analysis**: 
   - Run tests to validate the functionality of the sentiment analysis model through a client application.
     ```bash
     touch client.py
     python client.py
     ```
     

## Example Result 📊✨
<p align="center">
  <img src="https://raw.githubusercontent.com/rroy99/Sentiment_Analysis_using_Caikit_and_HuggingFace/main/WhatsApp%20Image%202024-11-05%20at%2020.44.26.jpeg" alt="Sentiment Analysis Image"/>
</p>

## Contributing 🤝
<p align="justify">
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.
</p>

## Credits 🙏
<p align="justify">
This project is inspired by materials from <strong>Cognitive Class</strong>.
</p>

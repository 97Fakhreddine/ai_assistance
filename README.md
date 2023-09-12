# AI Assistant Setup Guide

Follow these steps to set up your AI assistant project:

## Prerequisites

- Python 3 installed on your system.
- Virtual Environment (venv) installed.

## Setup

1. Install Python 3 if you haven't already.

2. Create a Virtual Environment and activate it. Here's how:

    - Create a virtual environment (replace `.myvenv` with your preferred virtual environment name):
      ```shell
      python -m venv .myvenv
      ```

    - Activate the virtual environment:
        - On Windows:
          ```shell
          .myvenv\Scripts\activate.bat
          ```

        - On Linux and macOS:
          ```shell
          source .myvenv/bin/activate
          ```

3. Install the required dependencies using pip:

   ```shell
   pip install speechrecognition
   pip install pyttsx3
   pip install wikipedia
   pip install wolframalpha
   pip install pygame
   pip install openai

If you plan to use Google Cloud Text-to-Speech, install it with the following command:
```bash 
pip3 install --user --upgrade google-cloud-texttospeech
```
Follow the instructions on the Google Cloud website or the provided video tutorial to set up authentication and enable the required API.

That's it! Your AI assistant project is now set up and ready to use. You can start exploring the capabilities of your assistant as outlined in the project documentation.

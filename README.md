# Project Code Maker

![GitHub stars](https://img.shields.io/github/stars/SixSigmaEngineer/ProjectCodeMaker.svg?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/SixSigmaEngineer/ProjectCodeMaker.svg?style=for-the-badge)
![License](https://img.shields.io/github/license/SixSigmaEngineer/ProjectCodeMaker.svg?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/SixSigmaEngineer/ProjectCodeMaker.svg?style=for-the-badge)

## Overview 🔍

Project Code Maker is a Python script that utilizes the OpenAI API and the LangChain library to generate unique and creative project codenames based on the client's business or product.

### Features

- Quickly generate project codenames for client projects.
- Utilizes the power of the OpenAI language model to create creative and context-aware codenames.

## Getting Started

To use this project codename generator, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/SixSigmaEngineer/ProjectCodeMaker.git
cd ProjectCodeMaker
Set up your OpenAI API Key:

Open the included python file.
Replace 'YOUR_OPENAI_API_KEY' with your actual OpenAI API key.
Install the required Python libraries:

pip install langchain
Run the generator:
bash
Copy code
python generator.py
Enter the type of business or product for which you need a project codename.

The script will generate a unique codename and display it in the terminal.

Customization
You can customize the prompt template in the generator.py file to fit your specific needs. Adjust the template to ask for additional information or modify the generated codename as necessary.

python
Copy code
template1 = "What is a good codeword for a client project that is in the business of {product}? Make it one single codeword."
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and test them.
Submit a pull request with a clear description of your changes.
License
This project is licensed under the MIT License.

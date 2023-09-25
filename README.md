# Project Code Maker

![GitHub](https://img.shields.io/github/license/SixSigmaEngineer/ProjectCodeMaker)
![GitHub last commit](https://img.shields.io/github/last-commit/SixSigmaEngineer/ProjectCodeMaker)
![GitHub issues](https://img.shields.io/github/issues-raw/SixSigmaEngineer/ProjectCodeMaker)

## Description

Project Code Maker is a Python tool that generates unique codenames for your client projects based on their business or product type. It utilizes the LangChain Library and the OpenAI API to provide creative and meaningful codewords.

## Features

- Automatically generates project codenames
- Uses human input to specify the client's business or product type
- Integrates with OpenAI for creative codename suggestions

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SixSigmaEngineer/ProjectCodeMaker.git
Navigate to the project directory:

```bash
Copy code
cd ProjectCodeMaker
Set your OpenAI API key as an environment variable:

```bash
Copy code
export OPENAI_API_KEY=your_api_key_here
Run the project using the provided batch file:

```bash
Copy code
./run_project.sh
Follow the on-screen instructions to enter the client's business or product type, and Project Code Maker will generate a unique codename.

Dependencies
LangChain Library
OpenAI Python
You can install the required dependencies using pip:

```bash
Copy code
pip install langchain
pip install openai
Configuration
You should set your OpenAI API key as an environment variable before running the project. Replace your_api_key_here with your actual API key.

```bash
Copy code
export OPENAI_API_KEY=your_api_key_here
Contributing
Contributions are welcome! If you'd like to contribute to Project Code Maker, please follow these guidelines:

Fork the repository.
Create a new branch for your feature: git checkout -b feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Create a pull request.
Please make sure your code follows the project's coding standards and includes relevant tests.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or suggestions, feel free to contact the project owner:

Email: your@email.com
GitHub: SixSigmaEngineer

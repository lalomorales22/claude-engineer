# AI-Powered Software Development Assistant

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Configuration](#configuration)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgements](#acknowledgements)

## Introduction

The AI-Powered Software Development Assistant is an advanced tool that leverages the Claude AI model to provide interactive coding help, project management, and software development insights. It combines natural language processing, code analysis, and real-time web search capabilities to offer a comprehensive assistant for developers.

## Features

- AI-powered conversation for software development assistance
- File and directory management within your project structure
- Code syntax highlighting for better readability
- Image analysis capabilities
- Real-time web search integration
- Autonomous mode for independent task execution
- Conversation memory for contextual interactions
- Configuration management using YAML and environment variables
- Robust error handling and logging system
- Asynchronous operations for improved performance
- Interactive and colorful command-line interface
- Code diff generation for clear change visualization

## Prerequisites

- Python 3.9 or higher
- Anthropic API key
- Tavily API key

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ai-dev-assistant.git
   cd ai-dev-assistant
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Configuration

1. Copy the example configuration file:
   ```
   cp config.example.yaml config.yaml
   ```

2. Open `config.yaml` and add your API keys:
   ```yaml
   anthropic_api_key: "your_anthropic_api_key_here"
   tavily_api_key: "your_tavily_api_key_here"
   ```

   Alternatively, you can set these as environment variables:
   ```
   export ANTHROPIC_API_KEY="your_anthropic_api_key_here"
   export TAVILY_API_KEY="your_tavily_api_key_here"
   ```

## Usage

Run the assistant:

```
python g0dmode.py
```

### Commands:
- Type your questions or requests for AI assistance
- Type 'exit' to end the conversation
- Type 'image' to include an image in your message
- Type 'automode [number]' to enter Autonomous mode with a specific number of iterations

### Examples:

1. Ask for coding help:
   ```
   You: Can you help me write a Python function to calculate the Fibonacci sequence?
   ```

2. Request project structure creation:
   ```
   You: Create a basic folder structure for a Python web application using Flask.
   ```

3. Analyze an image:
   ```
   You: image
   You: Drag and drop your image here: /path/to/your/image.jpg
   You: Can you describe what you see in this image and suggest how it might relate to a software project?
   ```

4. Enter automode:
   ```
   You: automode 5
   You: Refactor the Python script in the current directory to improve its efficiency and readability.
   ```

## Contributing

We welcome contributions to the AI-Powered Software Development Assistant! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request

Please make sure to update tests as appropriate and adhere to the project's coding standards.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Anthropic](https://www.anthropic.com) for the Claude AI model
- [Tavily](https://tavily.com) for the search API
- All the open-source libraries used in this project

---

For any questions or issues, please open an issue on the GitHub repository.

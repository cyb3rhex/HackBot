
# HackBot - AI Cybersecurity Chatbot
```text
     _   _            _    ____        _   
    | | | | __ _  ___| | _| __ )  ___ | |_ 
    | |_| |/ _` |/ __| |/ /  _ \ / _ \| __| By: Morpheuslord
    |  _  | (_| | (__|   <| |_) | (_) | |_  AI used: Meta-LLama2
    |_| |_|\__,_|\___|_|\_\____/ \___/ \__|
```

## Introduction

Welcome to HackBot, an AI-powered cybersecurity chatbot designed to provide helpful and accurate answers to your cybersecurity-related queries and also do code analysis and scan analysis. Whether you are a security researcher, an ethical hacker, or just curious about cybersecurity, HackBot is here to assist you in finding the information you need.

HackBot utilizes the powerful language model Meta-LLama2 through the "LlamaCpp" library. This allows HackBot to respond to your questions in a coherent and relevant manner. Please make sure to keep your queries in English and adhere to the guidelines provided to get the best results from HackBot.

## Features

- **AI Cybersecurity Chat:** HackBot can answer various cybersecurity-related queries, helping you with penetration testing, security analysis, and more.
- **Interactive Interface:** The chatbot provides an interactive command-line interface, making it easy to have conversations with HackBot.
- **Clear Output:** HackBot presents its responses in a well-formatted markdown, providing easily readable and organized answers.
- **Static Code Analysis:** Utilizes the provided scan data or log file for conducting static code analysis. It thoroughly examines the source code without executing it, identifying potential vulnerabilities, coding errors, and security issues.
- **Vulnerability Analysis:** Performs a comprehensive vulnerability analysis using the provided scan data or log file. It identifies and assesses security weaknesses, misconfigurations, and potential exploits present in the target system or network.

## How it looks

### Chat:
![HackBot_chat](https://github.com/morpheuslord/HackBot/assets/70637311/01a95209-6037-45c6-aadc-30919abccf7e)

### Static Code analysis:
![code_analysis](https://github.com/morpheuslord/HackBot/assets/70637311/52ef1b07-4cf0-464e-91ac-9e3b7d015cb2)

### Vulnerability analysis:
![vuln_analysis](https://github.com/morpheuslord/HackBot/assets/70637311/6683b226-425e-4862-b254-f155f8f7b57d)

## Installation

### Prerequisites

Before you proceed with the installation, ensure you have the following prerequisites:

- Python (3.10 or later)
- `pip3` package manager
- `Visual studio Code` - Follow the steps in this link [llama-cpp-prereq-install-instructions](https://github.com/abetlen/llama-cpp-python)
- `cmake`

### Step 1: Clone the Repository

```bash
git clone https://github.com/morpheuslord/hackbot.git
cd hackbot
```

### Step 2: Install Dependencies

```bash
pip3 install -r requirements.txt
```

### Step 3: Download the AI Model

```bash
python3 hackbot.py
```

The first time you run HackBot, it will check for the AI model required for the chatbot. If the model is not present, it will be automatically downloaded and saved as "llama-2-7b-chat.ggmlv3.q4_0.bin" in the project directory.

## Usage

To start a conversation with HackBot, run the following command:

```bash
python3 hackbot.py
```

HackBot will display a banner and wait for your input. You can ask cybersecurity-related questions, and HackBot will respond with informative answers. To exit the chat, simply type "quit_bot" in the input prompt.

Here are some additional commands you can use:

- `clear_screen`: Clears the console screen for better readability.
- `quit_bot`: This is used to quit the chat application
- `bot_banner`: Prints the default bots banner.
- `contact_dev`: Provides my contact information.
- `save_chat`: Saves the current sessions interactions.
- `vuln_analysis`: Does a Vuln analysis using the scan data or log file.
- `static_code_analysis`: Does a Static code analysis using the scan data or log file.

**Note:** I am working on more addons and more such commands to give a more chatGPT experience

**Please Note:** HackBot's responses are based on the Meta-LLama2 AI model, and its accuracy depends on the quality of the queries and data provided to it.

I am also working on AI training by which I can teach it how to be more accurately tuned to work for hackers on a much more professional level.

## Contributing

We welcome contributions to improve HackBot's functionality and accuracy. If you encounter any issues or have suggestions for enhancements, please feel free to open an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch with a descriptive name.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Open a pull request to the `main` branch of this repository.

Please maintain a clean commit history and adhere to the project's coding guidelines.

## AI training
If anyone with the know-how of training text generation models can help improve the code.

## Contact

For any questions, feedback, or inquiries related to HackBot, feel free to contact the project maintainer:

- Email: morpheuslord@protonmail.com
- Twitter: [@morpheuslord2](https://twitter.com/morpheuslord2)
- LinkedIn: [ChiranjeeviG](https://www.linkedin.com/in/chiranjeevi-g-naidu/)

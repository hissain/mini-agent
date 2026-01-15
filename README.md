# mini-agent

Minimal implementation of a coding assistant, capable of reading, writing, and editing files, as well as running shell commands.

## Requirements

- Python 3.x
- An API key for one of the supported providers:
  - Google Gemini
  - Anthropic
  - OpenRouter

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hissain/mini-agent.git
   cd mini-agent
   ```

2. Install dependencies (standard library only, no external pip packages required).

## Configuration

Set the environment variable for your chosen provider:

- For Google Gemini:
  ```bash
  export GEMINI_API_KEY="your-key-here"
  ```

- For Anthropic:
  ```bash
  export ANTHROPIC_API_KEY="your-key-here"
  ```

- For OpenRouter:
  ```bash
  export OPENROUTER_API_KEY="your-key-here"
  ```

Optionally, you can specify the model:
```bash
export MODEL="gemini-2.0-flash"
```

## Usage

Run the agent:

```bash
python agent.py
```

### Commands

- `/q` or `exit`: Quit the application.
- `/c`: Clear the conversation history.
- `/i`: Show system information.

Inspired by [nanocode](https://github.com/1rgs/nanocode)

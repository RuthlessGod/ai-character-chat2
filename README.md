# AI Character Chat

A web application for creating and interacting with AI-powered characters, featuring memory, multiple conversations, and player actions.

## Overview

AI Character Chat is a Flask-based application that allows users to:
- Create custom AI characters with distinct personalities and traits
- Chat with characters through a user-friendly interface
- Use AI-assisted generation for character features
- Perform roleplaying actions with different resolution methods
- Maintain persistent memory across conversations
- Manage multiple ongoing chat instances
- Customize prompt templates for AI interactions

## Key Features

- **Character Management**: Create, edit, and delete AI characters
- **AI-Assisted Generation**: Generate character names, descriptions, personalities, etc.
- **Multiple Chat Instances**: Maintain separate conversations with different characters
- **Memory System**: Characters remember previous interactions and context
- **Player Action System**: Interactive roleplaying with action resolution
- **Theme Customization**: Light/dark mode and different chat display styles
- **Field-Specific Generation**: Targeted AI content for individual character attributes
- **Prompt Template Management**: Customize how the AI responds in different contexts

## System Architecture

The application follows a modular architecture with clear separation of concerns:

### Backend (Python/Flask)
- RESTful API endpoints for all functionality
- AI model integration with OpenRouter or local models
- Character and chat instance management
- Memory and context management
- Scene and location description generation

### Frontend (HTML/CSS/JavaScript)
- Responsive UI with theme support
- Character creation and management interface
- Chat interface with message history
- Settings customization
- Field-specific AI generation interface
- Player action UI

## Documentation

The repository includes comprehensive documentation:

- **dir.md**: Directory structure and file overviews
- **pythonFiles.md**: Detailed documentation of Python modules
- **jsfiles.md**: Documentation of JavaScript modules

## Getting Started

### Prerequisites
- Python 3.8+
- OpenRouter API key or local LLM

### Installation

1. Clone the repository
```bash
git clone https://github.com/RuthlessGod/ai-character-chat2.git
cd ai-character-chat2
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Configure the application
- Create a `.env` file based on the provided template
- Add your OpenRouter API key or configure a local model

4. Start the application
```bash
# On Windows
start.bat

# On Linux/Mac
./start.sh
```

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Inspired by character-based AI interactions and roleplaying systems
- Special thanks to all contributors to this project
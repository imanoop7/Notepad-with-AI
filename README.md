# AI-Powered Notepad 🚀

A sophisticated notepad application featuring real-time AI-powered suggestions powered by Ollama's state-of-the-art language models.

## ✨ Features

### Core Features
- 🤖 Real-time AI suggestions as you type
- 📝 Clean, modern interface
- 🎯 Inline suggestions at cursor position
- 💾 Standard file operations (New, Open, Save)
- 🔄 Multiple AI model support with easy switching

### AI Capabilities
- Context-aware text completion
- Intelligent suggestions based on your writing
- Fast response times
- Multiple model options for different use cases

## 🤖 Supported AI Models

### Default Model
- **phi3** - Microsoft's latest model, optimized for fast responses

### Available Models
- **Gemma Series**
  - gemma - Google's base model
  - gemma2 - Enhanced version with improved capabilities

- **Qwen Series**
  - qwen - Alibaba's base model
  - qwen2 - Improved version with better performance

- **LLaMA Series**
  - llama2 - Meta's powerful language model
  - llama3 - Latest version with enhanced capabilities
  - codellama - Specialized for code completion

- **Other Models**
  - mistral - Fast and efficient model
  - tinyllama - Lightweight model for quick responses

## 🛠️ Requirements

### System Requirements
- Python 3.8 or higher
- Ollama installed and running
- Windows/Linux/MacOS supported

### Python Dependencies
```
tkinter (built-in with Python)
ttkthemes>=3.2.2
requests>=2.31.0
```

## 📦 Installation

1. **Install Ollama**
   ```bash
   # Visit https://ollama.ai
   # Download and install the appropriate version for your OS
   ```

2. **Clone the Repository**
   ```bash
   git clone https://github.com/imanoop7/Notepad-with-AI.git
   cd Notepad-with-AI
   ```

3. **Install Python Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Pull Required Models**
   ```bash
   # Pull the default model (phi3)
   ollama pull phi3
   
   # Optional: Pull additional models
   ollama pull gemma
   ollama pull llama2
   # etc.
   ```

## 🚀 Usage

### Starting the Application
```bash
python notepad.py
```

### Basic Operations
- **Create New File**: Ctrl+N or File → New
- **Open File**: Ctrl+O or File → Open
- **Save File**: Ctrl+S or File → Save
- **Exit**: File → Exit

### AI Features
1. **Getting Suggestions**
   - Simply start typing
   - Suggestions appear inline at your cursor
   - Press Tab to accept suggestions

2. **Changing AI Models**
   - Click AI → Change Model
   - Select from available models
   - Changes take effect immediately

### Keyboard Shortcuts
| Shortcut | Action |
|----------|--------|
| Ctrl+N | New File |
| Ctrl+O | Open File |
| Ctrl+S | Save File |
| Tab | Accept Suggestion |

## ⚙️ Configuration

### Default Settings
- Default Model: phi3
- Suggestion Delay: 1.0 seconds
- Font: Consolas, 11pt

### Model Selection Tips
- Use **phi3** for general writing
- Use **codellama** for programming
- Use **tinyllama** for faster responses
- Use **gemma/qwen** for creative writing

## 🔧 Troubleshooting

### Common Issues
1. **No Suggestions Appearing**
   - Check if Ollama is running
   - Verify model is properly installed
   - Check console for error messages

2. **Slow Responses**
   - Try switching to a lighter model (tinyllama)
   - Verify system resources

3. **Model Not Found**
   - Run `ollama pull [model_name]`
   - Restart the application
   - Check Ollama installation

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

# Nexus AI  ✨

Nexus AI is a modern, streamlined hub for creative AI tools. It provides an elegant interface for interacting with various AI services, including multi-model chat, image generation, and text-to-speech.

## 🚀 Online Experience

**[Visit Nexus AI -> ](https://pollinationsai.vercel.app/)**

## Core Features

* 🎨 **AI Tool Hub**: An elegant homepage showcasing all available AI tools.
* 💬 **Multi-Model AI Chat**:
* Converse with multiple cutting-edge AI models (GPT-4o, Llama 3, Claude 3.5, and more).
* Fluent conversations with contextual memory.
* A simple, tech-savvy user interface.
* 🖼️ **AI Image Generation**: Quickly access powerful text-to-image tools.
* 🔊 **AI Text-to-Speech**: Quickly connect to high-quality speech synthesis tools.
* 🌓 **Light and Dark Theme Switcher**: Switch between light and dark modes based on your preference.
* 📱 **Responsive Design**: Get a great experience on both desktop and mobile.

## 🛠️ Technology Stack

This project is built entirely with front-end infrastructure, with no backend servers or complex dependencies.

* **HTML**
* **CSS** (using native CSS variables for theming)
* **JavaScript** (native, no framework)

## Running Locally

You can easily run Nexus AI on your local computer.

1. **Clone the code repository:**
```bash
git clone https://github.com/zhangyao421/nexus-ai.git
```

2. **Enter the project directory:**
```bash
cd nexus-ai
```

3. **Start a local server:**
Due to browser security restrictions, you need to access `index.html` through a local server instead of opening it directly in the file browser. The easiest way is:

**Method 1: Use the Live Server plugin for VS Code**
* If you use Visual Studio Code, install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) plugin.
* Open the project folder in VS Code, then right-click the `index.html` file and select "Open with Live Server".

**Method 2: Using Python**
* If Python is installed on your computer, simply run the following command in the project root directory:
```bash
# Python 3.x
python -m http.server

# Python 2.x
python -m SimpleHTTPServer
```
* Then visit `http://localhost:8000` in your browser.

## ⚙️ Configuration

The AI chat feature requires an API key to work.

1. Open the `chat/index.html` file.

2. Find the `<script>` section at the bottom of the file.

3. Modify the `API_KEY` variable and fill it with your valid key:

```javascript
// API Key
const API_KEY = 'xxxxxxxxxx'; // <-- Replace this with your key
```
*Note: The code already includes your provided key. If you need to change it, please modify this line. *

## 🤝 Contributions

Contributions of all kinds are welcome! If you have a good idea or find a bug, please feel free to submit a pull request or open an issue.

## 📄 License

This project is open source under the [MIT License](LICENSE).

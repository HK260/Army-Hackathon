# 🦙 Installing Ollama & Downloading LLaMA 3.2 Locally

This guide provides step-by-step instructions to install **Ollama** on your local machine and use it to download the **LLaMA 3.2** model.

---

## ✅ 1. Install Ollama

### 🔹 macOS (Apple Silicon & Intel)

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### 🔹 Linux (Ubuntu / Debian)

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

> Make sure Docker is installed and running.

### 🔹 Windows

1. Download the installer: [https://ollama.com/download](https://ollama.com/download)
2. Run the `.exe` file and follow the installation steps.
3. Open Command Prompt or PowerShell to use `ollama`.

---

## ✅ 2. Verify Installation

Run the following command to confirm `ollama` is installed:

```bash
ollama --version
```

You should see something like:

```
ollama version 0.x.x
```

---

## 🚀 3. Download & Run LLaMA 3.2

Once Ollama is installed, you can pull the LLaMA 3.2 model:

```bash
ollama pull llama3.2
```

After the model is downloaded, you can launch your AI assistant notebook:

```bash
jupyter notebook ai_assistant.ipynb
```

## 📌 Notes

- Models are downloaded and cached locally.
- Ollama runs the model locally on CPU or GPU depending on your hardware.
- To list all available models:

```bash
ollama list
```

- For advanced usage (custom models, system prompts, etc.), refer to: [https://ollama.com/docs](https://ollama.com/docs)

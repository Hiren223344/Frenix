Frenix AI

Frenix AI is an OpenAI-compatible AI gateway that provides unified access to multiple AI models through a single API.

Frenix allows developers to route requests between different providers such as GPT, Claude, Gemini, and open-source models while keeping a consistent API interface.

🌐 Website: https://www.frenix.sh

---

🚀 Features

- OpenAI-compatible API
- Multi-provider model routing
- Unified API endpoint for multiple models
- Easy integration with existing OpenAI SDKs
- Support for GPT, Claude, Gemini, and other models
- High-performance AI gateway architecture

---

📦 Supported Models

Frenix can route requests to multiple providers, including:

- OpenAI models
- Claude models
- Gemini models
- Open-source models (LLaMA, Mixtral, etc.)

Example model format:

provider/model-name

Example:

openai/gpt-4
anthropic/claude-opus
google/gemini-pro

---

⚡ Quick Start

1. Clone the repository

git clone https://github.com/YOUR_USERNAME/frenix.git
cd frenix

2. Install dependencies

npm install

3. Start the server

npm run start

---

🔑 API Example

Frenix uses the same format as the OpenAI API.

Endpoint:

POST /v1/chat/completions

Example request:

{
  "model": "openai/gpt-4",
  "messages": [
    {
      "role": "user",
      "content": "Hello!"
    }
  ]
}

Authorization header:

Authorization: Bearer YOUR_API_KEY

---

🔀 Model Routing

Frenix can automatically route models between providers.

Example:

provider-1/claude-opus → provider-2/claude-haiku

This helps ensure reliability and fallback when a provider fails.

---

🌐 Website

Official website:
https://www.frenix.sh

---

📄 License

MIT License

---

👨‍💻 Author

Developed by Hiren Developer

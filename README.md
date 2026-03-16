# Frenix AI

**Frenix AI** is a modern AI platform that provides unified access to multiple advanced language models through a single API interface.

The goal of Frenix AI is to simplify how developers interact with different AI providers by offering a consistent and developer-friendly gateway. Instead of integrating multiple APIs separately, applications can use Frenix AI as a single entry point for accessing powerful AI models.

Frenix AI focuses on performance, reliability, and scalability, making it suitable for AI applications, chatbots, automation tools, and developer platforms.

---

## Key Features

- **Unified AI Gateway**  
  Access multiple AI models through a single API endpoint.

- **150+ Free AI Models**  
  Frenix AI provides access to **150+ AI models completely free of cost**, making it easy for developers to experiment and build without worrying about high API costs.

- **Developer Friendly API**  
  Designed to be simple and compatible with modern AI workflows.

- **Multi-Model Support**  
  Works with different AI models and providers.

- **High Performance Infrastructure**  
  Optimized for fast response times and scalable workloads.

- **Easy Integration**  
  Easily integrate Frenix AI into web apps, mobile apps, or backend services.

---

## Use Cases

Frenix AI can be used for a wide range of AI-powered applications:

- AI chatbots  
- Coding assistants  
- Automation tools  
- AI-powered SaaS platforms  
- Research and experimentation  
- Developer AI tools  

---

## Why Frenix AI?

Developers often need to work with multiple AI models and APIs. Managing different providers can be complex and time-consuming.

Frenix AI simplifies this process by acting as a **central AI gateway**, allowing applications to communicate with different models through a unified system.

Additionally, with **150+ free AI models available**, developers can start building immediately without worrying about expensive API costs.

---

## Website

Official website:  
https://www.frenix.sh

---

## Project Status

Frenix AI is an actively developing project focused on improving the AI developer ecosystem.

New features, improvements, and integrations are continuously being explored.

---

## Author

Developed by **Hiren Developer**

---

## License

This project is released under the **MIT License**.- High-performance AI gateway architecture

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

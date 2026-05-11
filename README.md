# 🔍 AI Monitoring & Observability

Two monitoring projects built with W&B Weave to track 
and compare AI model performance in production.

## 📁 Projects

### 1. RAG App Monitoring
Monitors a Production RAG Application tracking:
- Response times
- Query and answer logging
- Source document tracking
- Full LangChain trace visualization

### 2. Multi-Model Comparison
Compares 3 AI models simultaneously:
- LLaMA 3.1 8b (Meta)
- LLaMA 3.3 70b (Meta)
- Qwen3 32b (Alibaba)

Tracks across all models:
- Response time per model
- Answer quality and length
- Token usage
- Cost comparison

## 🛠️ Tech Stack
- LangChain — orchestration
- Groq API — LLM inference
- W&B Weave — monitoring dashboard
- HuggingFace Embeddings
- ChromaDB — vector database
- Google Colab

## 🔑 Setup
1. Get free API keys from:
   - console.groq.com
   - wandb.ai
2. Replace placeholders in notebooks
3. Run cells top to bottom

## 📊 Dashboard
All traces visible at: wandb.ai

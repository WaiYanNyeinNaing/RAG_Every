# RAG-Anything with Azure OpenAI & Google Gemini Support

Complete multimodal RAG system with dual LLM support and dependency fixes.

## 🚀 Quick Start

### Option 1: Azure OpenAI (GPT-4.1)
```bash
# Setup
cp .env.sample .env
# Add your Azure credentials to .env
python gradio_ui.py
```

### Option 2: Google Gemini (400x cheaper!)
```bash
# Setup
cp .env.gemini.sample .env
# Add your Gemini API key to .env
python gradio_ui_gemini.py
```

## 🔧 Installation (Fixes Dependency Conflicts)

```bash
# Clone repository
git clone https://github.com/WaiYanNyeinNaing/RAG_Every.git
cd RAG-Anything

# Use the fixed installation script
chmod +x install_dependencies.sh
./install_dependencies.sh
```

## 📦 Working Versions
- gradio==5.41.0
- matplotlib==3.10.5
- mineru==2.1.10
- lightrag-hku==1.4.5
- google-generativeai==0.8.5

## 📚 Documentation
- [Azure Setup Guide](README_AZURE.md)
- [Gemini Setup Guide](README_GEMINI.md)
- [Dependency Fixes](DEPENDENCY_FIX.md)
- [MinerU Models](MINERU_MODELS.md)

## 💰 Cost Comparison
| Model | Cost per 1M tokens | Free Tier |
|-------|-------------------|-----------|
| Gemini 2.0 Flash | $0.075 | 1M tokens/month |
| GPT-4 | $30 | None |

## Features
- ✅ Multimodal document processing (PDF, images, tables, equations)
- ✅ Real-time progress tracking
- ✅ Dual LLM support (Azure & Gemini)
- ✅ Dependency conflict resolution
- ✅ Document caching & resume
- ✅ Local MinerU parsing

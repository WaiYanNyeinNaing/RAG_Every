# RAG-Anything with Azure OpenAI Integration

## 🚀 Latest Updates

### Progress Tracking UI
- **NEW**: Real-time progress tracking with `gradio_ui_with_progress.py`
- Shows detailed processing stages:
  - Document Parsing (MinerU)
  - Entity Extraction (Azure GPT-4)
  - Relation Extraction (Azure GPT-4)
  - Graph Building
  - Embedding Creation (Azure text-embedding-3-large)
  - Indexing

### Quick Start
```bash
# Enhanced UI with progress tracking
python gradio_ui_with_progress.py

# OR use the launcher
./launch_progress_ui.sh
```

### Key Features
- Azure OpenAI integration (GPT-4 + text-embedding-3-large)
- Local MinerU parsing (YOLOv8, TableTransformer, LaTeX-OCR, PaddleOCR)
- Automatic rate limit handling
- Document caching and resume capability
- Real-time status updates

### Installation
1. Clone this repository
2. Copy `.env.sample` to `.env` and add your Azure credentials
3. Install dependencies: `pip install -r requirements.txt`
4. Run: `python gradio_ui_with_progress.py`

See full documentation in the main README.

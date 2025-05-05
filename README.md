# Tutorial Codebase Knowledge

A comprehensive knowledge base documenting various Python frameworks, tools, and architectures.

## Project Structure

```
.
├── docs/                  # Documentation files organized by framework/tool
│   ├── AutoGen Core/      # AutoGen framework documentation
│   ├── Celery/           # Celery distributed task queue docs
│   ├── Click/            # Click CLI framework docs
│   └── ...               # Other framework docs
├── utils/                # Utility scripts
│   ├── call_llm.py       # LLM calling utilities
│   └── crawl_*.py       # Documentation crawling scripts
├── flow.py               # Main workflow definition
├── nodes.py              # Node definitions for processing
├── main.py               # Entry point
└── requirements.txt      # Python dependencies
```

## Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/tutorial-codebase-knowledge.git
cd tutorial-codebase-knowledge
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the documentation processor:
```bash
python main.py
```

## Deployment to Modal

This knowledge base can be deployed to [Modal](https://modal.com) as a web service:

1. Install Modal CLI:
```bash
pip install modal-client
```

2. Authenticate:
```bash
modal token new
```

3. Deploy:
```bash
modal deploy main.py
```

## Contributing

To add new documentation:

1. Create a new directory under `docs/` for your framework/tool
2. Add Markdown files following the existing structure
3. Update the main README with links to new content

## License

MIT License - see [LICENSE](LICENSE) for details

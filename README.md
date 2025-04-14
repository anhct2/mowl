# MOWL - Modified Open-source Workflow with Large Language Models

This repository is a fork of the [OWL (Open-source Workflow with Large Language Models)](https://github.com/camel-ai/owl) project with custom modifications and enhancements. It is designed to be used as a personal version with several improvements:

## Enhancements

- Fixed import issues with the utils module in webapp_enhanced.py
- Added enhanced Gradio UI compatibility
- Implemented additional sandbox functionality
- Added progress tracking for scripts
- Added script automation features

## Main Features (from original OWL)

- Agent-based workflows
- Multi-agent collaboration
- Support for various LLM backends
- Terminal-based interactions
- Web UI for easy use

## Getting Started

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your environment variables in `.env` (see `.env_template` for reference)
4. Run the web UI: `python -m owl.webapp_enhanced`

## License

This project maintains the same license as the original OWL project.

## Acknowledgments

- Original [OWL project](https://github.com/camel-ai/owl) by CAMEL AI
- All contributors to the original project

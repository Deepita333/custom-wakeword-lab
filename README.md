# Custom Wakeword Lab 🎙️

**An open-source, beginner-friendly toolkit for training custom wake-word detection models.**

Custom Wakeword Lab aims to make wake-word model training easier to reproduce, debug, and deploy. The project is being developed alongside **Lexi**, a voice assistant for a News Intelligence Platform.

## 🎯 Goals

- Provide a guided Google Colab workflow for custom wake-word training.
- Validate the environment, audio files, and dataset paths before training.
- Make dataset preparation more reliable and recoverable.
- Evaluate models for false activations and missed detections.
- Help developers integrate trained models into their own voice applications.

## 🚧 Project Status

**Early development — training workflow not yet verified end to end.**

The initial target wake phrase is `Hi Lexi`. The notebook and training pipeline will be tested from a fresh Colab runtime before being described as ready to use.

## 🛠️ Planned Features

- [ ] Google Colab training notebook
- [ ] Environment and dependency checks
- [ ] Robust background-audio preparation
- [ ] Configurable wake phrases
- [ ] Model evaluation and testing
- [ ] Export and deployment instructions
- [ ] Integration example for Lexi

## 🚀 Getting Started

The training notebook is being developed. Setup instructions will be added after the workflow has been tested.

## 🧠 Built With

- Python
- Google Colab
- [openWakeWord](https://github.com/dscripka/openWakeWord)

Custom Wakeword Lab builds on existing open-source tools. Their original authors and licenses will be credited appropriately.

## 🤝 Contributing

Issues, reproducible bug reports, documentation improvements, and tested fixes will be welcome as the project develops.

## 📄 License

This repository is licensed under the MIT License. Third-party dependencies, datasets, and model weights may have separate license terms.

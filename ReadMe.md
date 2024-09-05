# Fast-RAG - RAGs_Updates Branch

Welcome to the `RAGs_Updates` branch of the Fast-RAG repository. This branch focuses on updates and enhancements related to Retrieval-Augmented Generation (RAG) using fast and efficient techniques. The following documentation provides an overview of the branch, its purpose, and how to use it.

## Overview

The `RAGs_Updates` branch is dedicated to the development and refinement of RAG methods. It contains experimental features, optimizations, and improvements that are not yet merged into the `main` branch. This branch may contain cutting-edge developments and may occasionally be unstable as new ideas are tested and validated.

## Key Features

- **Optimized Retrieval Mechanisms:** Improvements to the retrieval process to enhance speed and accuracy.
- **Enhanced Generation Models:** Updates to the generation models used in RAG to produce more coherent and contextually relevant outputs.
- **Custom RAG Implementations:** Custom implementations of various RAG methods tailored for specific use cases and datasets.
- **Integration with Qdrant:** Leveraging Qdrant for efficient vector search and retrieval within the RAG framework.

## Installation

To use the code from the `RAGs_Updates` branch, clone the repository and switch to this branch:

```bash
git clone https://github.com/ab-ark/Fast-RAG.git
cd Fast-RAG
git checkout RAGs_Updates
```

Ensure you have the necessary dependencies installed:
```bash
pip install -r requirements.txt
```

## Usage
The primary scripts and modules are located in the following directories:

- src/: Contains the core implementation of the RAG models and retrieval mechanisms.
- scripts/: Useful scripts for running experiments and tests.
- notebooks/: Jupyter notebooks demonstrating various aspects of the RAGs implemented in this branch.


You can run the main RAG pipeline by executing the following command:
```bash
python src/main.py --config config/rag_config.yaml
```

## Configuration
Configurations for different RAG models and setups are available in the config/ directory. You can modify these configuration files to tailor the RAG process to your specific needs.

## Contributing
Contributions to the RAGs_Updates branch are welcome! If you have ideas, bug fixes, or enhancements, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a Pull Request targeting the RAGs_Updates branch.


## Issues
If you encounter any issues or bugs, please report them using the Issues section of this repository. Specify that the issue pertains to the RAGs_Updates branch.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Thanks to all the contributors and users who have provided feedback and suggestions to improve this branch. Your support is invaluable!



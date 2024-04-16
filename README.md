# Gemini Notebooks
This repository is my collection of Jupyter notebooks for working with Gemini, Google's multimodal AI platform. These notebooks provide examples and tutorials for various tasks, helping you get started with Gemini's functionalities.

## Prerequisites

### Local development
- [Python (version 3.11 or later recommended)](https://www.python.org/downloads/)
- _(You can either use this)_ [Jupyter Notebook](https://jupyter.org/install)
- _(Or this)_ [Visual Studio Code (VSCode)](https://code.visualstudio.com/download)
- [gcloud CLI](https://cloud.google.com/sdk/docs/install)

## Setting Up Jupyter Notebook Development in VSCode

### Install Jupyter Notebook and Python Extension:

1. Open VSCode and navigate to the Extensions tab (Ctrl+Shift+X on Windows/Linux, Cmd+Shift+X on macOS).
Search for "Python" and install the official Python extension by Microsoft.
2. Create a Jupyter Notebook Environment:

```
1. Open the Command Palette (Ctrl+Shift+P on Windows/Linux, Cmd+Shift+P on macOS).
2. Type "Python: Select Interpreter" and press Enter.
3. Choose "Python 3.11.x" if it's available. If not, select "Create Interpreter" and follow the steps to create a new virtual environment with Python 3.
```
3. Install the __"Jupyter Notebook"__ extension for VSCode (search for it in the Extensions tab) for enhanced features like syntax highlighting and code completion.

### Using the Notebooks
This repository contains various Jupyter notebooks showcasing Gemini functionalities. Feel free to explore them and adapt them to your specific needs.

### Open a notebook file (.ipynb) within VSCode.
Click the "Run" button (green triangle) in the top toolbar or press Shift+Enter to execute the code cell by cell.
The output will be displayed below each code cell.

I hope this helps you get started with Jupyter Notebooks with Gemini!

## Troubleshooting
1. if you encounter an authentication error when running the cells in the notebook, go to __Google Cloud Platform__ > __Vertex AI__ > __Dashboard__, and click on __Enable All Recommended APIs__. Then, re-run the failed cell.

## Related Repositories

[GCP Generative AI](https://github.com/GoogleCloudPlatform/generative-ai/) - Great collection of informative docs and notebooks from GCP
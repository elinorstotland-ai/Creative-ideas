# Creative Ideas Notebook

This beginner-friendly Google Colab notebook asks for an everyday object and uses the OpenAI Responses API to suggest **one unusual, practical use** for it.

## Open it in Google Colab

1. Upload creative_ideas.ipynb to Google Drive, or open the notebook from your repository in Colab.
2. Run the cells from top to bottom.
3. When prompted, enter your OpenAI API key. The notebook uses getpass so the key is not shown while you type.
4. Enter an everyday object and read the suggested use.

The first setup cell installs or updates the openai Python SDK. The key is entered at runtime and is not included in the notebook source. Avoid saving a copy of the notebook with outputs that contain sensitive information.

The notebook uses the model gpt-6-luna through the Responses API. API access and model availability depend on your OpenAI account.

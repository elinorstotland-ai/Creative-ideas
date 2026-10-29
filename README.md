# Creative Ideas Notebook

This beginner-friendly Google Colab notebook suggests **three distinct, unusual, practical uses** for an everyday object. It uses the OpenAI Responses API with the gpt-6-luna model.

## Use the notebook

1. Upload creative_ideas.ipynb to Google Drive and open it in Google Colab.
2. Run the cells from top to bottom. The setup cell installs the OpenAI Python SDK.
3. Enter your OpenAI API key when prompted. getpass hides the key as you type; it is not hardcoded or printed by the notebook.
4. Enter an everyday object. The notebook makes one API request and prints a numbered list of exactly three ideas.
5. Enter another object to continue, or type exit to see the goodbye message and stop.

If you submit an empty object name, the notebook asks again without making an API request.

API access and model availability depend on your OpenAI account. Do not save a copy of the notebook with outputs that contain sensitive information.

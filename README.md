# Google Docs Meeting Notes Formatter

This project converts markdown-formatted meeting notes into a well-formatted Google Doc using Python and the Google Docs API.

## Features
- Converts Markdown headings to Google Docs headings
- Maintains nested bullet points
- Converts markdown checkboxes into Google Docs checkboxes

## Setup Instructions
1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Install dependencies:
   ```python
   !pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client markdown2

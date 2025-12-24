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
   ```
## Dependencies
- google-auth
- google-auth-oauthlib
- google-auth-httplib2
- google-api-python-client
- markdown2

## How to Run
1. Make a copy of the notebook in Google Drive or download it locally.
2. Open it in Google Colab.
3. Run all code cells.
4. The script will create a Google Doc and provide a link to access it.

## Notes
- Ensure your Google account has permission to create Google Docs.
- The notebook preserves the original markdown formatting.
- All headings, bullets, and checkboxes are converted properly.

## Repository Link
[Your GitHub Repository](https://github.com/HruthikG-hub/google-docs-meeting-notes)

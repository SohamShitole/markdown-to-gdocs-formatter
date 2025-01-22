# Project: Markdown to Google Docs Formatter

## Description
A simple script that reads a Markdown file (or string), parses it, and creates a new Google Doc with properly formatted headings, bullet lists, checkboxes, mentions, and footer text.

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/example/markdown-to-gdocs-formatter.git
   cd markdown-to-gdocs-formatter
   ```

2. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/drive/1xJD8r93r9fl574Wo_LwYBnlBEk-bv6bZ#scrollTo=cnIO5wzDviHg).
   - Upload the `markdown_to_gdocs.ipynb` notebook or open it from GitHub directly.

3. **Enable the Google Docs API**:
   - Go to your [Google Cloud Console](https://console.cloud.google.com).
   - Create a new project (or use an existing one).
   - Enable the **Google Docs API** for that project.
   - Set up **OAuth credentials** (if not done already).

4. **Authentication**:
   - When you run the notebook, use the Colab prompt to authenticate your Google account.
   - Ensure the account you use has access to create Google Docs and has the Docs API enabled.

---

## Required Dependencies

- `google-api-python-client`
- `google-auth`
- `google-auth-oauthlib`
- `google-auth-httplib2`

In Colab, you can install these via:

```python
!pip install --upgrade google-api-python-client google-auth google-auth-oauthlib google-auth-httplib2
```

---

## How to Run

1. Open the notebook `markdown_to_gdocs.ipynb` in Colab.
2. Run all cells in order.  
   The script will:
   - **Authenticate** with your Google account.
   - **Parse** the Markdown content (you may store it as a string or read from `example_markdown.md`).
   - **Create** a new Google Doc with the specified formatting (headings, bullets, checkboxes, etc.).
   - Print the **new document ID** and a **link** to the doc.

---

# Google Form Autofiller

A simple Python script that automatically fills out Google Forms using Playwright and the OpenAI API.

It opens a form in your browser, reads the questions, uses GPT to generate short answers, fills them in, and submits the form.  
Built mostly for fun and to experiment with browser automation.

---

## 🧰 Requirements

- Python 3.9 or newer  
- [Playwright](https://playwright.dev/python/)  
- [OpenAI Python SDK](https://pypi.org/project/openai/)  
- OpenAI API key (from https://platform.openai.com)

Install dependencies:

```bash
pip install playwright openai
playwright install chromium

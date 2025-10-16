# web-scrapper-using-ai
 AI Web Scraper

An AI-powered web scraping tool that uses Selenium to extract webpage content and LLMs (like LLaMA 3 via LangChain) to intelligently parse and extract specific information from the DOM.

Built with Streamlit, the app provides a user-friendly interface to:

Scrape a website

View and clean the body content

Ask questions or request structured data from the content using natural language

 Features

1. Scrape website content using a browser automation (via Selenium)

2. Automatically solve captchas (ScrapingBrowser integration)

3. Clean and extract useful content from HTML

4. Ask questions or extract structured data using LLM

5. Streamlit-powered user interface

🛠️ Requirements

Python 3.9+

Ollama installed locally (for LLM usage) OR access to a compatible language model via LangChain

.env file with your scraping browser connection string:

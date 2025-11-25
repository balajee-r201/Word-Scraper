# Word-Scraper
A simple Python application that lets you enter a word and instantly fetch its meaning from Merriam-Webster.
Built using Tkinter for the GUI and BeautifulSoup for HTML parsing.

# How It Works

The GUI collects the input word.

The scraper builds the Merriam-Webster URL.

BeautifulSoup parses the HTML and extracts definition blocks.

The meaning is sent back and displayed inside the Tkinter window.

# Dependencies
- tkinter
- pillow
- requests
- beautifulsoup4
- re
- os
- sys

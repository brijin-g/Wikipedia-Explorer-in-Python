🧠 Wikipedia Explorer – Python Tkinter App
A lightweight GUI application built using Python and Tkinter that allows users to search for topics and view summaries directly from Wikipedia.

📌 Features
Simple, user-friendly interface

Real-time search from Wikipedia

Displays a summary of the entered topic

Error handling for invalid or missing pages

🧰 Technologies Used
Language: Python

Libraries:

wikipedia – to fetch data from Wikipedia

tkinter – to create the graphical user interface

▶️ How to Run
1. Install Required Library
Make sure you have Python installed. Then run:

bash
Copy
Edit
pip install wikipedia
2. Run the Script
Save the code as wikipedia_explorer.py, then run:

bash
Copy
Edit
python wikipedia_explorer.py
🧠 How It Works
Users enter a topic in the input field.

The app fetches a summary using the wikipedia.summary() function.

The summary is displayed in the text area.

If the topic is not found, an error message is shown.

📄 File Structure
wikipedia_explorer.py – Main script containing GUI and logic.

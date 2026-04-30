🤖 Python Voice Assistant
A beginner-friendly Python CLI assistant that responds to text commands — no extra libraries needed!

Features

👋 Greetings and friendly responses
⏰ Current time and date
😄 Random jokes
🌐 Web search — opens Google in your browser
🧮 Basic calculator (supports + - * /)
❓ Built-in help menu
👋 Graceful exit with bye or Ctrl+C


Requirements

Python 3.6+
No third-party libraries — uses only the Python standard library (datetime, webbrowser, random)


Getting Started
bash# Clone or download the project
git clone https://github.com/your-username/python-voice-assistant.git
cd python-voice-assistant

# Run the app
python voice_assistant.py

Usage
Type a command at the prompt and press Enter. Type help to see all available commands.
Available commands:
CommandExampleWhat it doeshello / hiheyGreets you backtimetimeShows the current timedate / todaywhat day is itShows today's datejoketell me a jokeTells a random jokesearch <topic>search Python tutorialsOpens a Google searchcalculate <math>calculate 10 * 5Evaluates a math expressionaboutwho are youDescribes the assistanthelphelpShows the full command listbye / exitgoodbyeQuits the program
Example session:
You: hi
Assistant: Hello! How can I help you today? 😊

You: calculate 15 * 4 + 2
Assistant: 🧮 Result: 15 * 4 + 2 = 62

You: search Python for beginners
Assistant: 🌐 Opening Google search for: 'Python for beginners'

You: bye
Assistant: 👋 Goodbye! Have a great day!

Project Structure
python-voice-assistant/
├── voice_assistant.py   # Main application
└── README.md

Limitations

Text-based only — no actual voice/speech recognition
Calculator uses eval() restricted to safe characters (0-9 + - * / . ())
Web search requires a default browser configured on your system


License
MIT License — free to use, modify, and distribute.

﻿# Panda
Helping Panda is a voice-controlled assistance application developed using Python. The application leverages speech recognition for converting spoken commands into actions and text-to-speech for providing feedback to the user. The key features include:

    Voice Command Recognition: The app listens continuously for specific commands such as "play," "open," "google search," and "exit."
    Text-to-Speech Feedback: Provides audible responses to the user using pyttsx3.
    Task Handling:
        Play music via the mu.songs function.
        Open apps using the app.apps function.
        Google search through a browser.
    Multithreading: Ensures the voice recognition and GUI operate simultaneously without freezing.
    GUI Interface: Displays a simple interface with a background image and buttons to interact with the system.
    Graceful Exit: The app terminates when "exit" or "destroy" is spoken.

The project is designed to provide an intuitive, hands-free experience, allowing users to interact with the system through voice commands.


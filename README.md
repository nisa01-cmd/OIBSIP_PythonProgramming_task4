# 🗣️ Voice Assistant using Python

## 📌 Objective
This project is aimed at developing a basic Voice Assistant using Python that can perform simple tasks based on voice commands. The assistant can respond to greetings, tell the current time or date, and search the web based on user queries. It also provides audio feedback to make interactions more natural.

---

## ⚙️ Tools & Technologies Used
- **Python** – Core language for development
- **speech_recognition** – For recognizing and converting voice to text
- **pyttsx3** – For text-to-speech output
- **pyaudio** – For capturing microphone input
- **datetime** – To fetch and format current date/time
- **webbrowser** – To open search queries in a browser

---

## 🧭 Steps Performed
1. Installed required Python libraries using pip.
2. Set up the speech recognition and text-to-speech engines.
3. Captured voice input through the user's microphone.
4. Converted the voice input to text using the `speech_recognition` library.
5. Processed the recognized text to identify specific commands:
   - "Hello" ➝ Responds with a greeting.
   - "Time" ➝ Speaks the current system time.
   - "Date" ➝ Speaks today’s date.
   - "Search [your query]" ➝ Opens a web browser and searches Google.
6. Used the `pyttsx3` library to provide voice responses for better user interaction.

---

## 🎯 Outcome
- The voice assistant listens to voice commands in real time.
- It can greet the user, tell the current time and date.
- It can search for queries online using a simple voice prompt.
- The assistant responds back with spoken replies, offering a more engaging experience.

---

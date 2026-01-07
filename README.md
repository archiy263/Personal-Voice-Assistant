# Personal-Voice-Assistant
A Python-based personal voice assistant that performs common desktop tasks using voice commands. The assistant uses speech-to-text, rule-based command mapping, and text-to-speech to provide a complete voice interaction experience.

## 🚀 Features

- **Speech-to-Text** using `SpeechRecognition`
- **Rule-Based Command Mapping** (open apps, search web, tell time, etc.)
- **Text-to-Speech** using `gTTS`
- **Robust Error Handling**
- **Hands-Free Desktop Automation**

## 🧠 How It Works

1. Captures user voice  
2. Converts voice to text  
3. Matches command using rule-based logic  
4. Executes corresponding action  
5. Speaks back the response

---

## 🧪 Sample Voice Commands

- Tell me the time  
- Open Google  
- Open YouTube  
- Search machine learning  
- Take screenshot  
- Exit

- ## 🛠️ Installation & Setup

### 1️⃣ Install Required Python Packages

Before running the project, install these dependencies:

```bash
pip install SpeechRecognition gTTS pydub pyautogui sounddevice numpy
```
## 2️⃣ Install FFmpeg

Download FFmpeg from:  
https://www.gyan.dev/ffmpeg/builds/

(Download the **release essentials** `.zip` file)

Extract the downloaded file.

Open the extracted folder and go inside the **`bin`** directory.  
You should see at least these files:

- ffmpeg.exe  
- ffprobe.exe  
- ffplay.exe  

Copy the full path of the **`bin`** folder.

Add this path to your **System Environment Variables → Path**.

Restart your terminal.


## 3️⃣ Run the Assistant

Navigate to the project folder and run:

```bash
python assistant.py
```



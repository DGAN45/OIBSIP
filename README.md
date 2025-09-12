# Python Mini Projects  

This repository contains three beginner-friendly Python projects:  

1. 🎙 Voice Assistant  
2. ⚖ BMI Calculator  
3. 🔐 Password Generator  

---

## 1. 🎙 Voice Assistant (voiceassistant.py)  

A simple voice-controlled assistant that can respond to greetings, tell the time/date, perform Google/YouTube searches, and exit on command.  

### Features  
- Speech recognition using speech_recognition  
- Text-to-speech with pyttsx3  
- Google and YouTube search via pywhatkit  
- Handles greetings, time, date, and exit commands  

### Usage  
```bash
python voiceassistant.py
```

Say commands like:  
- "hello"  
- "time"  
- "date"  
- "search Python programming"  
- "open youtube"  
- "exit"  

---

## 2. ⚖ BMI Calculator (BMI calculator.py)  

A console-based BMI (Body Mass Index) calculator that takes weight and height as input and categorizes the result.  

### Features  
- Input validation (ensures positive numbers)  
- Calculates BMI using the formula:  
  BMI = weight (kg) / (height (m)²)  
- Categorizes BMI into Underweight, Normal, Overweight, Obese  

### Usage  
```bash
python "BMI calculator.py"
```

Example output:  
```
Enter your weight in kilograms (kg): 70
Enter your height in meters (m): 1.75

✅ Your BMI is: 22.86
📊 BMI Category: Normal weight
```

---

## 3. 🔐 Password Generator (Password_Generator.py)  

Generates secure random passwords with options for including digits and symbols.  

### Features  
- User-defined password length  
- Option to include/exclude digits  
- Option to include/exclude symbols  
- Ensures password length ≥ 4  

### Usage  
```bash
python Password_Generator.py
```

Example interaction:  
```
=== Password Generator ===
Enter password length: 12
Include digits? (y/n): y
Include symbols? (y/n): n

Generated Password: aBcXyZtRkLpQ
```

---

## ⚙ Requirements  

Install dependencies before running the projects:  
```bash
pip install speechrecognition pyttsx3 pywhatkit
```

(The BMI Calculator and Password Generator only require Python’s standard library.)  

---


# 🎵 Arduino Happy Birthday Melody

## 📌 About the Project
This project plays a simplified version of the **Happy Birthday song** using an Arduino Uno and a buzzer. It uses different sound frequencies and timing delays to create a recognizable melody.

## 🛠️ Components Used
- Arduino Uno
- Buzzer
- Jumper wires
- USB cable

## 🔌 Circuit Connections
| Buzzer Pin | Arduino Uno |
|---|---|
| Positive (+) | Digital Pin 8 |
| Negative (-) | GND |

## 💻 How It Works
- `tone()` generates a sound at a specified frequency.
- The melody array stores the frequencies of the notes.
- The duration array controls how long each note plays.
- `noTone()` stops the sound between notes.
- `delay()` creates timing gaps to separate the notes.

## 🚀 How to Run
1. Connect the buzzer to Arduino Uno.
2. Open the Arduino IDE.
3. Copy the source code into a new sketch.
4. Select your Arduino board and port.
5. Upload the code and listen to the melody!

## 📚 What I Learned
- Generating different sound frequencies using Arduino C++.
- Using arrays to store musical notes and durations.
- Controlling timing with `delay()`.
- Producing a melody using `tone()` and `noTone()`.

## 🔮 Future Improvements
- Improve the melody's rhythm and accuracy.
- Add push-button controls to start and stop the song.
- Explore ways to control the perceived loudness.

## 👩‍💻 Built With
- Arduino Uno
- Arduino C++
-

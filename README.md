# Yell-Game-Box
The Yell Box is an Arduino-based game where a sound sensor detects when the user makes a loud noise or yells. If the sound level passes a set threshold, the system unlocks a “flag” displayed on an LCD screen, demonstrating real-time sound detection and simple interactive game logic.

<img src="https://github.com/user-attachments/assets/5d2958aa-17da-4fcc-90ed-24f544e14179" width="200"/>
<img src="https://github.com/user-attachments/assets/ed5297a8-6812-4207-b717-78424b615858" width="200"/>
<img src="https://github.com/user-attachments/assets/5252a051-af3c-4930-8f5a-f067675d567e" width="200"/>
<img src="https://github.com/user-attachments/assets/b2f7ba83-b8f2-4dcc-864d-eca759cf9ad7" width="200"/>
<img src="https://github.com/user-attachments/assets/1965a7e7-a658-494b-bc06-1b9ea1a2b6a1" width="200"/>
<img src="https://github.com/user-attachments/assets/ade492e7-15f7-4ec0-8e72-31f087ce6970" width="200"/>


The concept is simple but fun:  
The louder you scream, the more LEDs light up.  
When all LEDs are fully lit, the LCD screen reveals the hidden flag!
This project turns sound into interaction and creates a playful, real-time game experience.
## ⚙️ How It Works
- The microphone sensor detects sound intensity.
- The Arduino reads the analog values.
- A 10-segment LED bar graph visualizes the sound level.
- When the maximum threshold is reached:
  - The LCD I2C displays the hidden flag.
  - A vibration motor activates for feedback.

## 🧰 Components Used
- Arduino Uno  
- KY-038 Microphone Sensor  
- LCD I2C Display  
- 10-segment LED Bar Graph  
- Small vibration motor *(retrieved from a broken PS2 controller 🎮)*  

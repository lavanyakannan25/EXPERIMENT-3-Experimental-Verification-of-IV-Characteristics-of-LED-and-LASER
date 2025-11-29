
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---

## 🧪 PROCEDURE

```
	Refer to the block diagram and make the following connections.
	Keep all switch faults in OFF position.
	Slightly unscrew the cap of LED SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the 1-meter fiber into the cap. Now tighten the cap by screwing it back.
	Slightly unscrew the cap of Photo Diode SFH250V. Do not remove the cap from the connector. Once the cap is loosened, insert the other end of fiber into the cap. Now tighten the cap by screwing it back.
	Keep the jumpers JP1 short for +12v, JP2 towards sine wave, JP3 short for
+12 v & JP4 towards TX1on FCL-01.
	Keep switch SW2 in VI position on FCL-01.
	Connect voltmeter and current meter as per the polarities shown in the block diagram.
	Switch on the power supply.
	Keep the potentiometer P3 in its maximum position (anti-clockwise rotation). P3 is used to control current flowing through the LED.
	Keep the potentiometer P4 in its fully clockwise rotation.P4 is used to control bias voltage of the LED.
	To get the IV characteristics of LED, rotate P3 slowly and measure forward current and corresponding forward voltage. Take number of such readings for various current values and plot IV characteristics graph for the LED.
•	For each reading taken above, find out the power, which is product of I and
V. This is the electrical power supplied to the LED. Data sheets for the LED specify optical power coupled into plastic fiber when forward current was 10 mA as 200 mW. This means that the electrical power at 10 mA current is converted into 200 mW of optical energy. Hence the efficiency of the LED comes out to be approx. 1.15%.
•	With this efficiency assumed, find out optical power coupled into plastic optical fiber for each of the reading. Plot the graph of forward current v/s output optical power of the LED.
•	Similarly measure the current at the detector.
•	Plot the graph of receiver current v/s output optical power of the LED.
•	Perform the above procedure again for all the combinations of Transmitter & Receiver.
 
```

---

## 🔌 CONNECTION DIAGRAM
<img width="908" height="580" alt="image" src="https://github.com/user-attachments/assets/37c75d16-e2e6-43f9-9c13-9e14ae185401" />



---

## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
| 1.5                    |     1.0                 |
| 1.6                    |     2.0                 |
| 1.7                    |     4.0                 |
| 1.8                    |     6.5                 |
| 1.9                    |     9.0                 |
| 2.0                    |     12.0                |
| 2.1                    |      15.0               |
---

## 📈 MODEL GRAPH
<img width="423" height="358" alt="image" src="https://github.com/user-attachments/assets/ff8a5abf-323e-4f3a-ba43-68e545315c75" />
<img width="706" height="888" alt="image" src="https://github.com/user-attachments/assets/5b886ebf-22dd-458e-a815-f1c30d5d59ea" />


---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.

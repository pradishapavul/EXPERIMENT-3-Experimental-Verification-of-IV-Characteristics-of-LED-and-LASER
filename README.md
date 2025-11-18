
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

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM
<img width="1280" height="815" alt="image" src="https://github.com/user-attachments/assets/f7ece961-e9df-42f1-9e10-d6ea7bf4c8bd" />


---

## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
|    1.565               |       0.223             |
|    1.600               |       0.397             |
|    1.640               |       0.728             |
|    1.680               |       1.165             |
|    1.80                |        2.8              |
|    1.86                |        3.8              |
|    2.2                 |         6.2             |
|   2.38                 |        10               |
|     2.42               |        22.4             |
|                        |                         |
                        
---

## 📈 MODEL GRAPH
*(Insert graph of Vf vs If here)*
<img width="992" height="1280" alt="image" src="https://github.com/user-attachments/assets/694fecbf-91c9-4263-ab30-cb8ee4bb0926" />


---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.

# Linear Interpolation (LERP)
---

### Student Information
* **Name:** Muhammad Muzammil Hussain
* **Seat No:** B23110006108
* **Section:** A

---

## 1. Concept
Linear Interpolation (LERP) calculates a value between a start ($A$) and an end ($B$) based on a percentage ($t$).

### Formula:
$$Output = A + (B - A) \times t$$

---

## 2. HCI Principles
* **Visibility of System State:** The output updates instantly as the user moves the slider.
* **Mapping:** Moving the slider left-to-right directly correlates with moving from $A$ to $B$.
* **Immediate Feedback:** Real-time calculation provides a smooth experience without needing a "Calculate" button.

---

## 3. Implementation
* **Dynamic Range:** The slider is constrained between **0.00** and **1.00**.
* **Precision:** Results are rounded to **2 decimal places** using `.toFixed(2)` for clarity.
* **Event Listeners:** `input` triggers ensure the UI stays in sync with all user changes.

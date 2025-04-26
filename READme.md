# Virtual Doctor App (C Language)

This is a simple console-based "Virtual Doctor" application written in C.  
It helps users identify potential health issues based on a few questions about their symptoms.

---

## Features

- Friendly welcome and instructions for the user
- Symptom checking for:
  - Fever
  - Pain in eyes
  - Headache
  - Shortness of breath
  - Difficulty breathing
  - Travel to malaria-prone areas
- Basic color-coded diagnosis:
  - Red messages for warnings
  - Yellow messages for instructions
  - Cyan messages for general information
- Easy "Yes" / "No" inputs (`Y` for Yes, `y` for No)

---

## How It Works

1. The app welcomes the user and explains how to answer questions.
2. It asks about different symptoms one by one.
3. Based on the answers, it suggests:
   - Seasonal Fever
   - Possible Dengue Fever
   - Respiratory Infection
   - Malaria Risk
   - Or no serious illness detected
4. Finally, it advises to consult a doctor if symptoms persist.

---

## How to Run

1. Save the code in a file, for example: `virtual_doctor.c`
2. Open your terminal or command prompt.
3. Compile the code:
gcc virtual_doctor.c -o virtual_doctor
Run the executable:
./virtual_doctor
(Make sure you have GCC installed).

Important Notes
Always enter your answers carefully:

Type Y for Yes

Type y for No

The app is for educational and practice purposes only — it is NOT a substitute for real medical advice.

Proper error-checking for invalid inputs is not implemented in this basic version.

Sample Screenshot

**************HELLO AND WELCOME!!**************
We can help you diagnose any medical concern you may have.

This app will help you identify any symptoms you may be experiencing
and advise you properly for further diagnosis.

Please enter "Y" as YES and "y" as NO as the answers for the following questions

Please enter your age: 22

Do you have fever? Ans: Y

You might have seasonal fever.

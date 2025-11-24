# Digital First Aid Helper  
*A Python-based console application for quick first-aid guidance*

##  Overview  
The **Digital First Aid Helper** is a simple Python console application designed to provide **instant first-aid instructions** for common injuries and emergencies.  
It helps users quickly understand what to do, what NOT to do, and when they should seek medical attention.

This project uses Python, modular code structure, and a JSON database to store first-aid information.

---

##  Features  
-  **Search by injury name** (e.g., burn, cut, fracture)  
-  **Search by symptom/keyword** (e.g., bleeding, swelling)  
-  **Display first aid steps, precautions, and danger signs**  
-  **Save emergency notes/contacts** to a local file  
-  **List all supported injuries**  
-  **Offline support** (all data stored in JSON file)  

---

##  Technologies Used  
- **Python 3.10+**  
- **JSON** (data storage)  
- VS Code (recommended)  

---

##  Project Structure

DigitalFirstAidHelper/
│── main.py
│── first_aid_engine.py
│── injury_database.py
│── utils.py
│── data/
│ └── injuries.json
│── quick_notes.txt (auto-generated)
│── README.md
│── statement.md


---

## 🚀 How to Run the Project

### **1️⃣ Install Python**  
Make sure Python 3.10+ is installed.

Check by typing in terminal:

python --version
or  
py --version

---

### **2️⃣ Open the Project in VS Code**
- Click: **File → Open Folder**
- Select the project folder: `DigitalFirstAidHelper`

---

### **3️⃣ Run the Program**

Open the terminal and type:

py main.py

or

python main.py


---

##  How to Use

### **Option 1 — Search by Injury Name**
Enter things like:
- `burn`
- `cut`
- `sprain`
- `fracture`
- `nosebleed`

You’ll get:
- Description  
- First-aid steps  
- Precautions  
- Danger signs  
- Recommendation  

---

### **Option 2 — Search by Symptoms**
Enter words like:
- `bleeding`
- `swelling`
- `twist`

This finds injuries linked to those symptoms.

---

### **Option 3 — List All Injuries**
Shows all injuries available in `injuries.json`.

---

### **Option 4 — Add a Quick Note**
You can save:
- Emergency contact  
- Hospital address  
- Important reminders  

Saved in: `quick_notes.txt`

---

##  JSON Data Format

Each injury in `injuries.json` follows this structure:

```json
{
  "name": "burn",
  "keywords": ["burn", "burns"],
  "description": "Thermal or chemical burn to skin",
  "first_aid": [...],
  "precautions": [...],
  "danger_signs": [...],
  "recommendation": "..."
}

You can add more injuries easily.

## Future Enhancements

 Flask-based web interface

 GUI version using Tkinter

 Audio-based emergency instructions

 Mobile app integration

 Multi-language support

Disclaimer

This tool provides basic first-aid guidance only and is NOT a replacement for professional medical care.
In severe cases, always contact emergency services.

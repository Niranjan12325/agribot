#  Agriculture Crop Recommendation Chatbot

##  Overview

The Agriculture Crop Recommendation Chatbot is a simple Python-based application that helps users get detailed information about different crops. By entering a crop name, users can receive insights such as best weather conditions, time to harvest, cost estimation, labor requirements, and fertilizer recommendations.

This project demonstrates the use of data handling and basic Natural Language Processing concepts to build an interactive command-line chatbot.

---

##  Features

*  Get crop-specific information instantly
*  Displays best weather conditions for cultivation
*  Provides time required for harvesting
*  Estimates total cost of cultivation
*  Shows number of people required
*  Suggests suitable fertilizers
*  Handles invalid input with suggestions

---

## Tech Stack

* Python
* Pandas

---

##  Project Structure

```
├── agriculture_crop_data.xlsx   # Dataset file
├── chatbot.py                   # Main chatbot script
└── README.md                    # Project documentation
```

---

##  Installation & Setup

###  Clone the repository

```
git clone https://github.com/your-username/agriculture-chatbot.git
cd agriculture-chatbot
```

### 2️⃣ Install dependencies

```
pip install pandas openpyxl
```

### 3️⃣ Run the chatbot

```
python chatbot.py
```

---

##  Usage

* Run the script
* Enter a crop name (e.g., rice, wheat, maize)
* Get detailed crop information instantly
* Type `exit` to stop the chatbot

---

##  Example

```
Enter crop name: rice

 Crop Details:

Crop: Rice
Best Weather: Warm and humid
Time to Harvest: 3-6 months
Total Cost: ₹20000 per acre
People Required: 5-10
Fertilizer: Nitrogen-rich fertilizer
```

---

##  Future Improvements

* Add NLP using libraries like NLTK or spaCy
* Convert into a web application using Django
* Add voice input/output
* Integrate real-time weather API
* Store user preferences for personalization

---

##  Learning Outcomes

* Data handling using Pandas
* File operations (CSV/Excel)
* Basic chatbot logic
* User input handling
* Building CLI-based applications

---

##  License

This project is for educational purposes.

---

##  Acknowledgment

This project was developed as part of learning Python and building real-world applications for placements.

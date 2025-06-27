# 🍎 Food-Product-Scanner — Nutriscan

**Nutriscan** is your ultimate health companion.  
Scan barcodes or enter food names to get **instant calorie**, **ingredient**, and **health insights**. Visualize nutritional values with **interactive charts** and get recommendations on how to burn calories through activities like **jogging**, **yoga**, and more.

---

## ✅ Features

- 📷 Real-time barcode scanning using **Quagga.js**
- 📝 Manual food name entry supported
- 🔍 Fetches product name and details using **FoodFacts API**
- 🧮 Retrieves nutritional data via **Nutrition API (API Ninjas)**
- 📊 Displays nutritional content in **bar charts**
- 🧘‍♀️ Suggests calorie-burning activities based on food
- 💡 Easy-to-use UI for smarter food decisions

---

## 🛠️ Requirement Specification

### 🔹 Frontend Development

- **Languages:**
  - HTML5 — For structuring web pages
  - CSS3 — For modern and responsive design
  - JavaScript — For interactivity and barcode scanning

- **Library:**
  - `Quagga.js` — A lightweight, open-source barcode scanning library for modern browsers

### 🔹 Backend Development

- **Framework:**
  - `Django` (Python) — A robust and scalable web framework

- **Libraries:**
  - `requests` — For making API calls
  - `mathfilter` — For template-level mathematical calculations
  - `static loader` — For managing static files
  - `humanizer` — For formatting numbers and dates in a readable way

### 🔹 APIs Used

- **FoodFacts API**
  - Fetches food product details based on barcode
  
- **Nutrition API (API Ninjas)**
  - Provides calorie, macronutrient, and ingredient breakdown per 100 grams

### 🔹 Data Visualization

- **Chart.js** — Used to create interactive bar charts of nutrient breakdown

---

## ▶️ How to Run This Project

### 📦 Step-by-Step Setup
✅ Option 1: Clone the Repository 
git clone https://github.com/sadath1913/Food-Product-Scanner---Nutriscan.git
cd Food-Product-Scanner---Nutriscan
## or Download as ZIP
    Go to the GitHub repository page.
    Click on the green Code button.
    Select Download ZIP.
    Extract the ZIP file on your system.
    Open the project folder in VS Code or any IDE.
**(or)Directly Download Zip file from upload section**
    
**After Saving this original folder then Follow Below Instructions**

1. **Create a new project in VS Code**  
2. **Install Required Dependencies**  
   ```bash
   pip install django
   pip install requests
   pip install django-mathfilters
3. ****Start the Project**
   django-admin startproject foodie .
4. **Create a New App**
    -django-admin startapp counter
5. **Project Structure Setup**
  - Create templates/ inside the counter app
  - Add home.html file inside templates/ folder
  - Create urls.py inside the counter app
  - Update the following files by copying from the original working project:
     - home.html
     - urls.py (inside foodie project folder)
     - views.py
     - settings.py
6. **Static Files**
  - Copy static/ folder from original project into both:
     - foodie/
     - counter/
7. **Collect Static Files**
  - python manage.py collectstatic
8. **Run the Server**
  - python manage.py runserver
9. **Launch App**
  - Open the generated HTTP link in your browser.

📸 Screenshots
[Home Page](Screenshots/pic1.png)
[ Page 1 ](Screenshots/pic2.png)
[ Page 2 ](Screenshots/pic3.png)
[ Page 3](Screenshots/pic4.png)

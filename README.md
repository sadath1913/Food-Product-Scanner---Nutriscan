# Food-Product-Scanner---Nutriscan
Nutriscan is your ultimate health companion. Scan barcodes or enter food names to get instant calorie, ingredient, and health insights. Visualize nutrition with intuitive charts. Learn how to burn calories through activities like jogging and yoga. Empower your health journey with smarter food choices.
**#Requirement Specification **
** Frontend Development** 
• Languages: 
o HTML5: To structure the web pages. 
o CSS3: For styling and creating an intuitive user interface. 
o JavaScript: For interactive functionalities and using Quagga.js for barcode scanning. 
• Library: Quagga.js 
Quagga.js is a lightweight and open-source barcode scanner library designed to work with modern browsers. It enables real-time barcode detection and decoding directly
through the browser.
**Backend** **Development** 
• Framework: Django (Python-based web framework) 
Django provides a robust foundation for building scalable web applications with minimal effort in configuration. 
• Libraries: 
o requests: For API calls to fetch data from FoodFacts API and Nutrition API. 
o mathfilter: For performing calculations in Django templates. 
o static loader: To manage and serve static files efficiently. 
o humanizer: To improve readability of data by formatting numbers and dates.
**APIs** 
• FoodFacts API 
o Purpose: Retrieve product details like product names, barcodes, and descriptions.
Nutrition API (API Ninjas) 
o Purpose: Fetch detailed nutritional information, including calorie content, ingredients, and values per 100 grams. 
o Integration: Allows the application to provide health insights and determine food quality. 
**Data** **Visualization** 
• Chart.js 
o Purpose: To create bar charts for visualizing nutritional values like protein, fat, carbohydrates, and vitamins. 
**Steps to Execute:**
1. Create new Project in Vscode
2. Install the Required Dependencies
3. Open New Terminal and Execute this commands
    pip install django
    pip install requests
    pip install django-mathfilters
4. Now Start Creating project named foodie using command
    ( django-admin startproject foodie . ) #At the end dot is compulsory otherwise foodie project created as subfolder and it will not run
5. Create and Startapp named as counter
    django-admin startapp counter
6. create new folder  template in counter > create File named home.html in template and copy the data from original file
7. create new file urls.py in counter and copy data from original file urls.py
8. follow same procedure for settings.py, views.py and (urls.py (Foodie Folder))#Copy data from original file paste it in New file
9. copy static files folder in foodie and counter both folder
  **Note:** Arrange the Files same as original file in newly created folder, Dont run original folder you should need to create new projeect and new app and copy data same as original files.
10. now Collectstatic files by executing this Command
    python manage.py collectstatic
11. After Making all changes Now time to Execute 
    python manage.py runserver
12. After Running serverr you will get a http link copy it and open i ur Browser. 

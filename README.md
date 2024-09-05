# HAIRKRAFT
A personalized web app suggesting haircare products based on user preferences.

## Table of Contents
* Project Overview
* Features
* Tech Stack
* Installation
* Usage
* Demo
* Database
* Conclusion
  
## Project Overview
HAIRKRAFT is a web-based application that recommends personalized haircare products to users based on their preferences and needs. Users input their hair type, concerns, and goals, and the system suggests suitable products from a curated database.

## Features
* Personalized product recommendations
* User-friendly interface for inputting haircare preferences
* Dynamic product display based on MySQL queries
* Frontend built with HTML/CSS/JavaScript
* Backend powered by Python and MySQL
  
## Tech Stack
**Backend**: Python

**Frontend**: HTML, CSS, JavaScript

**Database**: MySQL

**Other**: SQL for database management

## Installation
1. **Clone the repository**:
   
     git clone https://github.com/fazilahd/HAIRKRAFT.git

2. **Set up the database**:

* Import the hc.sql file into MySQL.
 
  mysql -u your_user -p your_database < hc.sql

3. **Install dependencies**: Ensure that you have Python and MySQL installed, then run:

     pip install -r requirements.txt

4. **Run the application**: Start the server using:

     python main.py
   
## Usage
1. Visit http://localhost:5000 in your browser.
2. Enter your hair type, hair concerns, and preferences.
3. View the personalized product recommendations generated by the system.
   
## Demo

Watch the Video Demo:

## Database
The MySQL database (hc.sql) stores:

* Product details (name, type, ingredients, price)
* User preferences and hair types
* Recommendation history
* To customize or update the product database, import hc.sql and modify it as needed.

## Conclusion
HAIRKRAFT offers a comprehensive and personalized solution for haircare product recommendations by leveraging user-specific preferences and habits. By analyzing various aspects such as hair condition, volume, scalp texture, and lifestyle factors, HAIRKRAFT delivers tailored suggestions that cater to individual needs.

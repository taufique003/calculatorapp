# calculatorapp
Flask Calculator App
This is a simple calculator web application built using Flask, a lightweight web framework for Python. The calculator app allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division on two numbers.

Features
Addition: Add two numbers together.
Subtraction: Subtract one number from another.
Multiplication: Multiply two numbers together.
Division: Divide one number by another (division by zero is handled).
Requirements
Python 3.x
Flask
Installation
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/flask-calculator-app.git
Navigate to the project directory:

bash
Copy code
cd flask-calculator-app
Install dependencies using pip:

bash
Copy code
pip install -r requirements.txt
Usage
Run the Flask application:

bash
Copy code
python calculator.py
Open your web browser and navigate to http://localhost:8080.

Use the calculator interface to input two numbers and select an operation.

Click the "Calculate" button to see the result.

Docker
Alternatively, you can run the calculator app in a Docker container. Make sure you have Docker installed on your machine.

Build the Docker image:

bash
Copy code
docker build -t calculator-app .
Run the Docker container:

bash
Copy code
docker run -p 8080:8080 calculator-app
Open your web browser and navigate to http://localhost:8080 to access the calculator app.

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

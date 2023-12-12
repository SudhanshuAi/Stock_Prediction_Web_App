Introduction :
Predicting stock prices is a cumbersome task as it does not follow any specific pattern. Changes in the stock prices are purely based on supply and demand during a period of time. In order to learn the specific characteristics of a stock price, we can use algorithm to identify these patterns through machine learning. One of the most well-known networks for series forecasting is LSTM (long short-term memory) which is a Recurrent Neural Network (RNN) that is able to remember information over a long period of time, thus making them extremely useful for predicting stock prices. RNNs are well-suited to time series data and they are able to process the data step-by-step, maintaining an internal state where they cache the information they have seen so far in a summarised version. The successful prediction of a stock's future price could yield a significant profit.

Aim :
To predict stock prices according to real-time data values fetched from API.

Objective :
The main objective of this project is to develop a web application that can predict stock price based on real-time data.

Project Scope :
The project has a wide scope, as it is not intended to a particular organization. This project is going to develop generic software, which can be applied by any businesses organization. Moreover it provides facility to its users. Also the software is going to provide a huge amount of summary data.




Project Installation:

STEP 1: Clone the repository from GitHub.

  git clone https://github.com/Kumar-laxmi/Stock-Prediction-System-Application.git
  
STEP 2: Change the directory to the repository.

  cd Stock-Prediction-System-Application
  
STEP 3: Create a virtual environment (For Windows)

  python -m venv virtualenv
  (For MacOS and Linux)

  python3 -m venv virtualenv
  
STEP 4: Activate the virtual environment. (For Windows)

  virtualenv\Scripts\activate
  (For MacOS and Linux)

  source virtualenv/bin/activate
  
STEP 5: Install the dependencies.

  pip install -r requirements.txt
  
STEP 6: Migrate the Django project. (For Windows)

  python manage.py migrate
  (For MacOS and Linux)

  python3 manage.py migrate
  
STEP 7: Run the application. (For Windows)

  python manage.py runserver
  (For MacOS and Linux)

  python3 manage.py runserver

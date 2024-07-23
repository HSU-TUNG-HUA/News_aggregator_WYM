# My Project

## Description
This is a flask application used to collect news from plenty of news agencies like BBC, NHK and CBS, convering mutitidinous contents such as SDGs, politics and economy.

In addition, this application boosts AI powered summary function by leveraging facebook/bart-large-cnn and tsmatz/mt5_summarize_japanese from Hugging face, aimming to help users to balance staying informed about global events with their daily responsibilities and interests.

On top of that, comments have been set up this application, making it possible for users to enjoy futher discussion with others users after the app being deployed to GCP.

## Installation

1. Make sure you have "VS cdoe" installed. You can download it from [here](https://code.visualstudio.com).
2. Open your "VS cdoe". This README assumes you are using Visual Studio Code (VS Code). Open the terminal in VS Code by clicking on "Terminal" in the menu and selecting "New Terminal".
3. Clone this repository: input `git clone https://github.com/HSU-TUNG-HUA/News_aggregator_WYM.git` in your terminal.
4. Navigate to the project directory: input `cd News_aggregator_WYM` in your terminal.
5. Set up a new virtual environment: input `python3 -m venv env` in your terminal.
6. Activate the virtual environment: input `source env/bin/activate` in your terminal.
7. Install your dependencies: input `pip3 install -r requirements.txt` in your terminal.

## Usage
To run the application locall, open the terminal and follow the instructions :

1. Navigate to the project directory if you haven't already: `cd News_aggregator_WYM`
2. Run the application: `python app.py`

The application will start, and you can access it at `http://localhost:5000` in your web browser.
Now you can enjoy the website !

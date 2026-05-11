AstanaGoGo Bot
AstanaGoGo Bot is a Telegram bot created in Python that helps users find entertainment places in Astana based on category, interests and budget.
The bot provides recommendations for:
* Cafes
* Restaurants
* Cinema
* Bowling
* Karaoke
* Coworking spaces
* Museums
* Exhibitions
* Parks
* Oceanarium
Users interact with the bot using Telegram inline buttons.
Features
* Interactive Telegram interface
* Category selection
* Budget-based recommendations
* Cafe recommendations by visit purpose
* Restaurant recommendations by cuisine
* Ticket price calculation for museums and oceanarium
* Information about places:
o address
o working hours
o average check
o ratings
o descriptions
* Main menu navigation button
* Organized and modular Python code
Technologies Used
* Python
* python-telegram-bot
* Google Colab
* InlineKeyboardButtons
* Dictionaries and lists for data storage
Project Structure
* AstanaGoGo_bot.ipynb - main Telegram bot code
* requirements.txt - required libraries
* README.md - project documentation

Installation and Setup
1. Clone or Download the Project
Download the repository or clone it from GitHub.

2. Install Required Libraries
Install dependencies using:
pip install -r requirements.txt
Or manually install:
pip install python-telegram-bot nest_asyncio pandas

Creating a Telegram Bot
1. Open Telegram
Search for:
BotFather

2. Create a New Bot
Use the command:
/newbot
Follow the instructions from BotFather.

3. Copy Your Bot Token
After creating the bot, BotFather will provide a token.
Example:
123456789:AAExampleBotToken

Running the Bot
1. Open the Notebook
Open:
AstanaGoGo_bot.ipynb
in:
Jupyter Notebook
or
Google Colab

2. Insert Your Token
Find this line:
TOKEN = "YOUR_BOT_TOKEN"
Replace it with your real Telegram bot token.
Example:
TOKEN = "123456789:AAExampleBotToken"

3. Run All Cells
Run all notebook cells from top to bottom.
If the bot starts successfully, Telegram will show the bot online.

How to Use the Bot
1. Open Telegram
2. Find your bot
3. Press /start
4. Choose a category
5. Select preferences and budget
6. Receive recommendations and information

Example Functionalities
* Cafe selection by purpose and budget
* Restaurant recommendations by cuisine
* Museum ticket calculation
* Oceanarium family ticket calculation
* Navigation back to main menu

Team Project
This project was created as a Python team project focused on:
* Telegram bot development
* User interaction
* Python functions and logic
* Modular programming
* GitHub collaboration

Requirements
Python version:
* Python 3.10+
Libraries:
* python-telegram-bot
* pandas
* nest_asyncio

Future Improvements
Possible future improvements:
* Google Maps integration
* Real-time cafe ratings
* Database connection
* AI-based recommendations
* Multi-language support


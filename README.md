# Insta-Info-Bot

> [!WARNING]
> This project is discontinued. Please use the latest [InstaGhost](https://github.com/Anon4You/InstaGhost) tool instead.

Insta-Info-Bot is a Telegram bot that allows users to fetch detailed information about any public Instagram profile. By simply sending an Instagram username, users can receive a variety of profile details.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Created by](#created-by)

## Features

- Fetches and displays:
  - Username
  - Full Name
  - Biography
  - Website
  - Number of Posts
  - Followers Count
  - Following Count
  - Instagram Numeric ID
  - Facebook Mention ID (if available)
  - Private Account Status
- Sends the profile picture of the user.
- Credit to the creator is included in the response.

## Requirements

- [Python 3.x](https://www.python.org/downloads/)
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [Instaloader](https://instaloader.github.io/)
- [Requests](https://docs.python-requests.org/en/latest/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Anon4You/Insta-Info-Bot.git
   cd Insta-Info-Bot
   ```

2. Install the required packages:

   ```bash
   pip install python-telegram-bot instaloader requests
   ```

3. Create a `token.txt` file in the project directory and add your Telegram bot token in it.

4. Run the bot:

   ```bash
   python bot.py
   ```

## Usage

1. Start a chat with your bot on Telegram.
2. Send the `/start` or `/help` command to receive a welcome message.
3. Send any public Instagram username to fetch the profile information.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [Instaloader](https://instaloader.github.io/) for providing a simple way to fetch Instagram profile data.
- [Telegram Bot API](https://core.telegram.org/bots/api) for enabling bot functionalities.

## Created by

* [Alienkrishn](https://t.me/Alienkrishn)

---

Feel free to reach check out my other repositories

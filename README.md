# Random Dog Telegram Bot

This is a Telegram bot named "Random Dog" that provides random dog images to users upon request.

## Features

- Provides an interactive interface for users to request images.

## Technologies Used

- python
- python-telegram-bot==13.15
- requests
- python-dotenv

## Project structure

```
# main folder
📦 random-dog
   # setup
 ┣ 📂 venv
 ┃  ┗ ... (virtual environment files)
 ┣ 📜 .gitignore
 ┣ 📜 .env
 ┣ 📜 .env.sample
 ┣ 📜 requirements.txt
 ┣ 📜 README.md
   # source
 ┣ 📜 bot.py
 ┣ 📜 config.py
 ┣ 📜 dogs.py
 ┗ 📜 handlers.py
```

## Setup

1. Clone this repository to your local machine.
2. Install the required dependencies using pip:
   ```
   pip install python-telegram-bot requests
   ```
3. Create a new Telegram bot and obtain the bot token from the [BotFather](https://core.telegram.org/bots#6-botfather).
4. Replace the placeholder token in the `config.py` file with your actual bot token.
5. Run the bot using the following command:
   ```
   python bot.py
   ```

## Usage

1. Start the bot by searching for it in Telegram and clicking on "Start".
2. Use the `/dog` command to request a random dog image.
3. Enjoy the adorable dog pictures!

## Contribution

### How to Contribute

1. Fork the repository to your GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch for your contribution:
   ```
   git checkout -b feature/your-feature-name
   ```
4. Make your changes and ensure they adhere to the coding standards.
5. Test your changes thoroughly.
6. Commit your changes with descriptive commit messages:
   ```
   git commit -m "Add feature: your feature description"
   ```
7. Push your changes to your forked repository:
   ```
   git push origin feature/your-feature-name
   ```
8. Create a pull request (PR) from your forked repository to the main repository.
9. Describe your changes in detail and explain why they are necessary.
10. Wait for the maintainers to review your PR. Make any requested changes if necessary.

### Things to Contribute

- Bug fixes
- New features
- Improvements to existing features
- Documentation improvements
- Code refactoring

### Code Guidelines

- Follow PEP 8 style guide for Python code.
- Write clear and descriptive commit messages.
- Keep the codebase clean and maintainable.

# Discord-Twitter Bot

This Python program connects a Discord bot and a Twitter bot. The Discord bot listens for new messages in specific Discord channels and then posts them on Twitter as a tweet.

## Getting Started

### Prerequisites

Before running this program, you need to have the following:

- A Discord account and access to the Discord Developer Portal
- A Twitter account and access to the Twitter Developer Portal
- Python 3.7 or later installed

### Installing

1. Clone this repository to your local machine.
2. Install the required Python packages by running the following command in your terminal:

    ```
    pip install -r requirements.txt
    ```

3. Set up your environment variables by creating a `.env` file in the root directory of the project and adding your Discord and Twitter API keys. The `.env` file should look like this:

    ```
    discord_token=YOUR_DISCORD_TOKEN_HERE
    consumer_key1=YOUR_TWITTER_CONSUMER_KEY_HERE
    consumer_secret1=YOUR_TWITTER_CONSUMER_SECRET_HERE
    access_token1=YOUR_TWITTER_ACCESS_TOKEN_HERE
    access_token_secret1=YOUR_TWITTER_ACCESS_TOKEN_SECRET_HERE
    ```

## Usage

1. Run the program by executing the following command in your terminal:

    ```
    python main.py
    ```

2. The Discord bot will listen for messages in the specific channels that are defined in the `discord_channel_id` variables in the `main.py` file.

3. When a new message is sent in one of the specified channels, the program will automatically post it as a tweet on Twitter.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

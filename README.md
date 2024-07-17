# Discord Bot for Tebex Coupon Generation

This is a Discord bot that generates Tebex coupons. It uses the discord.py library and the Tebex API.

## Features

- **Slash Commands**: The bot uses slash commands for easy interaction.
- **Coupon Generation**: The bot can generate Tebex coupons with a specific value.
- **Permission Control**: Only users with specific IDs are allowed to use the coupon generation command.

## Setup

1. Clone this repository.
2. Install the required Python packages using pip:
    ```bash
    pip install discord requests
    ```
3. Replace the `bot_token` and `tebex_secret` in the code with your Discord bot token and Tebex secret key respectively. (https://docs.tebex.io/plugin/authentication)
4. Replace the `allowed_user_ids` with the Discord user IDs that should be allowed to use the command.
5. Replace the `guild_id` with your Discord server's ID.
6. Replace the `currency` with the currency you use in your store.
7. Replace the `hex_color` with the color you wish to use on the left side of the embed. Example below.
8. Replace the `store_link` and `image_link` with the correct link to your store and how your checkout looks (if you wish).
9. Run the bot:
    ```bash
    python main.py
    ```

## Usage

Use the `/generatecoupon` slash command in Discord to generate a new Tebex coupon. The command requires two parameters: `value` (the value of the coupon) and `note` (the note attached to the coupon).

## Note

This bot is designed for a specific use case and might not suit your needs out of the box. Feel free to modify the code to fit your requirements.
All code that needs changing to suit your environment is under "CHANGE THESE" in the code.

## Picture
![image](https://github.com/user-attachments/assets/ec965be9-9ea9-4173-9cd7-8b678926343d)

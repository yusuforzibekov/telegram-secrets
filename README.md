# Telegram Secrets

This project requires the following Telegram secrets to be set:

- `sounds_reset`: This secret is used to reset the notification sounds for incoming calls and messages. To set this secret, follow these steps:
    1. Open Telegram and go to "Settings".
    2. Select "Notifications and Sounds".
    3. Scroll down to the bottom and select "Reset Notification Settings".
    4. A code will appear on the screen. Copy this code and set it as the value for the `sounds_reset` secret.

    ![Reset Notification Settings](images/reset_notification_settings.png)

- `call_incoming`: This secret is used to configure the notification sound for incoming calls. To set this secret, follow these steps:
1. Open Telegram and go to "Settings".
    2. Select "Notifications and Sounds".
    3. Select "Incoming Calls".
    4. Choose the sound you want to use.
    5. A code will appear on the screen. Copy this code and set it as the value for the `call_incoming` secret.

    ![Incoming Calls](images/incoming_calls.png)

- `msg_incoming`: This secret is used to configure the notification sound for incoming messages. To set this secret, follow these steps:
    1. Open Telegram and go to "Settings".
    2. Select "Notifications and Sounds".
    3. Select "Messages".
    4. Choose the sound you want to use.
    5. A code will appear on the screen. Copy this code and set it as the value for the `msg_incoming` secret.

    ![Messages](images/messages.png)

To set these secrets in your GitHub repository, follow these steps:

1. Go to your repository on GitHub and click on "Settings".
2. Select "Secrets" from the left-hand menu.
3. Click on "New repository secret".
4. Enter the name of the secret (e.g. `sounds_reset`) and the value (e.g. the code you copied from Telegram).
5. Click on "Add secret".

Repeat these steps for each of the three secrets (`sounds_reset`, `call_incoming`, and `msg_incoming`). Once you have set these secrets, your Telegram notifications should work correctly in your project.

[![Open Telegram](https://img.shields.io/badge/Open-Telegram-blue?logo=telegram)](https://telegram.org/)
[![GitHub](https://img.shields.io/badge/Open-GitHub-blue?logo=github)](https://github.com/)

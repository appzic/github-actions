# Reusable GitHub Actions

## Actions
### Telegram Send Message

Sends a message to a Telegram chat using a bot.

#### Inputs

- `token`: Telegram bot token (required)
- `chat_id`: Telegram chat ID (required)
- `message`: The message to send (required)

#### Example Usage

```yaml
uses: appzic/github-actions/telegram-send-message@89b399445b62d18c0e2b1fae9502704611dba25c
with:
  token: ${{ secrets.TELEGRAM_BOT_TOKEN }}
  chat_id: ${{ secrets.TELEGRAM_CHAT_ID }}
  message: "Hello from GitHub Actions!"
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details

# Telegram Integration

## Objective

Telegram is used as the primary communication interface for interacting with the OpenClaw AI assistant. It allows users to send requests and receive responses remotely in real time.

---

## Why Telegram

* Easy to set up and use
* Accessible from anywhere
* Real-time communication
* Available on mobile, desktop, and web platforms
* Seamless integration with OpenClaw

---

## Integration Steps

### Step 1: Open Telegram

Launch the Telegram application or access Telegram Web.

### Step 2: Search for BotFather

Search for **BotFather**, the official Telegram bot used to create and manage bots.

### Step 3: Create a New Bot

Run the following command:

```text id="f5v9xq"
/newbot
```

### Step 4: Configure the Bot

Provide the following details when prompted:

* Bot Name
* Unique Bot Username

Example:

```text id="79d2fh"
Bot Name: OpenClaw Assistant
Bot Username: openclaw_assistant_bot
```

### Step 5: Save the Bot Token

After successful creation, BotFather will generate an API token.

```text id="t9x8qm"
123456789:AAxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

Save this token securely, as it will be required during OpenClaw configuration.

### Step 6: Configure OpenClaw

Add the Telegram Bot Token to the OpenClaw configuration file or environment variables according to your setup.

### Step 7: Start the Services

Restart OpenClaw after updating the Telegram configuration.

### Step 8: Test the Bot

Open the newly created bot and send a test message.

```text id="n7y3pk"
Hello
```

If the integration is successful, the AI assistant should process the request and return a response through Telegram.

---

## Verification

* Telegram bot is online.
* Messages are received by OpenClaw.
* Responses are generated successfully.
* Communication between Telegram and the AI assistant is functioning correctly.

---

## Outcome

Telegram is successfully integrated with OpenClaw, providing a simple and remote interface for interacting with the AI cybersecurity assistant.

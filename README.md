# GateDaemon

> Autonomous gatekeeper bot for the OneDevOps Discord server. Filters out alt accounts, auto-assigns roles, and enforces access logic based on account trustworthiness.

---

## ⚙️ Features

- Assigns the `Cleared` role to new members based on account age
- Rejects suspected alt accounts (customizable cutoff)
- Sends DM alerts to denied or approved users
- Logs verification events to a configured channel
- Configuration via `config.yml`
- Fast, minimal, self-contained

---

## 🚀 Setup

1. Clone the repository:
```bash
git clone https://github.com/ephemeral8997/GateDaemon.git
cd GateDaemon
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create your configuration file:
```bash
cp config_template.yml config.yml
```

4. Edit `config.yml` with your bot token, guild ID, role ID, etc.

5. Run the bot:
```bash
python bot.py
```

---

## 🛡 License

This project is licensed under the MIT License.

---

## 👤 Author

Made by ephemeral8997

Custom-coded for the OneDevOps server.

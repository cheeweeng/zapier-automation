# 🏃‍♂️ Strava Motivation Bot

> A Zapier automation that automatically sends my latest Strava activity and a **motivational quote** to my Telegram bot.
> Built entirely using **Zapier** and low-code tools.

---

## 🔁 Workflow Overview

![Zapier Flow](assets/zapier-flow.png)

### 🔹 Trigger: New Athlete Activity (Strava)
Whenever I complete a new activity (e.g. run or ride) on Strava, this Zap is triggered.

### 🔹 Action 1: Webhook GET Request (Motivational Quote API)
Zapier sends a GET request to a quotes API (like [zenquotes.io](https://zenquotes.io) or similar) to retrieve an inspirational quote.

### 🔹 Action 2: Send Message (Telegram)
Combines Strava data and the motivational quote, then sends a formatted message to my Telegram bot.

---

## 📲 Example Telegram Message


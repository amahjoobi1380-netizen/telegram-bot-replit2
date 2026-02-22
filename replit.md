# Telegram Subscription Bot

## Overview
A Telegram bot for selling subscriptions, built with Python using aiogram and aiosqlite. Features include wallet management, subscription plans, referral system, admin panel, and link management.

## Project Architecture
- `main.py` - Main bot logic, handlers, keyboards, and state machines
- `db.py` - SQLite database layer using aiosqlite (local file `bot.db`)

## Tech Stack
- **Language**: Python 3.11
- **Telegram Framework**: aiogram 3.x
- **Database**: SQLite via aiosqlite (file-based, `bot.db`)
- **Config**: python-dotenv for environment variables

## Environment Variables
- `BOT_TOKEN` (required) - Telegram Bot API token
- `ADMIN_IDS` (required) - Comma-separated list of admin Telegram user IDs

## Running
The bot runs as a console workflow via `python main.py`.

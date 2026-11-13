# SocialSync-AI

A lightweight AI-powered social media workflow for planning, drafting, scheduling, and publishing content with a human approval gate.

## Overview

SocialSync-AI helps teams and creators:

- generate social content ideas and draft captions
- organize posts across multiple channels
- review and approve content before publishing
- schedule or trigger publishing workflows
- keep campaign state and assets in one place

## Getting started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the app locally:
   ```bash
   npm start
   ```
3. Open the app in your browser:
   ```text
   http://127.0.0.1:8090
   ```

## Project structure

- `app/` - frontend dashboard and client UI
- `lib/` - core application logic and integrations
- `scripts/` - platform-specific publishing helpers and workflows
- `data/` - local plans, media, and generated content
- `test/` - validation and regression checks

## Notes

This project is designed for local-first use and keeps the publishing process behind an approval step so content is reviewed before it goes live.

## License

MIT
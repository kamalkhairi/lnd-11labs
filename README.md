# ElevenLabs integration page

*Automatically synced with your [v0.app](https://v0.app) deployments*

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/kamal-khairis-projects/v0-eleven-labs-integration-page)
[![Built with v0](https://img.shields.io/badge/Built%20with-v0.app-black?style=for-the-badge)](https://v0.app/chat/lU34J1A0QxG)

## Overview

This repository will stay in sync with your deployed chats on [v0.app](https://v0.app).
Any changes you make to your deployed app will be automatically pushed to this repository from [v0.app](https://v0.app).

## Configuration

### Environment Variables

To configure your ElevenLabs agent, you can set the following environment variable:

- `NEXT_PUBLIC_ELEVENLABS_AGENT_ID` - Your ElevenLabs agent ID (optional)

**Setup:**

1. Copy `.env.example` to `.env.local`:
   ```bash
   cp .env.example .env.local
   ```

2. Add your ElevenLabs agent ID to `.env.local`:
   ```
   NEXT_PUBLIC_ELEVENLABS_AGENT_ID=your_agent_id_here
   ```

3. Find your agent ID in the [ElevenLabs dashboard](https://elevenlabs.io) under Agent Settings.

**Note:** The agent ID can also be entered directly in the UI input field, which will override the environment variable.

## Deployment

Your project is live at:

**[https://vercel.com/kamal-khairis-projects/v0-eleven-labs-integration-page](https://vercel.com/kamal-khairis-projects/v0-eleven-labs-integration-page)**

## Build your app

Continue building your app on:

**[https://v0.app/chat/lU34J1A0QxG](https://v0.app/chat/lU34J1A0QxG)**

## How It Works

1. Create and modify your project using [v0.app](https://v0.app)
2. Deploy your chats from the v0 interface
3. Changes are automatically pushed to this repository
4. Vercel deploys the latest version from this repository
# SIVA

SIVA is a Discord bot platform for managing multi-clan gaming communities. It launches with Destiny 2 support and is designed to expand to additional games such as Warframe.

The platform focuses on real-time activity visibility, Discord-native UI using Components V2, and automation tools that help communities manage members, roles, and engagement directly within Discord.

## Features

- Multi-clan support per Discord server
- Live activity rosters and rankings
- Bungie OAuth account linking
- Automatic role assignment and nickname management
- Clan applications via slash commands
- Activity-based notifications
- Free and Premium tiers
- Optional dedicated bot instances for Premium servers

## Architecture

SIVA uses a split architecture:

- Backend: Python, FastAPI, Bungie API
- Frontend: Node.js, discord.js, Components V2

This design enables scalability, multi-game support, and reduced API and Discord rate limits.

## Tiers

Free tier provides standard branding and slower update intervals.  
Premium tier adds custom branding, faster updates, advanced configuration, and optional dedicated bot instances.

## Status

Early development. Current work focuses on command UX, component structure, backend contracts, and MVP definition.

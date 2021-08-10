---
title: BlitzJS
description: Example Blitz app that connects to a PostgreSQL database
tags:
  - blitz
  - postgresql
  - typescript
  - prisma
---

# Blitz.js Postgres Example

This example is a [Blitz.js](https://blitzjs.com/) app that connects to a
Railway Postgres database.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new?template=https%3A%2F%2Fgithub.com%2Frailwayapp%2Fexamples%2Ftree%2Fmaster%2Fexamples%2Fblitzjs&plugins=postgresql&envs=SESSION_SECRET_KEY&SESSION_SECRET_KEYDesc=%3E+32+character+secret+key)

## ✨ Features

- Blitz.js
- Postgres
- TypeScript

## 💁‍♀️ How to use

- [Create a Railway project with the Postgres plugin](https://dev.new)
- Connect to your Railway project with `railway link`
- Migrate the database `railway run blitz prisma migrate`
- Run the Blitz app `railway run yarn dev`

## 📝 Notes

This example was generated by running `blitz new`. The default SQLite database was swapped out for Postgres by following [this guide](https://blitzjs.com/docs/database-overview#switch-to-postgresql).

Read more about Blitz.js at their [official documentation](https://blitzjs.com/docs/getting-started).

# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b2e4de18723808c875ca93_user:uCMk2%21CxDCunIRnNk0SB2%40W96uM1Diq3@ep-summer-truth-a4qn07cx.us-east-1.aws.neon.tech:5432/AppDB_69b2e4de18723808c875ca93?sslmode=require`

## Web API

**WebApi URL:** https://webapi69b2e4de18723808c875ca93-production.up.railway.app

**Swagger API Tester URL:** https://webapi69b2e4de18723808c875ca93-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.

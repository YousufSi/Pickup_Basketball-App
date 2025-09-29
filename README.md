# Pickup

**Pickup** is a networking app that helps basketball players easily find and join local games. 
Instead of relying on scattered group chats, Pickup provides a streamlined way to create, 
discover, and fill teams for casual basketball sessions.

## Features
- Create or join pickup basketball games in real time
- See player counts and open spots before committing
- Simple interface for organizing full teams or drop-in runs
- Focused on spontaneity — play anytime, without hassle

## Tech Stack
- React / React Native (via Bolt.new)
- Supabase (backend, authentication, database)
- Expo (mobile runtime)

## Run Locally
1. Install Node.js (LTS recommended).
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start development server:
   ```bash
   npm start
   ```

## Environment Variables
This project uses the following environment variables (do not commit `.env`):
- `SUPABASE_URL`
- `SUPABASE_ANON_KEY`

## Project Structure
```
pickup-app/
  App.js
  package.json
  .gitignore
  README.md
  assets/
```

## Purpose
Pickup was built to solve a common community problem: 
the difficulty of quickly finding enough players for a game. 
This project combines clean UI design with backend integration to make organizing basketball games effortless.

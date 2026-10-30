# Focu Flow — Ready to Deploy on Vercel

Focu Flow is a study companion that organizes subjects, daily tasks, Pomodoro focus intervals, and learning progress.

## Project Structure
- `index.html`: Marketing and landing page explaining the benefits of Focu Flow with direct links to the application.
- `app.html`: The complete, interactive study planner application (Planner, Pomodoro Focus Timer, Subjects, Resource Library, and 7-day Analytics).
- `vercel.json`: Zero-config routing for clean URLs (`/` for landing page, `/app` for the study planner).
- `package.json`: Project metadata for Vercel static site auto-detection.

## How to Deploy to Vercel (3 Easy Steps)

### Option 1: Via GitHub & Vercel Dashboard (Recommended)
1. Push this folder to a new GitHub repository.
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository. Vercel automatically detects the static site configuration and deploys it in seconds!

### Option 2: Deploy in 30 Seconds via Vercel CLI
1. Open your terminal in this project folder.
2. Run:
   ```bash
   npx vercel
   ```
3. Follow the quick prompts to link and deploy your site immediately to a free `*.vercel.app` domain.

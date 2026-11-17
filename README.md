# Univanta AI — University of Hail student demo

A student-made independent demo, not an official University of Hail service.

## Deploy to Netlify
Connect this repository. Publish directory: `.`; functions directory: `netlify/functions`. No build command needed.

## AI chat
Set `OPENAI_API_KEY` in Netlify environment variables, then redeploy. Never commit API keys. The AI chat needs the included serverless function and a valid API key.

## Student services
The **اسألني** page contains six student service shortcuts plus an employee-contact demo form. Service shortcuts create AI prompts only; they do not read student records, grades, attendance, or schedules. Employee form is a local demo only; it does not submit a ticket or contact staff. Do not enter real personal data.

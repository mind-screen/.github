<p align="center">
  <img src="https://raw.githubusercontent.com/mind-screen/.github/main/profile/assets/mind-screen-banner.png" alt="Mind Screen — voice-guided self-screening app" width="720">
</p>

# Mind Screen

**Understand your mind through a simple conversation.**

Mind Screen turns mental health questionnaires into a conversation. An AI assistant reads each question aloud, listens to your answer and gives you a clear result in minutes. Four screenings are free: depression, anxiety, loneliness and burnout. Your history stays on your device. Not a diagnostic tool. For adults 18 and over.

## How it works

1. **Pick a screening** — depression (PHQ-9), anxiety (GAD-7), loneliness or burnout are free.
2. **Pick an assistant** — each one has its own voice.
3. **Talk** — the assistant reads each question aloud, word for word, and listens to your answer in your own words.
4. **Read your result** — a score, a severity level and a short explanation in plain language, a few minutes later.

<p align="center">
  <img src="https://raw.githubusercontent.com/mind-screen/.github/main/profile/assets/mind-screen-voice-session.jpg" alt="A Mind Screen voice session: the assistant listens to a spoken answer" width="260">
</p>

## Key features

- **Spoken screenings** — the assistant reads each question aloud and listens to your answer. No forms to fill in.
- **Eleven standardized questionnaires** — depression (PHQ-9), anxiety (GAD-7), loneliness, burnout, adult ADHD, panic, post-traumatic stress, alcohol and drug use, mood and cognitive screening.
- **Four free screenings** — depression, anxiety, loneliness and burnout, with no card required.
- **Eight AI assistants** — each with its own voice; two are free.
- **Clear results** — a score, a severity level and a short explanation in plain language.
- **History and PDF reports** — follow your results over time and share a report with a professional (Pro).
- **Private by design** — history stored on your device, no ads, in-app account deletion.
- **Question wording is never changed by the AI** — questionnaires are delivered word for word and scored by fixed rules.

## What Mind Screen is not

Mind Screen is a self-awareness aid, not a diagnostic tool. A result never replaces the opinion of a qualified mental health professional. It is not a medical device, and it is intended for adults 18 and over.

## How it is built

The app, not the AI model, owns the questionnaire: questions live in script files, the model only interprets the spoken answer, and the score is computed by code with fixed rules. The AI provider's keys never ship inside the app; requests go through a server-side proxy that checks the user's sign-in first.

Built with Flutter, Dart, Firebase Auth and Supabase Edge Functions. The source code of the app is not public; this organization hosts the project's public information.

## Team

Mind Screen was created by Haythem Yahyaoui, runner-up of season 16 of Stars of Science, and developed by Ahmed Znouda.

## Links

- Website: https://mind-screen.com/
- Google Play: https://play.google.com/store/apps/details?id=com.mindscreen.app
- Privacy policy: https://mind-screen.com/privacy
- LinkedIn: https://www.linkedin.com/company/mind-screen
- X : https://x.com/mindscreenapp

<p align="center">
  <img src="https://raw.githubusercontent.com/mind-screen/.github/main/profile/assets/mind-screen-banner.png" alt="Mind Screen: voice-guided self-screening app" width="720">
</p>

<p align="center">
  <a href="https://mind-screen.com/"><b>Website</b></a> ·
  <a href="https://play.google.com/store/apps/details?id=com.mindscreen.app"><b>Google Play</b></a> ·
  <a href="https://mind-screen.com/privacy">Privacy</a> ·
  <a href="https://www.linkedin.com/company/mind-screen">LinkedIn</a> ·
  <a href="https://x.com/mindscreenapp">X</a>
</p>

# Mind Screen

**Understand your mind through a simple conversation.**

Mind Screen turns standardized mental health questionnaires into a spoken conversation. An AI assistant reads each question aloud, listens to your answer in your own words and gives you a clear result a few minutes later. Four screenings are free: depression, anxiety, loneliness and burnout.

> Mind Screen is a self-awareness aid, not a diagnostic tool. For adults 18 and over.

## Why a conversation?

A questionnaire on a screen is a list of boxes to tick. Many people put it off, rush through it or stop halfway. Talking is easier: you hear the question, you answer the way you would answer a person, and the app takes care of the rest. The questions themselves do not change: you get the same standard wording, only spoken.

## How it works

<p align="center">
  <img src="https://raw.githubusercontent.com/mind-screen/.github/main/profile/assets/mind-screen-how-it-works.png" alt="Four steps: pick a screening, pick an assistant, talk, read your result" width="820">
</p>

1. **Pick a screening.** Depression (PHQ-9), anxiety (GAD-7), loneliness and burnout are free.
2. **Pick an assistant.** Each one has its own voice; two are free.
3. **Talk.** The assistant reads each question aloud, word for word, and listens to your answer.
4. **Read your result.** A score, a severity level and a short explanation in plain language.

## Eleven standardized questionnaires

<p align="center">
  <img src="https://raw.githubusercontent.com/mind-screen/.github/main/profile/assets/mind-screen-questionnaires.png" alt="The eleven questionnaires in Mind Screen, four of them free" width="820">
</p>

| Free | Pro |
|---|---|
| Depression (PHQ-9) | Adult ADHD |
| Anxiety (GAD-7) | Cognitive screening |
| Loneliness | Panic |
| Burnout | Post-traumatic stress |
| | Mood (mania) |
| | Alcohol and drug use |
| | Aggression |

## Key features

- **Spoken screenings.** No forms to fill in: the assistant asks, you answer out loud.
- **Questions never rephrased.** Every questionnaire is delivered word for word, in its standard wording.
- **Scores by fixed rules.** The score is computed by code, never by the AI model.
- **Eight AI assistants**, each with its own voice. Two are free.
- **Clear results.** A score, a severity level and a short explanation in plain language.
- **History and PDF reports (Pro).** Follow your results over time and share a report with a professional.
- **Private by design.** Your history stays on your device. No ads. You can delete your account from inside the app.

## How it is built

<p align="center">
  <img src="https://raw.githubusercontent.com/mind-screen/.github/main/profile/assets/mind-screen-how-it-is-built.png" alt="The app owns the questionnaire, the AI model interprets the spoken answer, and code computes the score" width="820">
</p>

The app, not the AI model, owns the questionnaire. Questions live in script files inside the app. The assistant reads them aloud, the AI model only interprets your spoken answer and matches it to one of the questionnaire's options, and the score is computed by code with fixed rules. The same options always give the same score.

The AI provider's keys never ship inside the app: requests go through a server-side proxy that checks the user's sign-in first.

**Stack:** Flutter and Dart, Firebase Authentication, Supabase Edge Functions. The source code of the app is not public; this organization hosts the project's public information.

## What Mind Screen is not

- It is **not a diagnostic tool** and not a medical device.
- A result **never replaces the opinion** of a qualified mental health professional.
- It is **not an emergency service.** If you are in crisis, contact your local emergency number or a crisis line.
- It is intended for **adults 18 and over**.

## Frequently asked questions

**Is Mind Screen a diagnostic tool?**
No. It is a self-awareness aid. A result can help you decide whether to talk to a professional; it never replaces their opinion.

**Which questionnaires does it include?**
Eleven standardized questionnaires, including the PHQ-9 for depression and the GAD-7 for anxiety. Four are free: depression, anxiety, loneliness and burnout.

**Does the AI decide my score?**
No. Questions are delivered word for word, and scores are computed by fixed rules, not by the AI model.

**Do I have to speak?**
Yes, the screenings are designed as a spoken conversation, so you need a microphone and a quiet moment of a few minutes.

**Where is my history stored?**
On your device. There are no ads, and you can delete your account from inside the app.

**Who is it for, and on which devices?**
Adults 18 and over. Mind Screen is available on Android; iOS is planned.

## Team

Mind Screen was created by **Haythem Yahyaoui**, runner-up of season 16 of *Stars of Science*, and developed by **Ahmed Znouda**.

## Links

- Website: https://mind-screen.com/
- Google Play: https://play.google.com/store/apps/details?id=com.mindscreen.app
- Privacy policy: https://mind-screen.com/privacy
- LinkedIn: https://www.linkedin.com/company/mind-screen
- X: https://x.com/mindscreenapp

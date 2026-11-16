# Mindmap: Daily Water Intake Tracker (Mobile App)

```mermaid
mindmap
  root((Water Intake Tracker))
    User Needs
      Stay healthy
        Avoid dehydration
        Energy & focus
        Skin, digestion, weight goals
      Know how much to drink
        Personalized daily goal
        Adjust for weather & activity
        Guidance for pregnancy or medical needs
      Remember to drink
        Busy schedules
        Forgetfulness
      Low-effort logging
        Under 3 seconds per log
        No typing
      Motivation
        See progress
        Feel rewarded
        Build a habit
      Trust & privacy
        Health data kept safe
        No spammy notifications
    Features
      Onboarding
        Weight, age, activity level
        Climate & location
        Wake and sleep times
        Auto-calculated goal
      Logging
        One-tap quick add
        Custom cup and bottle sizes
        Other drinks with hydration factor
        Home-screen widget
        Smartwatch logging
        Voice via Siri or Google Assistant
        Smart bottle sync
      Reminders
        Smart timing based on schedule
        Quiet hours
        Snooze & adaptive frequency
        Location or activity triggers
      Progress & Insights
        Daily progress ring
        Weekly & monthly trends
        Best times of day
        Correlation with sleep & exercise
      Motivation & Engagement
        Streaks
        Badges & milestones
        Friend or team challenges
        Gentle encouragement messages
      Integrations
        Apple Health & Google Fit
        Wearables
        Weather API
        Calendar
      Personalization
        Units ml or oz
        Themes & dark mode
        Goal override
      Monetization
        Free core tracking
        Premium insights & themes
        Corporate wellness plans
    Potential Problems
      User Behavior
        Novelty wears off after 1-2 weeks
        Forgets to log, so data is wrong
        Over-logging or gaming streaks
        Streak loss makes users quit
      Notifications
        Reminder fatigue leads to mute or uninstall
        Bad timing in meetings or at night
        OS limits on background alerts
      Accuracy
        Generic goals don't fit everyone
        Water from food not counted
        Drink sizes estimated poorly
      Health & Safety
        Overhydration risk
        Users with kidney or heart conditions
        Implied medical advice and liability
      Privacy & Compliance
        Health data sensitivity
        GDPR & HIPAA questions
        Third-party SDK data sharing
      Technical
        Health-app sync conflicts
        Smart bottle connection issues
        Offline logging & data loss
        Widget & watch battery drain
      Market
        Crowded category with free alternatives
        Hard to differentiate
        Low willingness to pay
```

---

## How to read this

| Branch | PM takeaway |
|---|---|
| **User Needs** | The core job is *"help me remember and make it effortless."* Logging speed and good reminders matter more than detailed analytics. |
| **Features** | MVP = onboarding + personalized goal, one-tap logging and widget, smart reminders, daily progress ring, streaks. Integrations, challenges, and premium come later. |
| **Potential Problems** | The biggest risk is **retention**: novelty fades and reminders get muted. Address it from day one with adaptive reminders, forgiving streaks (e.g., "freeze" days), and logging that takes almost no effort. |

## Suggested MVP vs. Later

- **MVP (v1):** Onboarding & goal calculation, quick-add buttons, home-screen widget, smart reminders with quiet hours, daily ring + 7-day history, streaks, Apple Health / Google Fit sync.
- **v2:** Weather-adjusted goals, smartwatch app, other drink types, badges, deeper insights.
- **v3:** Social challenges, smart bottle integrations, premium tier, corporate wellness.

## Key metrics to watch

- **Day-7 / Day-30 retention**: the main signal of habit formation
- **Logs per active user per day**: shows engagement and data quality
- **% of days goal achieved**: shows the value delivered
- **Notification opt-out rate**: early warning for reminder fatigue

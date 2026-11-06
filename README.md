# Lamp

Light your lamp when you're open to meeting someone. Lamp shows who else in the same room (event, café, floor) has their lamp on, why you'd click, and an opener. Then you put your phone down and go talk.

Built in one evening at **Punk Software Hack Night: Own your interfaces** (SF, Nov 5, 2026).

## The idea

Big tech sits between us and the people we'd connect with, and it profits from keeping us on screens. Lamp is consent-based and room-scoped: only people who light their lamp can be matched, only within the room they're in, and nobody is notified when you look at them or walk over.

## What's in the prototype

- One-time onboarding: what Lamp is, your profile (one line, public links, interests), and exactly what lighting your lamp shares.
- **My Lamp:** room auto-detected (simulated), duration (30m / 1h / 2h / until off), optional "what I'm bringing tonight."
- **Room:** ranked list of people in your room with the reason you'd click; add or switch rooms.
- **Top matches:** swipeable cards with why you'd click and an opener; "Not now" is never a rejection.

## Full journey demo

Tap **Watch the full journey** on the first screen (or open the page with `#tour`) for a 12-step guided walkthrough: onboarding, profile, consent, lighting your lamp, top matches, saving someone for later, the room list, a match's card, putting the phone down, switching rooms, and Lamp recognizing your usual café. The tour uses sample data and saves nothing.

## Running it

`index.html` is a single file. It was built as a Claude Artifact, where it uses a shared database, viewer identity and Claude for tailored openers. Opened directly in a browser, it runs as a single-player demo with a sample room.

Location and room detection are simulated. Demo people are hack night attendees, shown by first name with descriptions drawn only from what they made public.

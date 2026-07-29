# 215 Super Search

A board president shouldn't need a spreadsheet and a prayer to hire a superintendent.

When our building super announced he was leaving, I realized the hiring process ahead of us was going to be messy. We'd be evaluating three to five candidates against the same criteria—32BJ union membership, HPD certification, live-in commitment, experience with pre-war steam systems—but there was no consistent way to document interviews, track references, or compare candidates side by side. The kind of thing that ends with someone saying "I thought *you* called his references."

So I built a tool that enforces the process. Upload a resume, and Claude reads it against our building's actual specs: 110 units, commercial tenants sharing basement access, a boiler from another era. The AI flags relevant experience and gaps before we even pick up the phone. Then the interview framework walks through four scoring areas—building systems, operations, live-in fit, comparable property background—with the same questions every time. References get tracked with outcomes. Offers get logged with dates. One candidate gets marked hired.

The whole thing lives behind a login, to protect PII. But what it produces—a defensible, consistent record of how we evaluated each candidate—is something the full board can review.

***

## What it does

The app handles the full lifecycle of superintendent hiring for a single building. A PDF resume goes in; Claude extracts the candidate's profile and scores it against building-specific criteria (pre-war systems, NYC compliance filings, staff supervision, commercial tenant coordination). From there, the candidate moves through hard requirement checks, a structured interview with four scored competency areas, reference tracking with outcomes, in-person session logging, and offer management.

The dashboard shows every candidate side by side: average interview scores, recommendation status, reference summaries, offer progress. It's designed for a board president who needs to defend a hiring decision to a committee—not remember it.

***

## Stack

`React` · `Vite` · `Firebase Auth` · `Firestore` · `Netlify Functions` · `Claude API`

***

## Status

Private. In active use for an ongoing superintendent search.

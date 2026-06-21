# Jusoor × GSK — Shingrix AI Engagement Engine

An AI-powered patient engagement system for the GSK Shingrix (recombinant zoster vaccine) adult immunisation campaign in the Kingdom of Saudi Arabia, built by Jusoor.

## What it does
A conversational Arabic WhatsApp assistant that identifies eligible adults, educates them by risk profile, and follows them through the full two-dose course — lifting series completion without requiring access to MOH records (Phase 1 runs entirely on opt-in, self-reported data).

## Eligibility logic
- **50+** — all immunocompetent adults
- **18+** — adults who are immunocompromised
- **Two doses**, 2–6 months apart (shorter 1–2 month interval offered to immunocompromised patients)
- **Caregiver branch** for under-50 contacts caring for an eligible parent/spouse

## The system (`index.html`)
A single self-contained file with 8 sections: Overview dashboard, Vaccination Registry, Today's Actions, Patient Segments, Arabic WhatsApp Bot simulator, Messaging Centre, Compose Campaign, and the RWE Pipeline.

Open `index.html` in any browser, or enable GitHub Pages to get a live demo link.

> Demo data is illustrative. Clinical copy should be reviewed by GSK medical/regulatory before patient use.

# Uber Trip Recovery Intelligence

> Rescuing the journey, not just the ride.

An independent product management case study exploring how ride-hailing apps could **automatically recover a disrupted trip** — driver cancellation, pickup failure, or ETA blowout — instead of dropping the rider back to a blank search screen.

The core idea: a rider's goal was never *"complete this specific booking,"* it was *"reach my destination."* This project reframes trip failure from a dead end into a recoverable state.

🔗 **[Live prototype](https://triprecoveryintelligence.lovable.app)**  

📄 **[Full PRD](https://app.notion.com/p/Uber-Trip-Recovery-Intelligence-3bae7f155a8e80a08be6de300fd0a0a7?source=copy_link)** 

---

## What this repo contains

A single-page React + TypeScript + Tailwind prototype (built with Bolt) simulating the end-to-end recovery flow:

1. **Booking** — standard ride booking, destination pre-filled
2. **Rescue Activating** — auto-triggers when the driver cancels; destination and fare carry forward automatically, no re-entry
3. **Recovery Options** — a ranked best-match recovery plus alternatives
4. **Urgency Input** — optional deadline field that re-ranks options toward arrival reliability over price
5. **Fare Delta Confirmation** — if the recovered ride costs more, the rider sees the exact delta and must explicitly confirm before being charged
6. **Mid-trip ETA Disruption** — a separate recovery path for delays that happen *after* pickup, distinct from a pre-pickup cancellation


---


## Why this exists

Built as a portfolio case study to practice full-cycle PM work: problem framing, prioritization (RICE + MoSCoW), user stories, functional/non-functional requirements, an A/B test design with a real power calculation, and a clickable prototype to validate the flow — not just a written spec.

## Tech stack

- React + TypeScript
- Tailwind CSS
- Vite
- Hosted via Bolt

---

## About

Built by [Mehak](https://github.com/mehak2710) as part of a product management portfolio.

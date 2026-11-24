# LifeFirst BD

**A smart emergency response system for Bangladesh.**

> "Ensuring no life is lost due to lack of information or coordination."

LifeFirst BD is a **concept and design project that is currently in development**. This repository contains the design documents. The working app is not built yet.

Started at **Grace Hopper MindStorm 2.0** (organized by the BRAC University Computer Club, Women's Day 2026), where it won first place. Team: **Team Nemo**.

---

## The problem

In an emergency in Bangladesh, people often lose critical time because:

- Emergency systems are centralized and poorly coordinated
- Ambulance response can be delayed
- Hospitals do not share real-time data on beds or ICU availability
- It is hard to know where blood is available
- People turn to unverified sources, such as social media groups, which causes confusion

These delays can cost lives, and they put heavy emotional and financial pressure on families.

## The gap in existing solutions

| Existing option | Limitation |
|---|---|
| Hotline services | Slow and overloaded |
| Facebook groups | Unverified and chaotic |
| Hospitals | Not digitally connected |
| Ambulances | No tracking system |

## The proposed solution

One platform that connects:

- **Users:** one-tap emergency alert
- **Blood donors:** instant matching by blood group
- **Ambulances:** real-time tracking
- **Hospitals:** bed and ICU availability
- **Pharmacies:** medicine availability at the nearest pharmacy

## How it works

1. A user triggers an emergency through the **app or by SMS**.
2. The system detects the user's location (GPS).
3. A matching algorithm finds the nearest available services.
4. The nearest ambulance, hospital and matching blood donors are **notified within a set radius (about 10 to 50 km)**.

SMS access is included so people with **basic button phones**, including rural and low-income users, can also use the system.

## Design principles

LifeFirst BD is meant to be used by people who are scared, in a hurry, and often not using a smartphone. So the design aims to be:

- **Fast:** the main emergency action takes one tap
- **Simple:** very few choices on screen during an emergency
- **Inclusive:** works on smartphones and on basic phones through SMS
- **Trustworthy:** verified responders, consent-based data sharing
- **Private:** donors and patients control who sees their information

## Planned technology

These are planned choices, and none are final.

- Android-first mobile app
- Cloud database (Firebase or AWS)
- GPS and location services
- Matching algorithm for nearest services
- SMS gateway for rural access
- Optional integrations: government health database and hospital dashboards

## Roadmap

**Phase 1: Dhaka pilot**
- Partner with selected hospitals
- Onboard ambulance services

**Phase 2: Expansion**
- Add blood banks and donors
- Improve matching

**Phase 3: Nationwide**
- Rural SMS integration
- Government collaboration
- NGO partnership (for example, BRAC)
- Reach through mobile financial service agents (for example, bKash)

Long-term ideas: telemedicine support, emergency prediction, and a freemium service model.

## Privacy and ethics

- Protect user data
- Share data only with consent
- Handle medical information securely
- No misuse of personal data
- Accessible to all income groups, in both urban and rural areas

## Current status

- [x] Problem research and gap analysis
- [x] Concept design and presentation (this repository)
- [ ] User interviews (donors, patients' families, ambulance drivers)
- [ ] Interface prototype
- [ ] Working app and SMS service
- [ ] Hospital and ambulance pilot

The app screens in the presentation are **concept designs**, not a finished product.

## Files

- `LifeFirst BD.pdf`: the full presentation (problem, solution, plan, ethics, future)

## Sources for the problem statement

The presentation refers to reporting from *The Daily Star*, *The Business Standard* and *Dhaka Tribune* on slow emergency helpline response, overcrowded hospitals, misinformation in health, and the lack of ambulance lanes.

## About

**Ayesha Islam Upama**
Second-year B.Sc. student in Computer Science and Engineering, BRAC University.
Interested in Human-Computer Interaction, inclusive design, and technology that serves communities.

Contact: ayesha.islam.upama@g.bracu.ac.bd

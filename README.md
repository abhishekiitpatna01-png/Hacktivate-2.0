# ✈️ Predictive Turnaround Optimization (PTO) — Demo

A simple demo project for **Flight Hack 2.0 — Program Management Track**.

## What problem does this solve?

When a plane lands, many teams have to finish their work fast before it can take off again — fueling, cleaning, catering, boarding, and baggage. Right now, these teams don't talk to one system, so delays are noticed *after* they happen. That causes late flights.

## What does this project do?

This is a small dashboard that:
1. Shows all the ground jobs for each flight (fueling, cleaning, catering, boarding, baggage).
2. Checks how much of each job is done.
3. Tags each flight as:
   - **On Time**
   -  **At Risk**
   -  **High Risk**
4. Shows an alert message for flights that are falling behind — so the ground team can fix it *before* the flight is delayed.

This is a **demo only**. In the real idea (see the pitch deck), the risk score would come from a trained machine learning model using live airport data. Here, we use simple, easy-to-read rules instead, so anyone looking at the code can understand it.

## Files in this project

| File | What it does |
|---|---|
| `index.html` | The web page itself |
| `style.css` | Makes it look nice (colors, cards, progress bars) |
| `data.js` | Fake/sample flight data (stand-in for real airport data) |
| `predict.js` | Simple rules that decide if a flight is On Time / At Risk / High Risk |
| `script.js` | Draws the flight cards on the page using the data and the rules |

## How to run it

You don't need to install anything.

1. Download or clone this project.
2. Double-click `index.html` (or open it in any web browser).
3. That's it — you'll see the dashboard with sample flights.

## How to put this on GitHub

1. Create a new repository on GitHub (e.g. `flight-turnaround-predictor`).
2. Upload all the files in this folder to that repository.
3. (Optional) Turn on **GitHub Pages** in the repo settings so anyone can view the live dashboard in their browser, no download needed.

## How to change the data

Open `data.js` and edit the numbers for `fueling`, `cleaning`, `catering`, `boarding`, and `baggage` for any flight (0 to 100). Save the file and refresh `index.html` — the dashboard updates automatically.

## Next steps (if you build this further)

- Connect `data.js` to a real airport data feed instead of fake numbers.
- Replace the simple rules in `predict.js` with a real ML model.
- Add SMS/app push alerts to actually notify ground crews (mentioned in the pitch deck).
- Add a history/analytics page to track turnaround improvements over time.

---
Made for the Flight Hack 2.0 idea submission: **Predictive Turnaround Optimization (PTO)**.

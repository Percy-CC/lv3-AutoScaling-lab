# Project Notes

## Purpose

This project is a standalone Auto Scaling learning simulator for Cloud Computing Lab 10. It models fictional traffic, instance capacity, start-up time, failure detection, cost, load balancing, and scaling policies.

## Architecture

| Area | Implementation |
|---|---|
| UI and simulation | A single self-contained [index.html](./index.html) file |
| State | Browser `localStorage` |
| Charts | Native Canvas 2D |
| Interactions | Vanilla JavaScript |
| Transitions | GSAP core, loaded from jsDelivr with a no-animation fallback |

## Main learning areas

1. Single-server capacity limits
2. Vertical and horizontal scaling
3. Load balancing
4. Auto Scaling configuration
5. Predictive scaling

## Localization

The header language button applies Traditional Chinese or English to the visible interface. Navigation uses full mission names:

| Traditional Chinese | English |
|---|---|
| 任務一 | Mission 1 |
| 任務二 | Mission 2 |
| 任務三 | Mission 3 |
| 任務四 | Mission 4 |
| 任務五：AI | Mission 5: AI |

The selected language persists through `localStorage`.

## Validation

For changes to the lab:

1. Open `index.html` in a browser.
2. Check both language modes, including mission pages and learning progress.
3. Run at least one simulation in each language.
4. Verify no JavaScript errors appear in the browser console.


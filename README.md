# Baraka Share 🍽️

**A bilingual (English/Arabic) food-sharing website that connects people with surplus food to charities and neighbours in Saudi Arabia.**

Built for **WarriorHacks 2.0** · Theme: *solve an issue in your community, county, state, or nation*.

## The problem

Saudi Arabia wastes a huge amount of edible food every year, from restaurants, weddings, events, bakeries, and households. At the same time, many families and charities need meals. There is no simple, fast way for a restaurant with 30 leftover meals at 9 PM to reach someone who can use them before they spoil.

## The solution

Baraka Share is a simple website where:

1. **Donors** (restaurants, bakeries, families) post surplus food in under a minute: what it is, how many meals, which city, and how long it stays safe.
2. **Receivers** (charities, volunteers, anyone nearby) browse live listings, filter by city, and claim food before it expires.
3. A live **impact counter** shows meals and kilograms of food rescued.

## Features

- Arabic and English with full right-to-left support (one-click language switch)
- Post food, filter by city, and claim listings
- Countdown timers and urgency badges so food is picked up in time
- Food safety tips built into the page
- Accessible design: large tap targets, high contrast, keyboard focus outlines, screen-reader labels
- Works on phones and desktops, no installation or login needed

## How to run

No setup needed:

1. Download or clone this repo.
2. Open `index.html` in any web browser.

To host it free, use GitHub Pages: repo **Settings → Pages → deploy from `main` branch**.

## Tech

- Plain HTML, CSS, and JavaScript (single file, no dependencies)
- Browser `localStorage` for saving data in this prototype
- Built-in translation system for English/Arabic

## Feasibility and next steps

This is a working prototype. The path to a real product:

- Replace `localStorage` with a shared database (for example Firebase or Supabase) so all users see the same listings
- Add user accounts and verified charity partners
- Add a map view and pickup notifications (WhatsApp/SMS)
- Partner with existing food-rescue organisations and restaurants

## Judging criteria

| Criteria | How Baraka Share addresses it |
|---|---|
| Impact | Targets food waste and hunger, with a clear audience: donors and charities |
| Feasibility | Simple tech, free to host, clear scaling path |
| User Experience | Bilingual, mobile-friendly, accessible, 1-minute posting |
| Technical Craft | Clean single-file architecture, RTL i18n system, expiry logic, persistent state |

## Team

Solo project by **Jood Ibrahim**, Saudi Arabia.

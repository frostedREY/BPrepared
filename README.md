# BPrepared

**BPrepared** is an offline-first, single-page web app built as an educational DRRM tool for teachers, school heads, and non-teaching personnel. It focuses strictly on what school staff should do before, during, and after a bomb threat — and stops exactly where Explosive Ordnance Disposal (EOD) and law enforcement take over.

Below is a full feature breakdown.

---

## 📱 Platform & Technical Features

- **Single-file core app** — the entire UI runs from one `index.html` file with no build step, no framework, and no dependencies. Just open and use.
- **Offline-first** — works fully offline once loaded. No internet connection required for any content.
- **Minimal-online** - only use internet intent upon clicking "Learn more from the creator, CISA Bomb Threat Guide and Visit Github Repo"
- **Works from `file://`** — no web server needed. Double-click the HTML file and the app runs.
- **Capacitor-ready** — designed to be wrapped into a native Android APK via Capacitor without code changes.
- **Externalized content** — large sections (like Myths vs. Facts) can now live in separate `.js` file and are now possible to injected on load using *import file* function, keeping the main file clean and easy to maintain.
- **Dark mode aware** — full dark mode across every section, toggle-persisted.
- **Responsive layout** — designed for phones first, with safe-area insets support for notched devices.

---

## 🧭 Navigation & UX

- **Bottom navigation bar** — five thumb-friendly tabs: **Home**, **Procedures**, **Reference**, **Remember**, and **More**.
- **Top app bar** — displays the current screen title, plus a quick-access phone icon for emergency contacts.
- **Card-based layout** — every section uses clean, tappable cards with consistent spacing and readable typography.
- **Sticky segmented control** — the Before / During / After tabs stay anchored at the top of the Procedures screen as you scroll.
- **Exclusive accordion behavior** — opening one section in the Knowledge Base automatically closes the others, so you never lose your place.
- **Collapsible cards** — Acknowledgements and App Information sections start collapsed and expand on tap to reduce visual clutter.
- **Adjustable text size** — Small / Medium / Large options let users scale the content to their comfort level.
- **Smooth entrance animations** — every screen fades in cleanly when navigated to.
- **Persistent preferences** — theme and text size choices are saved to `localStorage` and restored on next launch.

---

## 🚨 Emergency Response Contacts

- **Top Section in the Reference Page** — a dedicated section accessible from reference page.
- **Editable contact fields** — personalize the numbers for:
  - Bureau of Fire Protection (BFP)
  - Local PNP Station
  - Rescue Team
  - Municipal DRRMO
- **Save to device** — numbers are stored locally via `localStorage`.
- **Input validation** — accepts only valid phone number formats.

---

## 📋 Procedures (Before / During / After)

- **Three-phase breakdown** with a segmented control for quick switching.
---

## 📚 Reference Library (Knowledge Base)

A comprehensive, self-contained knowledge base organized as exclusive accordions:

### 👥 Roles & Responsibilities
Color-coded blocks that define exactly who does what — School Head, DRRM Coordinator, Teachers, Security / Utility Personnel, and Learners — with individual duty lists under each.

### 🎭 Special Situations
Scenario cards covering real-world contexts, and on how to handle each.

### 📖 Terms & Definitions
Plain-language and simplified definitions of relevant terminologies.

### ⚖️ Philippine Legalities & DepEd Orders
Four categorized groups with full titles, descriptions, and quick-reference tags.

### 👁️ Suspicious Indicators
A visual awareness guide organized into four categories — Objects & Items, Persons & Behavior, Vehicles, and Situations & Signs. High-risk items are flagged in red.

### 📍 Vulnerable Areas — Risk Mapping
Every common school zone classified into three color-coded risk tiers:
- 🔴 **High Risk** — 9 prime target areas
- 🟠 **Medium Risk** — 10 vulnerable spots
- 🟡 **Low Risk** — 8 occasional-check areas

### 🕵️ Who Are Possible Bombers
Possible threat-actor profiles, that can be used for awareness-not for profiling individuals.

### 🧨 Bomb Items — Image Awareness
Visual reference cards with actual image loading support:

Each card shows "Looks like" vs "Actually is" chips and filename placeholders that auto-load real images when dropped into the folder.

### ▶️ YouTube Videos — Watch & Learn
Curated video library organized to serve as a video reference. *Still ongoing*

Each card shows a YouTube-red thumbnail, title, badge, and URL. Tap to open in the native YouTube app or browser.

### 🏠 Highly Dangerous Household Items
Awareness-only reference for common household precursors, should be used for recognition not handling.

---

## 🧠 Most Important Things to Remember

Critical reminder cards organized by urgency:

**Critical reminders (red badge):**
**Standard reminders:**
**Safe-practice reminders (green badge):**

### 📖 Common Misconceptions
Myth vs. Fact cards that correct the most dangerous false beliefs about bomb threats and bombings — from "it's just a prank" to "we can search the building ourselves."
Import functions added in the *v2.1.2* release, users can now import files from their local storage.
---

## 💝 Support & About

- **Developer message** — a personal note explaining why the app exists and who it's for.
- **Crypto donation panel** — collapsible section with BTC, DOGE, and XRP wallet addresses.
- **Copy with confetti** — tapping "Copy" on any address triggers a colorful confetti burst animation as visual confirmation.
- **Acknowledgements** — collapsible cards crediting DepEd, PNP EOD / K9, BFP, MDRRMO, CISA, teachers, and the open-source community.
- **Sources & References** — collapsible card listing legal and technical citations.

---

## 🎨 Visual & Interaction Design

- **Material-inspired card UI** — clean, modern, and readable.
- **Color-coded by meaning** — blue for information, red for danger, amber for warnings, green for safe practices.
- **High-contrast typography** — deliberately chosen for readability in classrooms and stressful situations.
- **Iconography throughout** — every section, card, and action uses a consistent emoji set for instant visual recognition.
- **Large touch targets** — every interactive element meets the 48dp minimum for accessibility.
- **Smooth transitions** — subtle animations on accordions, sheets, screens, and toggles never interfere with content.
- **Dark mode** — full theme support with proper contrast across every card, tile, and callout.

---

## 🔒 Privacy & Safety

- **No tracking** — no analytics, no telemetry, no third-party scripts.
- **No ads** — completely free, forever.
- **No data collection** — all user preferences stay on-device via `localStorage`.
- **No permissions required** — the app does not request camera, location, contacts, or storage access.
- **Clear scope boundary** — every section respects the boundary where school personnel responsibilities end and EOD / law enforcement control begins.

---

## 🌐 Localization Notes

- All content is written in English.
- Legal references follow Philippine law and DepEd issuances.
- Designed for use by Filipino teachers and school staff.

---

## 🛠️ Customization Points

- **Emergency contacts** — teachers can enter their own local numbers without editing code.

---

**BPrepared **
*Bomb Threat Preparedness and Response for Teachers and School Personnel*
Developed by Rey

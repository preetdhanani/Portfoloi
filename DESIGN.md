---
name: Prit Dhanani · Portfolio
description: Single-page portfolio of an AI engineer who fine-tunes, aligns and evaluates language models that run on your own hardware.
colors:
  paper: "#E8ECF0"
  raise: "#F4F6F8"
  ink: "#16243A"
  muted: "#53607A"
  line: "#C8D0DA"
  cobalt: "#2B47D9"
  signal: "#D9861C"
  soft: "#DCE2EA"
  status-green: "#2DB36A"
  on-accent: "#FFFFFF"
  paper-dark: "#111A27"
  raise-dark: "#172234"
  ink-dark: "#E4E9F1"
  muted-dark: "#97A3B7"
  line-dark: "#2A3850"
  cobalt-dark: "#8297FF"
  signal-dark: "#F2B157"
  soft-dark: "#1C2940"
typography:
  display:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(3.4rem, 9vw, 7.6rem)"
    fontWeight: 800
    lineHeight: 0.9
    letterSpacing: "-0.045em"
  contact-display:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 7vw, 5.4rem)"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2.2rem, 5vw, 3.6rem)"
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  statement:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.6rem, 3.2vw, 2.4rem)"
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: "-0.02em"
  role:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.2rem, 2.2vw, 1.6rem)"
    fontWeight: 400
    lineHeight: 1.3
  contact-link:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.3rem, 3.4vw, 2.2rem)"
    fontWeight: 400
  title:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.7rem, 3vw, 2.3rem)"
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  subtitle:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  fact-title:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
  brandmark:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 800
    letterSpacing: "-0.03em"
  metric:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "2rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.03em"
  button:
    fontFamily: "IBM Plex Sans, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "0.98rem"
    fontWeight: 500
  body:
    fontFamily: "IBM Plex Sans, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "IBM Plex Sans, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "0.88rem"
    fontWeight: 400
    lineHeight: 1.6
  monogram:
    fontFamily: "Bricolage Grotesque, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "0.7rem"
    fontWeight: 800
    letterSpacing: "0em"
  svg-text:
    fontFamily: "IBM Plex Sans, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 400
  svg-label:
    fontFamily: "IBM Plex Sans, Helvetica Neue, Arial, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 400
rounded:
  pill: "999px"
  card: "22px"
  browser: "14px"
  card-inner: "10px"
  inner: "9px"
  control: "8px"
  tab: "7px"
  chip: "6px"
  focus: "4px"
spacing:
  xs: "0.4rem"
  sm: "0.75rem"
  md: "1.5rem"
  lg: "3rem"
  section: "clamp(4rem, 9vw, 7rem)"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "0.8rem 1.25rem"
  button-primary-hover:
    backgroundColor: "{colors.cobalt}"
    textColor: "{colors.paper}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0.8rem 1.25rem"
  button-ghost-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  chip-outline:
    backgroundColor: "{colors.raise}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0.35rem 0.8rem"
  tag-soft:
    backgroundColor: "{colors.soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.chip}"
    padding: "0.25rem 0.65rem"
  card-viz:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "1.6rem"
---

# Design System: Prit Dhanani · Portfolio

## Overview

**Creative North Star: "The Engineer's Bench"**

Every element on this page is a tool laid out for work.
The palette is a draughtsman's desk: cool paper, blueprint navy ink, one cobalt for structure and one amber for attention.
Type talks in a characterful grotesque and reads in a documentation workhorse.
Nothing is decorative that cannot explain what it is for; the hero canvas, the pipeline diagrams and the ScoutFox demo are all the same idea, a system doing its work in front of you.

The surface is flat and line-separated.
Depth comes from tonal steps (paper, raise, soft) and 1px hairlines, never from stacked shadows.
Color is scarce on purpose: cobalt and amber together cover well under ten percent of any viewport, and their rarity is what makes the diagrams and the agent demo read as alive.
Motion follows one doctrine: pixels move when a system in the story is working, and they answer immediately when the visitor acts.

**Key Characteristics:**

- Flat, hairline-separated surfaces with tonal layering instead of shadows.
- Two-accent discipline: cobalt works, amber points.
- Editorial asymmetric grids that collapse to a single honest column.
- Diagrams and demos are first-class content, not illustrations.
- Numbers set large and heavy; proof is the loudest voice on the page.

## Colors

A cool, desaturated desk palette carried by two saturated working accents.

### Primary

- **Printer's Cobalt** (#2B47D9): the working hand.
Links, the timeline spine and node markers, focus rings, the primary button's hover state, chart highlights and the "now" job dot.
It marks structure and interaction, never alarm.

### Secondary

- **Bench Amber** (#D9861C): the pointing hand.
The agent's live activity (falling tokens, moving cursor, click pings), the ScoutFox tab accent, marked results and stopped states.
It says "look here, this is happening now", never "error" and never "brand".

### Neutral

- **Cool Paper** (#E8ECF0): page background and the inner face of cards.
- **Raised Surface** (#F4F6F8): cards, the projects band, chips and the browser mock's chrome.
- **Blueprint Navy** (#16243A): all primary text, the dark About band's background, primary button fill.
- **Muted Slate** (#53607A): secondary text, captions, idle nav links.
- **Hairline** (#C8D0DA): every structural border and divider.
- **Soft Fill** (#DCE2EA): quiet fills inside cards, skeleton bars, chip backgrounds on dark surfaces.
- **Status Green** (#2DB36A): reserved for genuine success and completion states (done checks, the demo's Done card).
It never decorates.

### Named Rules

**The Two-Hand Rule.**
Cobalt is the working hand: structure, links, focus, selection.
Amber is the pointing hand: live activity and attention.
They never swap jobs, and no third accent ever joins the bench.

**The Scarce Accent Rule.**
Cobalt and amber together stay under roughly ten percent of any viewport.
If a screen feels gray, the answer is more proof, not more color.

Dark mode (`prefers-color-scheme` plus a `data-theme` override) keeps every role and flips the values: paper #111A27, raise #172234, ink #E4E9F1, muted #97A3B7, line #2A3850, cobalt #8297FF, signal #F2B157, soft #1C2940.
Any new color must ship both light and dark values in the same edit.

**The Deep Signal Rule.**
Amber on light paper is only 2.4:1 - fine for large fills, below the 3:1 non-text minimum for thin lines.
Thin amber linework in the diagrams (the 16 GB limit line, the Deck Engine retry loop) uses `--signal-deep` (#B26612, 3.7:1); dark mode maps it back to `--signal` (#F2B157, 9.3:1).
Filled marks, pings, the cursor and status tints keep `--signal`: they are large, haloed or momentary, and their brightness is the live-activity energy.

## Typography

**Display Font:** Bricolage Grotesque (variable, optical size 12-96; weights 400, 600, 800) with Avenir Next, Segoe UI, system-ui.
**Body Font:** IBM Plex Sans (400, 500, 600, italic 400) with Helvetica Neue, Arial, system-ui.

**Character:** a grotesque with a personality doing the talking, and a documentation workhorse doing the reading.
The pairing says "engineered, but written by a person".

### Hierarchy

- **Display** (800, clamp(3.4rem, 9vw, 7.6rem), line-height 0.9, tracking -0.045em): the hero name only.
- **Contact display** (800, clamp(2.6rem, 7vw, 5.4rem), tracking -0.04em): the contact headline, a step smaller than the hero name.
- **Headline** (600, clamp(2.2rem, 5vw, 3.6rem), line-height 1.05, tracking -0.02em): section titles.
- **Title** (600, clamp(1.7rem, 3vw, 2.3rem)): featured project names.
- **Subtitle** (600, 1.5rem): role names and list-group headings.
- **Statement** (400, clamp(1.6rem, 3.2vw, 2.4rem), line-height 1.3): the about quote.
- **Role line** (400, clamp(1.2rem, 2.2vw, 1.6rem), line-height 1.3): the hero's one-sentence pitch.
- **Contact link** (400, clamp(1.3rem, 3.4vw, 2.2rem)): the email link, display face at rest weight.
- **Fact title** (600, 1.25rem): the about band's fact headings.
- **Brandmark** (800, 1.15rem, tracking -0.03em): the "Prit." mark.
- **Metric** (800, 2rem, line-height 1, tracking -0.03em): proof numbers, always paired with a 0.88rem caption.
- **Button** (500, 0.98rem): button labels.
- **Body** (400, 1.0625rem, line-height 1.6): running text, capped near 52-58 characters.
- **Label** (400-500, 0.88rem): captions and demo readouts.
- **SVG text** (13px) and **SVG label** (12px): type inside the inline diagrams.

The label band below body runs 0.78-0.98rem in continuous steps (0.78 demo readout, 0.8 hint, 0.82 stack chip, 0.85 tag and viz caption, 0.9 footer, 0.92 skill chip, 0.94 entry detail, 0.95 nav link, 0.96 row detail).
That band is intentional: pick a size by hierarchy distance from the text it supports, not by a grid.

### Named Rules

**The Tight Display Rule.**
Display sizes run tight leading (0.9-1.05) and negative tracking; that is the voice.
Body text never drops below 1.6 leading, and display leading never leaks into it.

**The Number Is the Copy Rule.**
Metrics are set in the display face at 800 with no decoration around them.
If a number needs an adjective to land, the number is wrong.

## Layout

One continuous column on a centered container: `min(1160px, 100% - 2.5rem)`, so side gutters are 1.25rem at the smallest and the content never stretches past 1160px.
Sections breathe with `clamp(4rem, 9vw, 7rem)` of vertical padding.

Grids are asymmetric and editorial, built from `minmax(0, Nfr)` columns so text never overflows:
hero 1.15fr/0.85fr, about 1.4fr/1fr, featured projects 1.1fr/1fr with the visual column alternating sides, section heads 1fr/2fr, experience rows 1fr/2fr, skills 1fr/3fr.

Breakpoints collapse to a single column in order: 860px (hero, about, features), 760px (section heads, experience rows, project rows, skills), 720px (nav links hide except Contact).
The ScoutFox browser mock uses a container query at 440px to grow its own two-column layout independent of the viewport.

## Elevation & Depth

The system is flat by default.
Structure is carried by tonal steps (paper under raise under soft) and 1px hairlines; nothing earns a shadow by sitting in the flow of the page.
Shadows exist only for elements that float above the page: the portrait photo, the two floating tags, the ScoutFox browser window and the agent's cursor.

### Shadow Vocabulary

- **Portrait float** (`0 30px 60px -30px rgba(22,36,58,.55)`): the one large soft shadow on the page, under the circular portrait.
- **Tag float** (`0 8px 20px -12px rgba(0,0,0,.4)`): small pills that sit on top of the portrait.
- **Window float** (`0 24px 40px -28px rgba(22,36,58,.5)`): the browser mock, lifted like a real window on the desk.

### Named Rules

**The Float-Only Shadow Rule.**
A shadow is proof that an element physically floats above the page.
Cards in the layout flow never get one; if it would not cast a shadow on a real desk, it does not get one here.

## Shapes

The radius vocabulary is a fixed ladder, and each step means something:
999px pills for actions and status tags (buttons, chips, URL bar, status pills);
22px for the large diagram cards;
14px for the browser mock's outer chrome;
10px for the demo's result card;
9px for controls inside cards (task box, result rows);
8px for the demo's buttons and search field;
7px for the browser tab;
6px for the smallest stack chips;
4px on focus outlines only.

Border weights are equally fixed: 1px hairlines carry structure, 1.5px marks anything interactive (buttons, inputs, demo controls), and 2px is an accent mark (the h3 underlines in the education grid, the mail link's underline).
One recurring silhouette: the dashed 1.5px cobalt ring that orbits the portrait.

## Components

The component feel is **tactile and confident**: controls answer immediately, movement is small and sure, and a press always settles back.
Hover lifts are 1-2px, presses compress, and everything runs on the house ease `cubic-bezier(0.2, 0.7, 0.2, 1)` at around 200ms.

### Buttons

- **Shape:** full pill (999px), 1.5px ink border, padding 0.8rem 1.25rem, weight 500.
- **Primary:** ink fill, paper text; hover turns the fill cobalt and lifts the button 2px; ghost fills ink with paper text.
- **Active:** the press settles back to rest with a 1% compress (`scale(0.99)`); the lift never bounces.
- **Disabled:** demo controls sit at 45% opacity with a default cursor; no other disabled style exists yet.
- **Transition:** background, color and transform at 0.2s on the house ease; focus is the global 2px cobalt outline offset 3px.

### Text links

**The Detaching Underline motif.**
Every text link owns a solid underline that detaches on hover: the underline slides a few pixels away from the text and stays attached to its color.
Project links (1.5px cobalt underline) move padding-bottom from 1px to 3px; the contact email (2px underline, display face) moves to 0.2rem.
Both run 0.2-0.25s on the house ease.
Nav links are exempt: they answer with color alone, the bar stays quiet.

### Result Card (ScoutFox)

**The Honest Result Rule.**
The demo's outcome card speaks in exactly four states, and a run that did not work never looks like a success:
done (green border), unconfirmed, failed, or stopped by you (amber border, with a count of the steps left unfinished).
State colors come from the palette's meaning: green only for genuine completion, amber for interruption and attention.

### Browser Surfaces

The parts the browser draws by default carry the palette too:
text selection is cobalt fill with paper text;
proof numerals (the metric blocks) set `tabular-nums` so digits never jitter;
focus is always the global 2px cobalt outline, offset 3px, radius 4px.
These are never left at browser defaults.

### Chips

- **Stack chips** (project tech lists): soft fill, 6px radius, 0.82rem, no hover behavior; they are labels, not controls.
- **Skill chips:** pill outline on raise, hover turns border and text cobalt with a 1px lift; they invite pointing.

### Cards / Containers

- **Diagram card (.viz):** paper fill, 1px hairline, 22px radius, 1.6rem padding, no shadow; it sits on the desk.
- **Browser mock (.sf):** raise fill, 14px radius, window float shadow; the one object that pretends to be hardware.
- **Result rows (.rows):** full-width hairline-separated rows; hover raises the background and indents the row 0.5rem.

### Inputs / Fields

- **Demo fields (search box, task box):** 1.5px hairline border, 8-9px radius, paper fill; focus turns the border cobalt and shows a blinking caret block.
- **Focus:** global `:focus-visible` is a 2px cobalt outline offset 3px with a 4px radius; never removed, never recolored.

### Navigation

Sticky 64px bar on a blurred 92% paper backdrop; the bottom hairline fades in only after the page scrolls.
A 2px cobalt indicator rides the bar's bottom edge and travels under the link of the section you are in, transform-only at 0.35s on the house ease, and the active link carries `aria-current`.
It hides at the top of the page and on widths where a link is collapsed; reduced motion lets it jump instead of travel.
Links are muted slate and turn ink on hover; on small screens only the mark and Contact survive.

### Timeline

A 2px spine gradient running cobalt into hairline, with 16px dots ringed 3px in cobalt.
The current job's dot is filled; past jobs are hollow.
The spine draws itself top-down over 1.4s on the house ease when the section enters the viewport, once per load; under reduced motion it is simply there.
Roles sit in a 1fr/2fr grid, title block left, bullets right.

### Certification Rows

Hairline-separated rows under the skills grid: a 30px issuer tile (6px radius, soft fill, monochrome mark or bold monogram - the Microsoft four-square, a chain link for LangChain Academy, a line-drawn face for Hugging Face, the AWS smile arrow, IBM and CC monograms), the credential name at 0.95rem weight 500, and the date in cobalt at 0.82rem on the right.
Hover lights the row one tonal step (raise on paper) and draws the cobalt underline on the name through text-decoration-color; no layout animation.
Every row links to the real credential and names its issuer to assistive tech.

### Signature Components

- **The embedding-space hero (canvas):** a live scatter of topic clusters; the visitor's cursor is the query and the five nearest documents light up in amber with numbered ranks.
It gathers from noise over 1.8s on load and wanders on its own when nobody is pointing.
- **The ScoutFox demo:** a scripted, honest browser-agent run with its own cursor, click pings, checklist and result card, controllable with pause, resume and stop.
It loops only while visible.
- **The pipeline diagrams (inline SVG):** dashed cobalt flow lines that march, bars that fill left-to-right over 1.6s, and amber tokens that drop through layers, all triggered once by a 0.35-threshold intersection observer.

### Motion Grammar

Motion belongs to systems doing work: the hero retrieval field, the agent run, the pipeline flows.
Human-triggered feedback is immediate and small (0.15-0.25s); authored arrivals are 0.7-0.9s on the house ease and happen once.
Loops must stop when offscreen or hidden, and every animation has a reduced-motion path that keeps meaning while removing movement: spatial travel, spins and pulses stop, while opacity, color and state changes that carry the meaning stay.
Loop and reset boundaries dissolve too: the demo's result card fades out over 250ms when a new run starts, never hard-cuts.
The one scroll-triggered arrival allowed beyond the hero is structural: the experience spine draws itself once.
Text and cards never fade or rise on scroll.
The two focal sequences (hero canvas, ScoutFox run) carry the page's authorship; nothing else may compete with them for attention.

**The Powered-On Entrance.**
The page loads like the bench switching on, in a fixed order: the name wipes up from below the baseline (clip-path reveal, 0.7s), the supporting lines rise in their 120ms stagger while the dashed cobalt ring calibrates around the portrait (rotating in from -120 degrees over 1.1s, then handing off to its slow orbit), and the canvas gathers its noise into clusters over 1.8s.
The whole sequence is pure CSS and runs even if scripts fail; under reduced motion the page simply appears already powered on, settled and readable.
New sections must not replay this sequence; the entrance happens once, at load, for the hero only.

## Do's and Don'ts

### Do:

- **Do** keep cobalt for structure and interaction, amber for live attention, green for real success states.
- **Do** keep body text at 1.0625rem over 1.6 leading and cap line length near 58ch.
- **Do** use the radius ladder as written; pick the step that matches the element's role, not its size.
- **Do** ship light and dark values together for any new token.
- **Do** animate systems at work and visitor feedback; keep everything else still.
- **Do** theme the browser's own surfaces (selection, caret, focus, numerals) from the palette.
- **Do** give every new animation a reduced-motion path that keeps the meaning and drops the movement.

### Don't:

- **Don't** introduce decorative gradients; the timeline spine gradient and color-mix transparency fills are the only two, and they are structural.
- **Don't** add a third accent color or let cobalt and amber swap jobs.
- **Don't** put a shadow on anything that sits in the layout flow.
- **Don't** animate a status dot that is not tied to genuinely live data.
- **Don't** fake a success state; the honest-states rule (done, unconfirmed, failed, stopped) is a brand commitment, not a UI detail.
- **Don't** stack entrance animations on scroll; the hero owns the powered-on entrance, and repeated section reveals dilute it.
- **Don't** animate layout-driving properties (width, height, top, left, margins, padding) in new work; move things with transform and opacity. The project row's hover indent is grandfathered.

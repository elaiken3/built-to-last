# Built to Last — EDS-Friendly Muscle Building Program

A mobile-first, single-page workout reference hosted on GitHub Pages. Designed for a woman with Ehlers-Danlos Syndrome (EDS), postpartum clearance, and a history of migraines triggered by neck and shoulder loading.

## Live Site

[View the program](https://your-username.github.io/your-repo-name/)

> Replace with your actual GitHub Pages URL once deployed.

## Who This Is For

- Women with EDS or hypermobility spectrum disorders
- Postpartum (cleared for resistance training)
- Migraine history linked to neck/trap loading
- Home gym: dumbbells and kettlebells only
- 2–3 days/week availability
- Beginner to returning lifter

## What's Inside

A single `index.html` file — no frameworks, no build tools, no dependencies beyond a Google Fonts import. Everything is self-contained and renders correctly on mobile browsers.

### Program Structure

| Tab | Contents |
|---|---|
| Overview | Core principles, avoid/prioritize lists, 12-week phases, Green/Yellow/Red flare system |
| Warmup | 8-minute warmup + 3-minute cooldown (every session) |
| Day A | Squat + Glutes + Supported Upper (floor press, supported row) |
| Day B | Hinge + Single Leg + Upper Back (KB deadlift, split squat, chest-supported row) |
| Day C | Optional third day — circuit or swimmer's posture session |
| Flare Day | 10–15 min red day plan + neck tightness rescue protocol |
| Cue Card | Per-exercise form cues written for EDS compensation patterns |
| Weights | Starting weight ranges, the "Perfect 8" test, progression rules, troubleshooting |

### Key Design Decisions

- **No overhead pressing** — removed entirely due to spine/migraine risk
- **Slow tempo throughout** — 3 sec down, 1 sec pause, smooth up
- **Supported positions prioritized** — chest-supported rows, hand-on-wall single-leg work
- **RPE 6–7 ceiling** — never grinding, never to failure
- **Traffic light system** — Green (full plan) / Yellow (half volume) / Red (flare day only)
- **Double progression** — build reps before adding weight; progress only when all four criteria are met

## Deploying to GitHub Pages

1. Create a new GitHub repository
2. Add `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose `main` branch and `/ (root)`, then click **Save**
6. Your site will be live at `https://your-username.github.io/your-repo-name/` within a minute or two

## Customization

All styles are in a single `<style>` block inside `index.html`. Key values:

| Element | Color Code |
|---|---|
| Dark background | `#2c2520` |
| Gold accent | `#b69d76` |
| Cream background | `#f7f3ee` |
| Stop/warning red | `#c0392b` |
| Green (go) | `#5a9e6f` |
| Yellow (caution) | `#d4aa47` |

To update exercise content, find the relevant `.exercise-card` block inside the appropriate tab panel (`#dayA`, `#dayB`, etc.) and edit the HTML directly.

## Medical Disclaimer

This program was developed based on a detailed personal profile and is intended as a personal reference tool, not general medical advice. Always follow guidance from your physician, OB, or pelvic floor physical therapist. Modify or skip any exercise that causes pain, joint instability, or neurological symptoms.

## License

Personal use only.

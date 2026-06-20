# rf-mobile

An interactive field guide for Baofeng UV-5R-style handheld radios, focused on beginner-friendly radio use in Chula Vista, San Diego County, and general VHF/UHF field communication.

This project is a lightweight static website built with plain HTML, CSS, and JavaScript. It is designed to help a new radio user understand what a Baofeng UV-5R-style handheld can do, what it should not be used for, how to listen safely, how to communicate radio-to-radio legally, and how to think about local frequencies, repeaters, NOAA weather, emergency communications, and programming basics.

## Live Site

GitHub Pages URL:

```txt
https://c9obvi.github.io/rf-mobile/
```

Possible alternate guide route:

```txt
https://c9obvi.github.io/rf-mobile/docs/baofeng/
```

## Project Purpose

The Baofeng UV-5R and similar radios are popular because they are inexpensive, flexible, and widely available. They are also confusing for beginners and easy to misuse.

`rf-mobile` was created as a practical, mobile-friendly guide that answers questions like:

* What do the buttons do?
* How do I talk from one radio to another?
* What frequencies can I listen to?
* What frequencies can I legally transmit on?
* What is the difference between ham, GMRS, FRS, MURS, NOAA, marine, and public safety radio?
* Why can I hear some things but not talk back?
* Why is this not a real police scanner?
* How do I save channels manually?
* What is CHIRP and why would I use it?
* What should I know before pressing the PTT button?

The goal is to turn a confusing handheld radio into something approachable, useful, and safe.

## What This Project Is

`rf-mobile` is an educational static web app / field guide.

It includes:

* Beginner radio walkthrough
* Baofeng UV-5R-style button map
* Basic VFO and memory mode explanation
* Radio-to-radio setup guide
* Simplex frequency guidance
* Local San Diego / Chula Vista frequency references
* NOAA weather radio listening references
* Marine radio listening notes
* Amateur repeater examples
* Manual programming instructions
* CHIRP-style starter channel planning
* “Can I transmit?” decision guidance
* Emergency communication reminders
* Mobile-first layout for quick field use

## What This Project Is Not

This project is not:

* A police scanner
* A dispatch tool
* A trunked radio scanner
* A replacement for official emergency alerts
* Legal advice
* FCC licensing advice
* A guarantee that any frequency is currently active, open, or legal for a specific use
* A substitute for checking current FCC, repeater, NOAA, USCG, ARRL, RadioReference, RepeaterBook, or local emergency communication resources

The guide is intended to help a beginner learn safely and responsibly.

## Important Legal and Safety Notice

A Baofeng UV-5R-style radio can usually receive many VHF and UHF frequencies, but transmitting is regulated.

Do not transmit on frequencies where you are not licensed or authorized.

In general:

* Amateur radio frequencies require an amateur radio license to transmit.
* GMRS requires a GMRS license and proper GMRS-certified equipment.
* FRS is license-free for normal personal/family communication, but requires FCC-certified FRS radios.
* MURS is license-free for certain VHF channels, but requires proper MURS-certified radios.
* NOAA weather frequencies are listen-only.
* Marine channels are not for casual land-based radio-to-radio use.
* Aviation frequencies are not for casual use.
* Public safety frequencies are not for casual use.
* Business, school, hospital, transit, security, government, and utility frequencies are not for casual use.
* Emergency, distress, and calling channels should never be used for testing or casual conversation.

When in doubt, listen only.

## Radio Services Covered

The guide explains the practical difference between common radio services:

| Service               | Typical Use                                                             |                License Needed? | Can a Normal UV-5R Transmit There?               |
| --------------------- | ----------------------------------------------------------------------- | -----------------------------: | ------------------------------------------------ |
| Amateur / Ham Radio   | Hobby, public service, emergency practice, radio-to-radio communication |                            Yes | Yes, only if licensed and within allowed bands   |
| GMRS                  | Family / group communication with higher power than FRS                 |                            Yes | Usually no, unless the radio is GMRS-certified   |
| FRS                   | Family walkie-talkie use                                                |                             No | No, use FRS-certified radios                     |
| MURS                  | Short-distance VHF business/personal communication                      |                             No | No, use MURS-certified radios                    |
| NOAA Weather          | Weather alerts and forecasts                                            |           No license to listen | Listen only                                      |
| Marine VHF            | Boating, distress, navigation safety                                    |            Special rules apply | Listen only from land unless properly authorized |
| Public Safety         | Police, fire, EMS, government                                           |          Authorized users only | No                                               |
| Business / Industrial | Warehouses, facilities, security, maintenance                           | Licensed/authorized users only | No, unless specifically licensed and authorized  |

## Radio-to-Radio Communication

The guide includes a radio-to-radio section for two Baofeng radios.

The simple concept:

1. Both radios must be on the same frequency.
2. Both radios must use the same tone settings, or no tones.
3. Both radios must use compatible bandwidth settings.
4. Both users must be legally allowed to transmit on that frequency.
5. For ham frequencies, both operators generally need amateur radio licenses.
6. For no-license personal use, the better option is usually dedicated FRS or MURS radios, not a standard UV-5R.

For legal ham simplex use, the guide references common amateur simplex calling and working frequencies, while reminding users to listen first, avoid interrupting active traffic, and follow the rules.

## Local San Diego / Chula Vista Focus

This guide is locally useful for the Chula Vista and San Diego County area.

It includes references for:

* NOAA weather radio
* Local VHF/UHF amateur radio use
* Otay Mountain / South Bay repeater examples
* Marine Channel 16 listen-only awareness
* Public safety scanning limitations
* San Diego County radio environment notes

Because repeaters and frequency use can change, local frequency information should be verified before relying on it.

Recommended sources to verify current local information:

* FCC rules and licensing resources
* ARRL band plans
* RepeaterBook
* RadioReference
* NOAA Weather Radio
* U.S. Coast Guard marine VHF guidance
* Local ham radio clubs
* Local ARES / RACES groups
* CHIRP radio programming documentation

## Baofeng UV-5R Notes

The guide is written around Baofeng UV-5R-style radios.

These radios usually support:

* VHF FM receive/transmit ranges around the 2-meter amateur band
* UHF FM receive/transmit ranges around the 70-centimeter amateur band
* Frequency mode
* Memory/channel mode
* Dual display lines
* CTCSS/DCS tones
* Repeater offsets
* Wide/narrow bandwidth settings
* Manual memory programming
* CHIRP programming support on many models

However, UV-5R-style radios also have limitations:

* They are not true public safety scanners.
* They cannot properly follow modern trunked radio systems.
* They cannot decrypt encrypted traffic.
* They are not ideal for fast scanning.
* They can be confusing to program manually.
* Some models/variants may differ.
* Some versions have transmit restrictions depending on firmware, market, or compliance version.

## Features

Current features include:

* Static single-page guide
* Mobile-friendly design
* Beginner-friendly language
* Radio button/function explanations
* Radio-to-radio walkthrough
* Frequency/service comparison
* Transmit caution labels
* Local frequency examples
* Manual programming steps
* CHIRP-style planning notes
* Emergency communication checklist
* Print/PDF-friendly behavior
* Lightweight static hosting through GitHub Pages

## Suggested Future Features

Possible future additions:

* Cleaner `/baofeng/` route
* Separate `style.css` and `app.js` files
* Printable PDF export
* Dedicated mobile emergency card mode
* Offline/PWA support
* Add-to-home-screen support
* QR code for sharing the guide
* More San Diego County repeater references
* Repeater filtering by city/mountain/site
* “Beginner mode” and “Advanced mode” toggle
* Saved personal channel plan using browser local storage
* Exportable CHIRP CSV generator
* Visual radio keypad simulator
* Frequency legality quiz
* GMRS/FRS/MURS buying guide
* Ham license study resource section
* Field checklist for emergencies, road trips, camping, and neighborhood comms
* Spanish-language version for bilingual use
* Dark/light mode toggle

## Project Structure

```txt
rf-mobile/
├── index.html
├── docs/
│   └── baofeng/
│       └── index.html
├── .gitignore
└── README.md
```

The root `index.html` is the main website entry point.

The Baofeng guide also exists under:

```txt
docs/baofeng/index.html
```

Depending on how GitHub Pages is configured, one or both of these may be available:

```txt
https://c9obvi.github.io/rf-mobile/
https://c9obvi.github.io/rf-mobile/docs/baofeng/
```

## Recommended Cleaner Route

A cleaner route would be:

```txt
https://c9obvi.github.io/rf-mobile/baofeng/
```

To create that route, add a root-level `baofeng` folder:

```bash
mkdir -p baofeng
cp docs/baofeng/index.html baofeng/index.html
```

Then commit and push:

```bash
git add .
git commit -m "Add clean Baofeng page route"
git push
```

The guide would then be available at:

```txt
https://c9obvi.github.io/rf-mobile/baofeng/
```

## Hosting on GitHub Pages

This project is designed to work with GitHub Pages.

Recommended GitHub Pages settings:

```txt
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

Because the repository includes a root-level `index.html`, GitHub Pages can serve the site directly from the root folder.

After pushing changes, GitHub Pages usually redeploys automatically.

## Local Development

No build tools are required.

You can open `index.html` directly in your browser, or run a simple local server.

Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```txt
http://localhost:8000
```

Using VS Code, Cursor, or another editor, you can also use a simple live server extension.

## Updating the Site

Basic update workflow:

```bash
git add .
git commit -m "Update radio guide"
git push
```

GitHub Pages will redeploy after the push.

## Common Git Commands

Check the current repo status:

```bash
git status
```

See recent commits:

```bash
git log --oneline
```

Add all changed files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Update guide"
```

Push to GitHub:

```bash
git push
```

Pull latest changes:

```bash
git pull --rebase origin main
```

## Git Ignore

This project should ignore macOS `.DS_Store` files.

Recommended `.gitignore`:

```gitignore
.DS_Store
```

If `.DS_Store` files were already committed, remove them from Git tracking:

```bash
git rm --cached .DS_Store docs/.DS_Store
git commit -m "Remove macOS system files"
git push
```

## Design Philosophy

This project is designed to be:

* Fast
* Simple
* Mobile-friendly
* Practical
* Beginner-oriented
* Clear about legal boundaries
* Useful in the field
* Easy to host
* Easy to modify
* Easy to share

The goal is not to build a complicated radio database. The goal is to give a beginner a useful, responsible, quick-reference tool.

## Why Static HTML?

Static HTML is enough for this project because the guide does not need:

* A backend server
* A database
* Login/authentication
* API keys
* User accounts
* Build tooling
* Package management
* Hosting infrastructure

This makes the project easy to host on GitHub Pages and easy to share from any phone or laptop.

## Possible Improvements to the Codebase

The current project can stay as one HTML file, but if it grows, the next cleanup step would be splitting it into:

```txt
rf-mobile/
├── index.html
├── style.css
├── app.js
├── assets/
│   └── radio.jpg
├── baofeng/
│   └── index.html
└── README.md
```

That would make the project easier to maintain as the guide expands.

## Content Accuracy

Radio information can change.

Frequencies, repeater offsets, tones, local repeater status, public safety systems, and FCC rules should be verified against current sources before use.

Good verification sources include:

* FCC
* eCFR Title 47
* ARRL
* RepeaterBook
* RadioReference
* NOAA Weather Radio
* U.S. Coast Guard
* Local ham clubs
* Local ARES/RACES organizations
* CHIRP documentation

## Responsible Use

Before transmitting:

1. Know what frequency you are on.
2. Know what service that frequency belongs to.
3. Know whether you are licensed or authorized.
4. Know whether your radio is certified for that service.
5. Listen first.
6. Use low power when possible.
7. Identify properly when required.
8. Do not interfere with emergency, public safety, marine, aviation, business, or government communications.
9. Do not use distress channels for testing.
10. When unsure, do not transmit.

## Disclaimer

This project is for educational and personal reference use only.

It is not legal advice, emergency advice, official licensing guidance, or an official frequency coordination source.

The creator is not responsible for misuse of radio equipment, unlawful transmissions, outdated frequency information, repeater access issues, emergency communication failures, or regulatory violations.

Always verify current rules and local frequency information before transmitting.

Use responsibly.

## License

No formal license has been selected yet.

Until a license is added, this project should be treated as a personal educational project. If this project is made public for reuse, consider adding a license such as MIT, Apache-2.0, or Creative Commons depending on whether the goal is code reuse, content reuse, or both.

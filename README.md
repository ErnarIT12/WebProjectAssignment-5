# GYMZONE - Assignment 5

Static fitness website for SE-2508: Umirgaliyev Yernar and Kazybek Karabala.

Open index.html in a modern browser or serve this folder with a local static server.
No installation or build is required. Bootstrap, fonts, images and the sound are local.

## Assignment 5 demonstration

1. Home / Exercise Explorer: filter nine exercises into Upper Body, Lower Body or CrossFit.
2. Home / Movement Gallery: select a thumbnail to change the image, description and guide.
3. Main navigation: focus a link and use arrows, Home or End. On mobile, expand the menu first.
4. Footer / Join GYMZONE: use Next/Back through three form steps; check errors, review and reset.
5. Footer / Sound: enable the preview, then complete a valid profile check for a success tone.
6. Footer / Background: cycle the palettes. The local clock continues updating.

The earlier CSS 3/2/1 cards, Bootstrap grid/cards/navbar/carousel, FAQ and Contact validation remain.

## File responsibilities

- js/main.js: existing behavior, shared validation helpers and popup opening/closing.
- js/exercises.js: exercise objects and methods using switch, find and filter.
- js/advanced.js: keyboard events, dynamic cards, gallery, callback form and sound.
- css/advanced.css: layouts, selected states and event-triggered animations.
- audio/success.wav: original short success sound generated locally.
- ASSIGNMENT5_CHECKLIST.md: requirement mapping.
- DEFENSE_Assignment5_RU.md: Russian explanation and demonstration guide.

## Form and audio behavior

The profile is a frontend demonstration. It creates no account, sends no signup data,
and stores no password. Passwords are cleared after success, reset or closing the popup.
The Contact form validates inputs before opening a configured email application.
Sound starts muted. One audio element prevents overlap; playback requires user interaction.
Animations respect reduced-motion preferences.

## Verification

Chrome and Edge: all eleven pages at 320, 390, 768 and 1440 pixels (88 page/viewport checks).
Tests cover keyboard wrapping, filters, attributes, wizard errors and value retention,
reset, popup dismissal, audio playback/mute/restart and earlier assignment features.

## Publication

The owner handles commit and push. After the existing GitHub Pages workflow finishes,
verify the new features at https://ernarit12.github.io/WebProjectAssignment-4/.
Submit the verified URL, Assignment 5 PDF report and project ZIP through LMS.
Every member submits and attends the defense. No push or deployment was performed here.

See GITHUB_COMMANDS.md for the current repository URL and exact commit/push commands.
The final review also checks malformed emails, declared input length limits, low-height
popup focus/reset behavior and rapid sound toggling.

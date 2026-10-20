# GYMZONE - Assignment 4

Static fitness website for SE-2508: Umirgaliyev Yernar and Kazybek Karabala.

Open `index.html` in a modern browser, or serve this folder with a local static server.
Bootstrap and fonts are bundled locally; no install or build step is required.

## Assignment 4 features

- Home page: Training Questions accordion with smooth transitions.
- Every footer: Join GYMZONE opens a profile form with custom validation.
- Every footer: Background button cycles Forest, Graphite and Midnight.
- Every footer: Current local date and time update every second.
- Contact page: JavaScript validates required fields and email before the existing mailto submission.

Profile validation checks required fields, email, an eight-character minimum password
and matching confirmation. It is a frontend demonstration: it creates no account,
sends no data and stores no password. Closing the popup resets the form.
The contact form needs a configured email application to send the message.

Custom JavaScript: `js/main.js`. Interactive styles: `css/interactive.css`.
Existing responsive layouts and Bootstrap components are retained.

## Manual checks

1. Submit the empty profile form, then test a malformed email, short password and mismatched confirmation.
2. Enter valid demo details; verify the success message and cleared passwords.
3. Close the popup using the close button, Escape and a click outside. Check keyboard focus returns.
4. Open and close FAQ answers; test from the keyboard.
5. Cycle all three backgrounds and observe the live clock updating.
6. Check the contact form, mobile menu, carousel and 3/2/1 training cards.

Verified in Chrome and Edge at 320, 390, 768 and 1440 pixels.

## Publish

Commit and push the project yourself, then wait for the existing GitHub Pages workflow.
Expected URL: https://ernarit12.github.io/WebProjectAssignment-3/
Verify the live Assignment 4 features before submitting the report, project ZIP and URL.

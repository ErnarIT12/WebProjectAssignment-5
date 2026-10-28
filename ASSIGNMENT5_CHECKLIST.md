# Assignment 5 requirement map

| Requirement | Implementation | Demonstration |
| --- | --- | --- |
| DOM selection | initializeExerciseFilters, initializeMovementGallery | Query specific elements and groups |
| Dynamic content | createExerciseCard, renderCategory, renderReview | Generated cards, counts and review text |
| Styling (chosen OR option) | initializeBackgroundButton in js/main.js | Body/CSS variables change on click |
| Attributes (chosen OR option) | selectExercise in js/advanced.js | Thumbnail changes src, alt, href and selection |
| Click listeners | Filter, thumbnail, wizard, sound and reset | Actions without page reload |
| Keyboard events | initializeKeyboardNavigation | Arrows, wrap-around, Home/End in main nav |
| Callback scenario (chosen OR option) | navigateStep(direction, renderCallback) | Three-step form retains inputs with Next/Back |
| Switch | exerciseLibrary.getByCategory and keyboard listener | Category and direction handling |
| Objects and methods | exerciseLibrary in js/exercises.js | Methods return data shown on the page |
| Arrays and explicit loops | items and for...of | Build cards, thumbnails and review rows |
| Higher-order function | filter, find, forEach; existing map | Collection processing through callbacks |
| Sound | initializeSoundEffects / audio/success.wav | Preview, success, mute and no overlap |
| Animations | advanced.css and image.animate | Filters, gallery selection and wizard steps |
| Separation / readability | External HTML, CSS and JS | No inline handlers or script blocks |
| UX / theme | Fitness data, focus, feedback and optional audio | Responsive layouts and accessible states |
| Deployment | Owner's next step | Commit/push and verify Pages before submission |
| Report | Separate Assignment 5 PDF | Steps, real source screenshots, results, tests and reflection |

The alternatives not selected (ratings, language selection, asynchronous POST, etc.)
are examples, not additional requirements. The attributes choice is the thumbnail
gallery; the callback choice is the multi-step form. These choices require no backend.

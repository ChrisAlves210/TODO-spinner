# Wireframes (ASCII)

## Index (Input Tasks)
```
Navbar
-----------------------------------------------------------
Hero (Title + Lead)
Form: [Title][Impact][Urgency][Notes]
Add Task Button | Feedback (aria-live)
-----------------------------------------------------------
Current Tasks (list)            | Weight Formula Card + Go To Spinner
-----------------------------------------------------------
Central CTA Go Spin (disabled until tasks exist)
Footer
```

## Features (Spinner)
```
Navbar
-----------------------------------------------------------
Hero: Spin (Result area + buttons: Spin / Tasks / Selected)
Result aria-live region
-----------------------------------------------------------
Tasks List (scroll)             
Accordion (Help & Tips: 3 items)
Footer
```

## Contact (Selected Task)
```
Navbar
-----------------------------------------------------------
Hero: Selected Task Details
Card: Title | Meta (Impact/Urgency/Weight) | Notes
Buttons: Done (opens modal) | Return | Spin | Tasks
Feedback aria-live region
Modal: Confirm completion (Confirm / Cancel)
Footer
```

## Notes
- Wireframes focus on layout hierarchy rather than pixel dimensions.
- Each interactive component (Toast, Accordion, Modal) placed for clear rubric mapping.
- Accessibility: aria-live regions for dynamic text (feedback/result).

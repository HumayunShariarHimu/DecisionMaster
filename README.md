# DecisionMaster

A Psychological Programme of Decision Making System

## Overview

DecisionMaster is a simple browser-based tool for comparing two choices by listing their pros and cons and assigning each item an importance or concern score.

## Getting Started

No build step is required for the basic app.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select **START!** to begin entering your choices.
4. Add benefits in the **Pros** fields and concerns in the **Cons** fields for each choice.
5. Adjust the sliders from 0 to 10 to rate how important each benefit is and how concerning each drawback is.
6. Select **Calculate!** to view the comparison result.
7. Use **RESET** if you want to clear the form and start again.

## Keyboard Accessibility Checks

Use these manual checks when testing the form with a keyboard, without a mouse:

1. Reload the page and press `Tab` repeatedly. Confirm focus moves through controls in a logical order and that the focused control is visibly indicated.
2. Press `Shift+Tab` to confirm you can move backward through the controls.
3. Confirm each text field and range slider has a meaningful accessible name. Placeholder text alone may not provide a persistent label; report any field whose purpose is unclear to assistive technology.
4. Use the arrow keys to change a focused range slider and verify its displayed value updates.
5. Use `Enter` or `Space` on focused buttons to test **START!**, **Calculate!**, and **RESET**.
6. Check that the result is understandable after calculation and that resetting the form returns controls to their initial values.
7. Record browser, operating system, steps, and expected versus actual behavior for any failure. Do not mark a check as passed unless it was tested.

These are manual checks, not a claim that the interface has passed an accessibility audit. The form currently uses placeholder text for its text inputs, so persistent labels should be considered a follow-up improvement.

## How to Use the Result

Use the score as a prompt for reflection, not as a definitive answer. The result depends on the items and ratings you enter, and it cannot account for every real-world factor.

## Project Files

- `index.html` — the decision comparison form and controls.
- `main.css` — the stylesheet referenced by the page.

## Contributing

If you find an issue or have an idea for improving the instructions or app, open an issue or submit a pull request with a clear description of the change.

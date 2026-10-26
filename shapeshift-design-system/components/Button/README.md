# Button
Two buttons: the green action button for the one call to action, and the blue text button for everything secondary.

- Markup: `<a class="ss-btn ss-btn--action">` or `<button class="ss-btn ss-btn--text">`; the consumer provides the label and the link or handler.
- Poppins 600, 14px, uppercase, 0.08em tracking, padding 16px 32px, `ss-radius`, at least `ss-touch` tall.
- Action: `ss-action` fill, `ss-action-ink` text, 1px `ss-action-edge` border, `ss-action-hover` on hover. One per view.
- Text: `ss-blue` text, no fill.
- Focus: 2px `ss-focus` outline at 2px offset; white inside `NavyBand`.
- Don't: white text on green, green for anything that is not an action, small text on cyan.

# FormField
A labelled text input, `ss-input` (48px) tall, with an optional help or error message.

- Markup: `<div class="ss-field">` holding `<label>`, `<input>` and an optional `<span class="ss-field__msg">`; add `ss-field--error` and `aria-invalid` for errors. The consumer provides the id, label and message text.
- Label: Poppins 600 uppercase at label size, 7px above the input. Groups `ss-3` apart.
- Error: `ss-error-edge` border, message in `ss-error-ink` that says what to fix.
- Don't: placeholder text as the only label, red alone without a message.

# DataTable
A plain table for specifications, schedules and quotes: no fill on the header, a strong navy rule under it, hairline rules between rows.

- Markup: `<table class="ss-table">` with `<thead>`/`<tbody>`; add `class="num"` to right-align figure columns. The consumer provides the rows.
- Header: Poppins 600 at label size, uppercase, 0.1em, `ss-ink`, 2px `ss-navy` bottom rule.
- Cells: Roboto at `small` size, `ss-3` vertical padding, 1px `ss-rule`, tabular numerals; row hover `ss-mist`.
- Don't: zebra stripes, coloured header fills, centred figures.

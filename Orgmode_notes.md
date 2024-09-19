### Basic Navigation and Editing
- **`TAB`**: Cycle visibility of the current section (fold/unfold).
- **`S-TAB`**: Cycle global visibility (fold all, unfold all, fold to headers).
- **`M-RET`**: Insert a new headline or item.
- **`M-S-RET`**: Insert a new headline/item above the current one.
- **`M-LEFT` / `M-RIGHT`**: Promote/demote a headline (change heading level).
- **`M-UP` / `M-DOWN`**: Move the headline or item up or down.

### Structure Editing
- **`C-c C-n`**: Jump to the next headline.
- **`C-c C-p`**: Jump to the previous headline.
- **`C-c C-f`**: Jump to the next item at the same level.
- **`C-c C-b`**: Jump to the previous item at the same level.
- **`C-c C-u`**: Go up to the parent headline.

### Task Management
- **`C-c C-t`**: Cycle through TODO states (e.g., TODO, DONE).
- **`C-c C-s`**: Schedule a task (`SCHEDULED` property).
- **`C-c C-d`**: Set a deadline (`DEADLINE` property).
- **`C-c C-x C-o`**: Log a note for the current headline.
- **`C-c / t`**: Show a sparse tree of TODO items.

### Time Management
- **`C-c .`**: Insert a timestamp (`DATE`).
- **`C-c !`**: Insert an inactive timestamp.
- **`C-c ,`**: Insert a timestamp with time (`DATE TIME`).
- **`C-c C-y`**: Insert a diary entry.

### Markup and Formatting
- **`*bold*`**: Bold text.
- **`/italic/`**: Italic text.
- **`_underline_`**: Underlined text.
- **`+strikethrough+`**: Strikethrough text.
- **`~code~`**: Inline code.
- **`=verbatim=`**: Verbatim text.

### Link and Image Insertion
- **`C-c C-l`**: Insert or edit a link.
- **`C-c C-o`**: Open a link or an inline image.
- **`C-c C-x C-v`**: Preview inline images.

### Tables
- **`C-c |`**: Create a new table.
- **`TAB`**: Move to the next cell in a table.
- **`S-TAB`**: Move to the previous cell in a table.
- **`M-RET`**: Insert a new row in a table.
- **`C-c ^`**: Sort table by column.

### Exporting
- **`C-c C-e`**: Export to various formats (HTML, PDF, LaTeX, etc.).
- **`C-c C-e h h`**: Export to HTML.
- **`C-c C-e l l`**: Export to LaTeX.
- **`C-c C-e p p`**: Export to PDF via LaTeX.

### Capture and Agenda
- **`C-c c`**: Capture a new note or task.
- **`C-c a`**: Open the agenda view.
- **`C-c a t`**: Show global TODO list.
- **`C-c a s`**: Search in agenda files.
- **`C-c a l`**: Show the timeline for the current day.

### Checkboxes and Lists
- **`C-c C-c`**: Toggle checkbox status.
- **`C-c -`**: Cycle the bullet type (e.g., `-`, `+`, `*`).

### Clocking and Time Tracking
- **`C-c C-x C-i`**: Start clocking time on the current task.
- **`C-c C-x C-o`**: Stop clocking time.
- **`C-c C-x C-e`**: Show clock report for the current buffer.

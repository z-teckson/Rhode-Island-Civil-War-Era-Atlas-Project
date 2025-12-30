# Contributing to the Rhode Island Civil War Era Atlas Project

## Data Format

The project uses CSV files for transcribing property owners from Henry F. Walling's 1855 "Map of the State of Rhode Island". Each CSV file corresponds to a map sheet.

### CSV Columns

- `map_sheet`: Name of the map sheet (e.g., "Providence - Part 3")
- `quadrant`: Quadrant identifier within the map sheet (e.g., "A", "B", "C", "D")
- `property_owner`: Name of the property owner as it appears on the map
- `location`: Brief description of location (optional, e.g., "near intersection of Main St and Water St")
- `notes`: Any additional notes (optional)

### File Naming

CSV files are stored in the `/data` directory and named after the map sheet using underscores (e.g., `providence_part_3.csv`).

### Transcribing Steps

1. Locate the high‑resolution scan of the map sheet in `/maps`.
2. Identify the quadrant assigned in the issue.
3. Transcribe **all** property owner names visible in that quadrant.
4. Add each entry to the appropriate CSV file, following the column order above.
5. Commit your changes and open a pull request.

### Quality Checks

- Ensure names are transcribed exactly as they appear (including punctuation and abbreviations).
- If a name is unclear, note it in the `notes` column.
- Do not add duplicate entries; check the existing CSV first.

Thank you for helping to preserve Rhode Island’s history!
# Rec

`rec` is a simple BASH-Script to record what you have done over the day.
The entries are stored in plain-text files in `$HOME/Documents/worklog`.
The text files are named by the current date. Entries are appended to today's
text file.

## Usage

- `rec <TEXT>` - to add a new entry, e.g: `rec "updated postgresql db"`
- `rec` - show entries that were added in the last 2 days

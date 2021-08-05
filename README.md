# piecetable

A barebones carp implementation of a *piece table*, a data structure often used
in text editing. This piece table supports the following operations:

- `insert`: Add a string to the original string associated with the table.
- `remove`: Delete a segment of the original string associated with the table.
- `move`: Move one segment of the original string to another position in the
  string.
- `substitute`: Replace a range of text in the original string with a new
  string.

Once you've performed these operations on a piece table, you can apply the edits
to build the resulting string using `apply-edits`.

Further documentation to come.

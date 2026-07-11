**VLOOKUP** (Vertical Lookup) is an Excel function used to search for a value in the first column of a table and return a corresponding value from another column in the same row.
* limitation: only from left -> right
# EXAMPLE:
=VLOOKUP(C2,$E$2:$F$4,2,FALSE)
Search: C2
In: E2:F4
Return: column 2
Match: exact

**Match** returns the position of the value within a range.
**Index** returns the value located at a specified position in a range.

**XLOOKUP** is an Excel function used to search for a value in one range and return the corresponding value from another range. It is more flexible than VLOOKUP because it can search in any direction and does not require column numbers.
# EXAMPLE:
=XLOOKUP("_",F:F,G:G)


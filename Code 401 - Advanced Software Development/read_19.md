# Automation

# Regular Expression - regex - Python

> a sequence of characters used to check whether a pattern exists in a given text (string) or not
> help manipulte textual data

- **Regex Applications - Examples**:
  - search engines
  - search and replace tools of word processors and text editors
  - Validation of email addresses or passwords

## re library - Functions

- compile()
- search() --> scans the string and looking for the text location
- group() --> returns the string matched
- findall()
- sub()
- split()
- match()
  > returns a match object if the text matches the pattern. Otherwise, it returns None

### Repetitions

{x} --> x times.
{x,} --> x times, at least
{x, y} --> between x and y times

## Code Examples

- > re.search(r'Co.k.e', 'Cookie').group()
  > 'Cookie'

## Notes

- **[abc]** - Matches a or b or c.
- **[a-zA-Z0-9]** - Matches any letter from (a to z) or (A to Z) or (0 to 9).

# shutil

- A python library that is used for high level file opertations, such as:

  - Copying Files
  - Copying File Metadata
  - Working With Directory Trees
  - Finding Files
  - Archives
  - File System Space

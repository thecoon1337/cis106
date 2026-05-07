### How to use Wildcards

- There are 3 Wildcards:
  `*` Matches any number of characters
  `?` Matches only one character
  `[set]` Matches a character from a given set

Wildcards are used when selecting existing files.

### Examples
- `ls *.png` lists all `.png` files.
- `mv *.jpg img/` moves every `.jpg` file into `img/`

### How to use Brace Expansion to create entire directory structures.

- Using the mkdir command
- Follow it with an open brace
- With no spaces, type your string separating entries with a comma
- Close the Brace

### Examples

- `mkdir {music,documents,pictures}` creates 3 directories
- `mkdir -p assets/{imgs,video}/{large,small}` creates multiple categories


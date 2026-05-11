# Left Sidebar Navigation

The left sidebar is controlled entirely by `SUMMARY.md`.

## Basic Structure

```markdown
# Table of Contents

## Section Heading
* [Page Title](path/to/file.md)
* [Another Page](path/to/another.md)

## Another Section
* [Page](file.md)
  * [Nested Page](nested/file.md)
  * [Another Nested](nested/file2.md)
```

## Rules

1. `##` in SUMMARY.md creates **section headings** (non-clickable labels)
2. `*` creates **clickable links**
3. Indent nested items with **2 spaces**
4. All paths are **relative** to the repo root

## Example Output

The above produces this in GitBook's sidebar:

```
SECTION HEADING
  ├── Page Title
  └── Another Page

ANOTHER SECTION
  └── Page
      ├── Nested Page
      └── Another Nested
```

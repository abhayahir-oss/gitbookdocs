# Creating Clear Navigation

Good navigation helps readers find content quickly. GitBook provides two 
types of navigation:

## Left Sidebar Navigation

Defined by your `SUMMARY.md` file. Supports:
- Top-level sections (created with `##` headings)
- Nested pages (indented with two spaces)
- Multiple levels of nesting

## Right-Side Sub-Navigation

GitBook automatically generates a **"On this page"** panel on the right 
side of any page that contains multiple headings (`##`, `###`).

### How to Trigger Right-Side Navigation

Add multiple `##` headings within a single page:

```markdown
## Section One
Content here...

## Section Two
Content here...

### Sub-section 2a
More content...
```

GitBook will list all headings in the right panel, allowing readers to 
jump directly to any section.

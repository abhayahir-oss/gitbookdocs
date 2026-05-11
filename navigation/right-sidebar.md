# Right-Side Sub-Navigation

GitBook automatically builds the right-side "On this page" panel from 
headings within your Markdown file.

## How It Works

When a page has multiple `##` or `###` headings, GitBook lists them 
on the right side so readers can jump directly to any section.

## Example

A page with this content:

```markdown
## Introduction
## Prerequisites  
## Step-by-Step Guide
### Step 1
### Step 2
## Troubleshooting
## Summary
```

Will show this on the right panel:

- Introduction
- Prerequisites
- Step-by-Step Guide
  - Step 1
  - Step 2
- Troubleshooting
- Summary

## Best Practices

- Use `##` for major sections within a page
- Use `###` for sub-sections
- Avoid going deeper than `####`
- Aim for 4–8 headings per page for clean right-nav

## When It Doesn't Appear

The right panel only shows if the page has **more than one heading**. 
Single-heading pages will not show right-side navigation.

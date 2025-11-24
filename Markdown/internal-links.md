# Internal Links & Anchors — Examples

This file demonstrates how to navigate within a single Markdown document using links and anchors.

## Table of Contents
- [Section A](#section-a)
- [Section B](#section-b)
- [Back to top](#top)

<a id="top"></a>

## Section A
Content for section A. Use a link to jump to Section B: [Go to Section B](#section-b).

## Section B
Content for section B. Jump back to the top: [Back to top](#top).

### Explicit HTML anchor example
You can also add an explicit anchor and link to it:

<a id="custom-anchor"></a>

- Link to the explicit anchor: [Custom Anchor](#custom-anchor)

---

Notes on anchor names:
- Most Markdown renderers generate anchors from headings automatically (lowercase, spaces → hyphens).
- If you need a stable anchor across renderers, add an explicit HTML anchor (`<a id="my-id"></a>`).

Navigation: [Index](index.md) • [Overview](overview.md)

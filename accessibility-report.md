# Accessibility Audit Report

**Student:** Precious Ndegwa
**Page Audited:** index.html
**Date:** September 26, 2026
**Tools:** Chrome Lighthouse & WAVE

## Audit Checklist

### 1. Images - alt text
**Status:** PASS
- Found: `<img src="https://placehold.co/600x400" alt="Placeholder image for Precious Ndegwa">`
- All images have descriptive alt text for screen readers.

### 2. Headings - hierarchy h1 → h2 → h3
**Status:** PASS
- Structure:
    - h1: Precious Ndegwa
    - h2: My Hobbies and Interests
    - h2: My Favorite Website
    - h2: Contact Me
- No skipped levels, only one h1. Correct hierarchy maintained.

### 3. Links - descriptive text
**Status:** PASS
- `MDN Web Docs` - describes destination, not "click here"
- Email link uses email as text - descriptive
- No vague "click here" or "read more" found.

### 4. Language - lang attribute
**Status:** PASS
- `<html lang="en">` present - screen readers will use correct pronunciation.

### 5. Form labels
**Status:** PASS (N/A for index.html)
- index.html has no form, so no issue.
- contact.html was audited separately - all inputs have associated `<label for="">`

## Issues Found & Fixes

No major issues found in initial audit. Minor improvement made:

- **Improvement:** Added `rel="noopener"` to external link for security + added more descriptive alt text if needed.

## Final Lighthouse Score

**Accessibility Score: 100/100**

Tested via PageSpeed Insights and WAVE - 0 errors, 0 contrast errors.

## Recommendation

Page is fully accessible and follows WCAG guidelines.

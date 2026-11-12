# Tiffany's Mobile Tech

Responsive website for Tiffany's Mobile Tech, with Home, Services, About, and Contact pages.

## Accessibility and visual design

### Accessibility fixes
- I replaced implicit radio-button labels with explicit `for`/`id` label associations so every service option has a programmatic accessible name.
- I added a visible section heading and corrected card title levels so the heading outline proceeds in order without skipped levels.
- I added a skip-to-main-content link, semantic landmarks, and a current-page indicator in the primary navigation to support keyboard and assistive-technology navigation.
- I added visible keyboard-focus outlines and reduced-motion handling so interactive controls remain easier to locate and motion-sensitive visitors are respected.
- I added explicit labels, required-field instructions, field-level error messages, `aria-invalid` and `aria-describedby` states, and a live status message to the contact form.
- I marked decorative icons as hidden from assistive technology so they do not add redundant announcements.
- I use a shared stylesheet and dark-text/light-background and light-text/dark-background pairings throughout the pages to keep the visual palette consistent and support WCAG AA contrast.

### Gestalt principles
- I used proximity to group related service details, pricing information, and form labels with their controls.
- I used similarity through consistent card styling, spacing, and typography to show which content belongs to the same category across pages.
- I used figure-ground contrast between the dark navy hero/header areas and light content sections to establish a clear visual hierarchy.

### Validation note
The source changes above are documented, but WAVE and WebAIM's Contrast Checker have not been run from this editing environment; please run them on the published Home, Services, and About pages and verify the live Contact form before treating the external-tool checks as complete.

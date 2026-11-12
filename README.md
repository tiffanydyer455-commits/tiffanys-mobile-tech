# Tiffany's Mobile Tech

Responsive website for Tiffany's Mobile Tech, with Home, Services, About, and Contact pages.

## Milestone 2: accessibility and visual design

### Accessibility fixes

- I added a skip link and a main-content target on every page so keyboard users can bypass repeated navigation.
- I marked the current navigation link with `aria-current="page"` and labeled header and footer navigation landmarks.
- I hid decorative brand letters, emoji, and process numbers from assistive technology while retaining meaningful text alternatives in the surrounding content.
- I corrected the home page's duplicated trailing markup and replaced the malformed, duplicated stylesheet with one valid, shared stylesheet.
- I associated page sections and contact panels with descriptive headings and used articles, lists, and landmarks for their intended structure.
- I added visible keyboard focus indicators, underlined text links, and a reduced-motion preference.
- I added explicit labels, required-field instructions, autocomplete hints, and a fieldset with a legend for the service radio group.
- I added inline error messages connected with `aria-describedby`, `aria-invalid` states, focus on the first invalid field, and a live status message.
- I clearly explain that the demo form validates locally and does not transmit or store form submissions.
- I selected dark text and accent colors with at least 4.5:1 contrast on light surfaces and white or mint text with at least 4.5:1 contrast on dark surfaces, meeting WCAG AA for normal text.

### Visual design principles

- **Proximity:** I grouped related service information, form controls, and pricing details into distinct cards with consistent internal spacing.
- **Similarity:** I repeated the same card shape, typography, spacing scale, and accent treatment to show that related offerings belong together.
- **Common region:** I used the same soft teal-tinted background to separate related content sections consistently across every page.
- **Consistent palette:** The shared stylesheet uses midnight navy (`#102a43`), navy (`#243b53`), teal (`#0f766e`), blue (`#1d4ed8`), mint (`#a7f3d0`), and pale neutral surfaces (`#f8fafc`, `#eaf2f4`) on all pages.

### Verification

The pages and stylesheet were reviewed for semantic structure, keyboard focus, form labeling, validation states, and selected WCAG AA color-pair contrast. WAVE and the WebAIM Contrast Checker are external interactive tools and could not be run from this repository-editing session; please run WAVE on the deployed pages and verify the stated color pairs in WebAIM before final submission.

## Responsive layout

The site uses CSS Grid and Flexbox, with layouts tuned for mobile, tablet, and desktop. At narrow widths, navigation wraps, content grids become single-column, and buttons expand to the available width; at tablet and desktop widths, multi-column layouts return where space allows.

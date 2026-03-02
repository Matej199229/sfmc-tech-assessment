Haus of Park Technical Assessment Matej Tinkovic – Responsive Email Development

Overview

This project consists of a fully responsive, table-based HTML email built according to industry-standard email development best practices.

The email was developed with a mobile-first mindset, while ensuring accurate rendering across a wide range of desktop and mobile email clients. The layout and styling were implemented to match the provided Figma creative as closely as possible.

Implementation Details
1. Email Structure & Best Practices

Built using a standard table-based email structure

No <div> elements, floats, flexbox, or modern layout methods

Inline styles applied where required for maximum client compatibility

Nested tables used to control alignment, spacing, and stacking behavior

Total email width does not exceed 600px, following email best practices

All layout decisions were made to ensure maximum compatibility across major clients including Outlook (Windows), Gmail, Apple Mail, and Android mail clients.

2. Responsive Behavior

Designed with a mobile-first approach

Desktop and mobile layouts follow the Figma creative as closely as possible

Stacking behavior is controlled using CSS media queries

Confirmed responsive behavior using Email on Acid testing

Important Note:
Not all mobile clients (especially Outlook and certain Android mail apps) consistently render stacked layouts. Rendering behavior can vary depending on the client’s CSS support.

The code is implemented correctly to stack content on mobile where possible, and this was verified through cross-client testing.

3. Links & CTAs

All images and CTA buttons use the URLs provided in the assignment.

Some URLs appear to be placeholder links and do not resolve to real pages.

No link errors were found in the markup.

It is assumed that non-functional links are intentional for the purpose of this assessment.

4. Copy Edits

There were a few minor typos in the provided copy, which were corrected during development.

Example:

"Explore a wide range of luttle puppies" → corrected to "Explore a wide range of little puppies"

All copy corrections were limited strictly to spelling and obvious typographical errors.

5. Light Mode & Dark Mode Support

Images render correctly in both light and dark modes.

Background colors, text colors, and layout were adjusted to support dark mode using: @media (prefers-color-scheme: dark) { ... }

Important Note:
Dark mode rendering varies significantly by client.

For example:

iPhone Mail applies true dark mode transformations.

Outlook applies its own inversion logic.

These differences are client-controlled and cannot be fully overridden by developers. The email was tested to ensure it behaves appropriately within these constraints.

6. Code Library & Reusable Components

The email was built leveraging a personal code library developed from previous professional email development work.

Some CSS classes (e.g., legacy references such as manulife) may appear in the stylesheet. These are unused remnants from reusable template structures and do not impact rendering or functionality.

This approach reflects real-world email development workflows where modular, reusable code blocks improve efficiency and consistency.

7. Spacing & Padding Implementation

Throughout the email:

Some sections use dedicated spacer <td> elements.

Other sections use padding applied directly to container <td> elements.

Both approaches are valid in email development and were used strategically depending on layout requirements.

In all cases:

The total email width remains within recommended constraints.

No overflow issues occur across tested clients.

Suggested Improvements (Professional Opinion)

8. I have used the font family, font size, colors, ect to the text, links, bg colors, etc as provided in the Figma file.

9. All project files provided in Zip Folder called "Haus of Park Technical Assessment Matej Tinkovic"

1. “Why get a dog at your shelter” Block

The 4-icon layout (2 columns × 2 rows) was implemented exactly as shown in the creative for both desktop and mobile.

However, from a UX perspective:

Stacking the four items vertically on mobile devices may improve readability and visual hierarchy on smaller screens.

While the current layout works correctly and passed testing, a single-column mobile layout may provide a better experience.

This is purely a design suggestion and not a technical limitation.

2. Email Length & Content Density

The email is intentionally large and content-heavy, likely to assess development capability across multiple block types and layout scenarios.

From a real-world marketing perspective:

The overall file size is quite large.

Long emails may be clipped in some Android clients.

The content density may be high for average reader engagement.

In a production environment, I would recommend:

Breaking content into shorter campaign sequences

Reducing total content length

Optimizing for engagement and scroll depth

That said, for the purpose of this technical assessment, the implementation is complete and functions as expected.

Testing

The email was tested using:

Email on Acid

Desktop clients

Mobile devices (where possible)

Rendering was verified across major clients with expected limitations documented above.

Conclusion

This email was built using:

Industry-standard table-based HTML structure

Responsive media queries

Dark mode support

Cross-client compatibility testing

All requirements outlined in the assignment have been addressed.

If any additional adjustments or refinements are required, I would be happy to provide them.
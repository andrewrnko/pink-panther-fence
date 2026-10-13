# Pink Panther Fencing logo - DRAFT

Concept drafts for Andrew to refine. Not final art.

- `logo-mark.svg` - the mark alone: three cedar pickets and two rails in brand pink,
  the middle picket topped with a cap. Reads as a fence at 24px and as a crown at 200px.
- `logo-lockup.svg` - mark + two-line wordmark (PINK PANTHER / FENCING). Static.
- `logo-animated.svg` - the lockup builds itself like a fence install: posts drop in
  one by one, rails slide across, then the name appears. Pure SVG + CSS, plays once,
  works inside an `<img>` tag. Respects prefers-reduced-motion.

The site header and hero use the same geometry from `src/components/Logo.tsx`
(React + GSAP version of the build animation).

Fonts: the wordmark in these SVGs uses `Tactic Sans Expanded` with Impact as the
fallback, so they render right on this machine and in the site. For a portable
file, outline the text in Illustrator before sending anywhere.

TODO (Andrew): decide if the mark should carry a panther element (ears on the cap,
a paw on the rail, or the mascot head). Kept geometric here so it holds up small.

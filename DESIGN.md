---
name: Shamrock Transportation
description: "You fly, I'll drive." A night drive down I-95, signed in interstate green.
colors:
  night: "#0e2a33"
  night-2: "#12343f"
  sign: "#0a6337"
  sign-deep: "#084d2b"
  sign-white: "#f4f7f2"
  leaf: "#3dbb6c"
  amber: "#f6b638"
  focus: "#3d9bff"
  focus-deep: "#1a5fb4"
  paper: "#eef2ee"
  paper-2: "#e2e9e3"
  ink: "#0e2a33"
  ink-soft: "#35505a"
  on-dark: "#f2f6f1"
  on-dark-soft: "#b9cdc7"
  rule: "#c8d4cb"
  rule-dotted: "#b9c8be"
  amber-hover: "#ffc75a"
  white: "#ffffff"
  road-band: "#173c33"
  road-band-2: "#163a37"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(3rem, 15vw, 5.6rem)"
    fontWeight: 850
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(2rem, 8.4vw, 3.4rem)"
    fontWeight: 850
    lineHeight: 1.02
    letterSpacing: "-0.015em"
  phone-number:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(26px, 8vw, 40px)"
    fontWeight: 850
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(21px, 5.6vw, 26px)"
    fontWeight: 750
    lineHeight: 1.3
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(18px, 4.8vw, 21px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.55
  label-sign:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 800
    letterSpacing: "0.12em"
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 800
  button-compact:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
  step-number:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 850
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
  hint:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 600
  wordmark-sub:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 600
    letterSpacing: "0.14em"
rounded:
  sign: "16px"
  sign-inset: "11px"
  control: "12px"
  row: "8px"
  focus: "6px"
  tick: "3px"
spacing:
  gutter: "20px"
  stack: "22px"
  section-top: "44px"
  section-bottom: "64px"
  section-top-wide: "56px"
  section-bottom-wide: "88px"
  column-gap-wide: "64px"
components:
  button-call:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "58px"
  button-call-hover:
    backgroundColor: "#ffc75a"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "58px"
  guide-sign:
    backgroundColor: "{colors.sign}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "7px"
  guide-sign-inset:
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign-inset}"
    padding: "14px 18px 18px"
  faq-row:
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    rounded: "{rounded.row}"
    padding: "14px 4px"
    height: "60px"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "The Night Drive Down I-95"**

The whole page is one drive south at night. The ground is the highway after dark: blue-green, never black. Headlines go up on interstate guide signs, and interstate green is also shamrock green, so the mark and the road share one colour. Headlight amber is the only warm light on the page. It belongs to the Call button and the road's centre line, and nothing else in the interface. Between sections, the light "sign-back aluminum" bands work like the backs of road signs: cool, matte, plain.

Density is low and sizes are large on purpose. The audience is mostly 60+, on a phone, often inside Facebook's in-app browser. Body text is 18px, buttons are 58px tall, and nothing relies on hover. The one interactive set piece is the road canvas. A packed cream car drives itself past state-line signs, and the reader can drag to steer it and push it along. It is something to play with, and the page never asks anyone to use it.

The world rejects the trucking-company template: no fleet photos, no quote forms, no badges. Type is the system font stack in heavy weights (750–850). Section headlines are uppercase. Lettering on the signs is mixed case, the way real guide signs are lettered.

**Key Characteristics:**
- Blue-green night ground with cool aluminum light bands. No pure black anywhere as a surface.
- Guide-sign panels (green, white inset border, rounded) carry the headlines that matter most.
- One warm colour, amber, reserved for calling and for the centre line.
- Interstate-shield blue appears only when something is hovered or focused.
- Animated lane-line seams stitch every section change.
- Heavy system sans with big tap targets, built for older eyes and thumbs.

## Colors

The palette is a night highway: a blue-green ground, sign green, cool aluminum, one headlight amber, and a shield blue that appears only on interaction.

### Primary
- **Interstate Guide Green** (sign): the field of every guide sign: the hero headline sign, the "You'll know who's driving" sign, the state-line signs drawn on the canvas, and the small square bullets in the services list. It is also shamrock green. Use it for signage, never as a button fill.
- **Sign Edge Green** (sign-deep): the sign panel's 2px bottom edge, which gives it thickness. It also outlines the roof luggage in the trunk illustration.
- **Sign White** (sign-white): legend colour on green. Use it for the inset border, sign lettering, the phone number on the Ed sign, and canvas road-edge lines (at 80% alpha). It is a raw literal in the source, repeated 13 times, and is not yet on `:root`.

### Secondary
- **Headlight Amber** (amber): the Call button fill, the road canvas centre line (dashed 16/16), lane-line seams that cross into or out of the night ground, and `::selection`. Text on amber is always ink.

### Tertiary
- **Interstate Shield Blue** (focus): hover borders and `:focus-visible` outlines on dark grounds.
- **Deep Shield Blue** (focus-deep): the same role on light grounds, dark enough for 3:1 against paper.
- **Shamrock Leaf** (leaf): the clover mark only (wordmark and favicon). Not an interface colour.

### Neutral
- **I-95 Night** (night): page ground, hero, and close section. The same value is **Ink** (ink): text on light sections, the numbered step discs, text on amber.
- **Night Shoulder** (night-2): footer ground, one step lighter than the page.
- **Sign-back Aluminum** (paper): the primary light section ground.
- **Weathered Aluminum** (paper-2): the second light band (rates and FAQ), so two light sections in a row still read as separate.
- **Road Grey-Green** (ink-soft): secondary text on light grounds, and the FAQ plus/minus disc.
- **Headlight Haze** (on-dark): text on night. **Dim Haze** (on-dark-soft): secondary text on night, the wordmark subline, the footer.
- **Guardrail** (rule): solid 2px FAQ dividers. **Guardrail Dotted** (rule-dotted): 2px dotted dividers in the services list.

### Named Rules
**The One Headlight Rule.** In the interface, amber is used only for the call action and the road centre line (the canvas centre dash and the lane-line seams that cross the night ground). Don't use it for links, borders, icons, headings, or a second button. The only amber outside the interface is the cargo box in the two car drawings, which is what "packed" looks like at that size.

**The Blue Only Moves Rule.** Interstate-shield blue appears only as a response to the pointer or keyboard: hover borders, focus outlines, underline colour on footer links. It is never at rest. The one exception is the I-95 route shield's own red/white/blue, because that is a real road artefact.

**The Never Black Rule.** Dark grounds are blue-green night (night, night-2), never #000. Black appears only as low-alpha shadow inside the canvas and under the sign.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** Same stack
**Label/Mono Font:** None. There is one family.

**Character:** One family, set heavy. Weight 850 for headlines, 750–800 for titles, labels, and buttons, 400 for reading text. It reads like highway lettering. The stack is a deliberate house-style choice for this pitch site: there is no webfont request, and every device gets its own native sans. Roboto is in the stack only as the Android fallback.

### Hierarchy
- **Display** (850, clamp(3rem, 15vw, 5.6rem), 0.98, -0.02em): mixed case. Used only on the hero guide sign ("You fly. / I'll drive."), one phrase per line.
- **Headline** (850, clamp(2rem, 8.4vw, 3.4rem), 1.02, -0.015em, uppercase, balanced wrap): section headlines, both on paper and on the Ed sign.
- **Phone Number** (850, clamp(26px, 8vw, 40px)): the cell number on the Ed sign. Set as big as a headline, because the number is the product.
- **Title** (750, clamp(21px, 5.6vw, 26px), 1.3): services list items. The same weight runs at fixed 20px for FAQ questions and 21px/1.25 for step titles.
- **Lede** (400, clamp(18px, 4.8vw, 21px), 1.5, max 38ch): the paragraph under a section headline. The hero promise is a lede variant (17–20px, max 34ch).
- **Body** (400, 18px, 1.55): FAQ answers (max 60ch), step descriptions. 18px is the floor for reading text.
- **Sign Label** (800, 18px, 0.12em tracking, uppercase): the direction word beside the route shield ("SOUTH" / "NORTH").
- **Small** (16px footer, 15px/600 canvas hint): the only text below 18px, and never for content someone has to act on.

### Named Rules
**The System Stack Rule.** Use the native system sans and nothing else. Don't add a webfont, a display face, or a serif. Hierarchy comes from weight, size, and case.

**The Signs Speak Mixed Case Rule.** Lettering on a guide sign is mixed case (except the route direction word). Section headlines off the sign are uppercase.

## Layout

The page is a single column of full-bleed bands inside a 1120px container with a 20px gutter. On phones every section stacks. At 760px and up:
- the hero splits 1.15fr / 1fr (sign on the left spanning two rows, promise and buttons on the right, aligned to the bottom)
- "What I do / How it works" and "Rates / Questions" become two columns with a 64px gap
- the Ed sign caps at 860px wide

Section padding is 44px top / 64px bottom on phones and 56 / 88 at 760px and up. The default vertical gap inside sections is 22px (lede margin is 18px, gap before the buttons 26px).

The road canvas is a full-bleed band under the hero copy: 236px tall on phones, 340px from 760px, 380px from 1100px.

Breakpoints:
- **≤379px** compacts the buttons: 12px padding, 17px text, and the icon on the Text button is hidden
- **760px** switches to the two-column layout
- **1100px** gives the road band more height
- **`(hover:hover) and (pointer:fine)`** hides the Text button, since `sms:` does nothing on most desktops

### Named Rules
**The Two Buttons Max Rule.** A contact cluster holds at most two buttons: Call (amber), then Text (outline). The hero and the closing section repeat the same pair. Don't add a third channel or a duplicate.

**The No Sticky Bar Rule.** There is no sticky or fixed bottom call bar. Call is reachable from the hero, the Ed sign, the close section, and the footer.

## Elevation & Depth

The page is flat with one exception. Paper sections and night sections don't use shadows: depth comes from the change between night and aluminum, plus the seams. The guide sign is the only lifted surface, because a real sign stands off its post. Inside the road canvas, every object (cars, trees, houses, signs, the plane) casts a small offset shadow at 18–35% black. That is the canvas's own top-down lighting, not UI elevation.

### Shadow Vocabulary
- **Sign Lift** (`box-shadow: 0 14px 30px -12px rgba(0,0,0,.55), 0 2px 0 #084d2b`): guide-sign panels only. The diffuse part lifts the panel off the ground. The 2px same-hue lip is the panel's metal edge, always sign-deep and never black.

### Named Rules
**The Only Signs Stand Up Rule.** Only guide-sign panels get elevation. Buttons, FAQ rows, and sections stay flat.

## Shapes

Corners are soft but never pill-shaped. Signs are 16px outside and 11px on the inset. The inset is a 3px sign-white border set 7px in from the panel edge, so the two radii stay concentric. Buttons are 12px. FAQ rows are 8px, which shows on the hover/focus outline. Focus rings are 6px. Circles mean either a count (the 44px ink step discs) or a toggle (the 30px FAQ plus/minus ring). Section edges are never straight lines: every section change is a wavy edge drawn by the seam.

## Components

### Buttons
Large, direct, and only for the thumb.
- **Shape:** gently rounded (12px), 58px minimum height, 18px/800 label, a 22px inline SVG icon (phone or chat) 10px before the label, no wrapping.
- **Call (primary):** amber fill and border, ink text, label "Call 732-300-3835" with the number written out. On a phone it is the wider column (`minmax(0,1fr) auto`).
- **Text (ghost):** transparent fill, on-dark text, 2px border at 55% haze. Opens `sms:` with a pre-filled message. Hidden on fine-pointer devices.
- **Hover / Focus:** hover applies only under `(hover:hover)`. Call lightens to #ffc75a and its border turns shield blue. The ghost button's border turns shield blue and its text goes white. Focus is a 3px shield-blue outline, 3px offset. Transitions: background and border .2s, transform .15s. Active state nudges down 1px.

### Guide Sign (signature)
The house component, and the system's headline device.
- **Structure:** a green panel (7px padding, 16px radius, Sign Lift shadow), then an inset with a 3px sign-white border at 11px radius, then content in sign-white.
- **Hero variant:** a route-marker row (the I-95 shield SVG, 38×40, plus the direction word as the Sign Label, which flips between SOUTH and NORTH by season), then the Display headline, one phrase per line.
- **Content variant (Ed):** inset padding 24/20 on phones, 40/44 wide. Holds a Headline, a Lede in sign-white, and the Phone Number link: a 3px underline at 50% white that turns shield blue on hover, 48px minimum height.
- **Canvas variant:** state-line signs drawn in the road ("Welcome to / Georgia"). Same green, a 1.5px sign-white inset stroke, 4px radius, 700-weight system type at 12.5–13.5px.
- On paper sections, focus outlines inside the sign switch to sign-white.

### Seams (signature)
A lane line rolling along the top edge of the next section.
- **Form:** an SVG 1200×64 viewBox stretched full width, 44px tall (64px at 760px and up), overlapping the previous band by its own height. The fill path takes the next section's ground (`--next`). The stroke is a 3px dashed lane line (26 on, 22 off, round caps) in `--lane`.
- **Wave:** `y = 34 + 9·sin(x/190 + 0.55t + φ) + 5·sin(x/83 − 0.9t + 2φ)`, sampled every 20 units, with φ = 1.7 × seam index so no two seams match.
- **Motion:** the dash offset travels at 46 units/s (`SEAM_SPEED`). It runs only while on screen (IntersectionObserver feeding one shared rAF loop) and is static under reduced motion.
- **Colour:** an amber lane when the seam crosses into or out of night. A muted grey-green lane (#9fb3a8) between the two aluminum bands, where amber would be a third call to action.

### Road Canvas (signature)
A top-down night highway the reader can take the wheel of.
- **Scene:** a winding two-lane road. Ground warms from cool green in Jersey to warmer green in Florida. Shoulder gravel #5b6a6c, asphalt #2c3439, sign-white edge lines at 80%, an amber centre dash 16/16. Reflector posts light up within 190px ahead of the headlights. Trees go pine to oak to palm as the car moves south, with eight states at 900px each. A house sits at each end of the trip, and a plane passes overhead now and then. The packed cream car (#e9e2cf) has an additive headlight beam.
- **Interaction:** drag sideways to push the car (up to 900px/s). It settles back to a 120px/s cruise. The finger's height picks the car's lane line, and the car springs back to its lane on release. Trees within 80px of the finger bend away on springs. A "Drag to drive" hint fades out on first touch. `touch-action:none` applies only inside the band.
- **Tunable constants:** CRUISE 120, MAX_SPEED 900, SEG 900, TREE_GAP 22, PUSH_R 80, SPRING 38, DAMP 6.5, road width 60px phone / 78px wide (phone = canvas under 700px), devicePixelRatio capped at 2. At each end it pauses 2.2s and reverses. Direction is southbound from September to February and northbound from March to August.
- **Reduced motion:** draws a single static frame and hides the hint.

### FAQ
Native `<details>` rows with plain answers.
- **Rows:** 2px solid guardrail top and bottom rules. The summary is the Title style (20px/750), at least 60px tall, padded 14px 4px, with the 8px row radius.
- **Toggle:** a 30px ring (2px ink-soft) with a 12px plus that turns into a minus as the vertical bar rotates (.25s).
- **Hover / Focus:** a 3px deep shield-blue outline at 2px offset around the whole row, and the ring border turns the same blue. Answers are body text at max 60ch.
- The first, most trust-building question is open by default.

### Lists
- **Services:** Title-weight lines between 2px dotted guardrail rules, each led by a 12px sign-green square (3px radius).
- **How it works:** a numbered list. The counters are 44px ink discs with 20px/850 sign-white numerals, beside a 21px title and an ink-soft description.

### Navigation
None. A wordmark bar sits at the top: a 34px clover, "Shamrock Transportation" at 17px/800, and a 14px/600 uppercase tracked subline ("Owner & driver: Ed Brannagan") in dim haze. The bar does not stick.

## Do's and Don'ts

### Do:
- **Do** put the headline that matters most on a guide sign: green, 3px sign-white inset border, 16/11px concentric radii, Sign Lift shadow.
- **Do** keep amber for Call and the centre line. Text on amber is always ink.
- **Do** show blue only on hover (gated behind `(hover:hover)`) and focus. Use deep shield blue on aluminum and sign-white focus inside green signs.
- **Do** stitch every change of ground with a seam whose fill is the next section's colour.
- **Do** keep reading text at 18px or larger, buttons at 58px tall or more, and FAQ rows at 60px or more.
- **Do** run every animation on the shared loop, pause it off screen, and draw a static frame under `prefers-reduced-motion`.
- **Do** write icons as inline SVG symbols that inherit `currentColor`.

### Don't:
- **Don't** add a webfont or a second family. The system stack is the house style.
- **Don't** add a sticky or fixed bottom call bar.
- **Don't** put more than two contact buttons in a cluster, or add a second amber element to the interface.
- **Don't** use blue at rest as a link colour, accent, or fill.
- **Don't** use #000 or near-black as a ground. Night is blue-green.
- **Don't** put a tracked uppercase label above a section headline. Tracked uppercase appears in only two places: the route direction word beside the shield inside a guide sign, and the wordmark subline.
- **Don't** add shadows to buttons, rows, or sections. Only signs stand up.
- **Don't** use stock fleet photos, quote forms, or trust badges.

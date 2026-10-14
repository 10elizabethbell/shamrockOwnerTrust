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
  amber-hover: "#ffc75a"
  focus: "#3d9bff"
  focus-deep: "#1a5fb4"
  paper: "#eef2ee"
  ink: "#0e2a33"
  on-dark: "#f2f6f1"
  on-dark-soft: "#b9cdc7"
  white: "#ffffff"
  rule: "#c8d4cb"
  rule-dotted: "#b9c8be"
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
    lineHeight: 1.35
  question:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 750
    lineHeight: 1.35
    letterSpacing: "0"
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(18px, 4.8vw, 21px)"
    fontWeight: 400
    lineHeight: 1.5
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(17px, 4.9vw, 20px)"
    fontWeight: 400
    lineHeight: 1.45
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
  wordmark:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "0.01em"
  wordmark-sub:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 600
    letterSpacing: "0.14em"
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
rounded:
  sign: "16px"
  sign-inset: "11px"
  control: "12px"
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
    backgroundColor: "{colors.amber-hover}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "58px"
  button-ghost-hover:
    textColor: "{colors.white}"
  guide-sign:
    backgroundColor: "{colors.sign}"
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign}"
    padding: "7px"
  guide-sign-inset:
    textColor: "{colors.sign-white}"
    rounded: "{rounded.sign-inset}"
    padding: "14px 18px 18px"
  qa-pair:
    textColor: "{colors.ink}"
    typography: "{typography.question}"
    padding: "20px 0"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "The Night Drive Down I-95"**

The whole page is one drive south at night. The ground is the highway after dark: blue-green, never black. The headlines that matter most go up on interstate guide signs, and interstate green is also shamrock green, so the mark and the road share one colour. Headlight amber is the only warm light on the page. It belongs to the Call button and the road's centre line, and nothing else in the interface. The light "sign-back aluminum" band reads like the back of a road sign: cool, matte, plain.

The page is calm and short on purpose. Its readers are mostly 40 to 70, on a phone, often inside Facebook's in-app browser, and they found an earlier, busier version confusing. So there is one moving thing on the page, the packed cream car driving the road band. The road is scenery to watch, not a toy: it takes no touch, the page scrolls straight over it, and nothing on the page asks to be tapped open. Body text is 18px, buttons are 58px tall, every word is visible on arrival, and nothing depends on hover.

The world rejects the trucking-company template: no fleet photos, no quote forms, no badges. Type is the system font stack set heavy (750–850). Section headlines are uppercase. Lettering on the guide signs is mixed case, the way real guide signs are lettered.

**Key Characteristics:**
- Blue-green night ground with one long cool-aluminum light run. No pure black anywhere as a surface.
- Guide-sign panels (green, white inset border, rounded) carry the headlines that matter most.
- One warm colour, amber, reserved for calling and for the centre line.
- Interstate-shield blue appears only when something is hovered or focused.
- Only the car moves. Seams, sections and text are still.
- Everything is visible: no accordions, no tabs, no tap-to-reveal.
- Heavy system sans with big tap targets, built for older eyes and thumbs.

## Colors

The palette is a night highway: a blue-green ground, sign green, cool aluminum, one headlight amber, and a shield blue that appears only on interaction.

### Primary
- **Interstate Guide Green** (sign): the field of every guide sign (the hero headline sign, the "You'll know who's driving" sign, the state-line signs drawn on the canvas) and the small square bullets in the services list. It is also shamrock green. Use it for signage, never as a button fill.
- **Sign Edge Green** (sign-deep): the sign panel's 2px bottom edge, which gives it metal thickness. It also outlines the roof luggage in the trunk illustration.
- **Sign White** (sign-white): legend colour on green: the 3px inset border, sign lettering, the phone number on the Ed sign, the I-95 shield face, focus rings inside a sign, and canvas road-edge lines (80% alpha) and reflector dots (30%). It is a raw literal in the source, not a `:root` property.

### Secondary
- **Headlight Amber** (amber): the Call button fill and border, the road canvas centre line (dashed 16/16), the lane line on both seams (each crosses into or out of the night ground), and `::selection`. Text on amber is always ink.
- **Lit Amber** (amber-hover): the Call button's hover fill, under `(hover:hover)` only.

### Tertiary
- **Interstate Shield Blue** (focus): hover borders and `:focus-visible` outlines on dark grounds; the underline colour of hovered footer links and the Ed phone number.
- **Deep Shield Blue** (focus-deep): the same role on aluminum, dark enough for 3:1 against paper.
- **Shamrock Leaf** (leaf): the clover mark only (wordmark and favicon). Not an interface colour.

### Neutral
- **I-95 Night** (night): page ground, hero, and close section. The same value is **Ink** (ink): all text on aluminum (headlines, ledes, services, questions and answers) and text on amber. There is no secondary grey text on light grounds.
- **Night Shoulder** (night-2): footer ground, one step lighter than the page.
- **Sign-back Aluminum** (paper): the one light ground. Pack it full, the Ed sign, and What I do / Good to know sit on one continuous aluminum run.
- **Headlight Haze** (on-dark): text on night; at 55% alpha it is the Text button's outline. **Dim Haze** (on-dark-soft): secondary text on night (the wordmark subline, the closing lede, the tagline, the footer).
- **White** (white): the Text button's label on hover only.
- **Guardrail** (rule): solid 2px rules framing the Good to know pairs. **Guardrail Dotted** (rule-dotted): 2px dotted rules between services.
- **Road Band** (road-band to road-band-2): the vertical gradient behind the canvas, visible before the first frame paints.

### Named Rules
**The One Headlight Rule.** In the interface, amber is used only for the call action and the road centre line (the canvas centre dash and the lane line on the seams). Don't use it for links, borders, icons, headings, or a second button. The only amber outside the interface is the cargo in the two car drawings, which is what "packed" looks like at that size.

**The Blue Only Responds Rule.** Interstate-shield blue appears only as a response to the pointer or keyboard: hover borders, focus outlines, underline colour on hovered links. It is never at rest. The one exception is the I-95 route shield's own red, white and blue, because that is a real road artefact.

**The Never Black Rule.** Dark grounds are blue-green night (night, night-2), never #000. Black appears only as low-alpha shadow under the sign and inside the canvas.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial)
**Body Font:** Same stack
**Label/Mono Font:** None. There is one family.

**Character:** One family, set heavy. Weight 850 for headlines, 750–800 for titles, questions, labels and buttons, 400 for reading text. It reads like highway lettering. The stack is a deliberate house-style choice for this pitch site: no webfont request, every device gets its own native sans. Roboto is in the stack only as the Android fallback.

### Hierarchy
- **Display** (850, clamp(3rem, 15vw, 5.6rem), 0.98, -0.02em): mixed case. Only on the hero guide sign ("You fly. / I'll drive."), one phrase per line.
- **Headline** (850, clamp(2rem, 8.4vw, 3.4rem), 1.02, -0.015em, uppercase, balanced wrap): section headlines on aluminum, on night, and on the Ed sign.
- **Phone Number** (850, clamp(26px, 8vw, 40px), -0.01em): the cell number on the Ed sign, set near headline size because the number is the product.
- **Title** (750, clamp(21px, 5.6vw, 26px), 1.3): services list lines.
- **Question** (750, 20px, 1.3, no tracking): the h3 of each Good to know pair.
- **Lede** (400, clamp(18px, 4.8vw, 21px), 1.5, max 38ch): the paragraph under a section headline, 18px below it.
- **Promise** (400, clamp(17px, 4.9vw, 20px), 1.45, max 34ch): the one-line promise beside the hero sign.
- **Body** (400, 18px, 1.55): Good to know answers (max 60ch) and the closing tagline (italic, dim haze). 18px is the floor for reading text.
- **Sign Label** (800, 18px, 0.12em, uppercase): the direction word beside the route shield ("SOUTH" / "NORTH", by season).
- **Button** (800, 18px; 17px under 380px wide): Call and Text labels.
- **Wordmark** (800, 17px, 1.1) with **Wordmark Sub** (600, 14px, 0.14em, uppercase) beneath it.
- **Small** (400, 16px): the footer. The footer's name and links step back up to 18px.

### Named Rules
**The System Stack Rule.** Use the native system sans and nothing else. Don't add a webfont, a display face, or a serif. Hierarchy comes from weight, size, and case.

**The Signs Speak Mixed Case Rule.** Lettering on a guide sign is mixed case, except the route direction word. Section headlines off the sign are uppercase.

## Layout

A single column of full-bleed bands inside a 1120px container with a 20px gutter. The page runs, top to bottom: wordmark bar; hero (sign, promise, contact pair) over the road band; a seam into aluminum; Pack it full; the Ed sign; What I do beside Good to know; a seam back into night; the close; the footer. Five content blocks, one light run, one dark close.

On phones everything stacks. At 760px and up:
- the hero splits 1.15fr / 1fr (sign on the left spanning two rows, promise and buttons on the right, aligned to the bottom)
- Pack it full splits 1.1fr / 1fr, copy beside the trunk drawing
- What I do and Good to know sit side by side, 1fr / 1fr with a 64px gap
- the Ed sign caps at 860px wide

Section padding is 44px top / 64px bottom on phones and 56 / 88 at 760px and up. Blocks that follow another block on the same ground close up (the Ed band opens at 8px, the services band at 8px) so the aluminum run reads as one surface. The default vertical gap inside a section is 22px (lede margin 18px, gap before the closing buttons 26px).

The road band sits full bleed under the hero copy: 236px tall on phones, 340px from 760px, 380px from 1100px.

Breakpoints:
- **≤379px** compacts the buttons: 12px padding, 17px text, 8px gap, the Text button's icon hidden
- **760px** switches to the split layouts
- **1100px** gives the road band more height
- **`(hover:hover) and (pointer:fine)`** hides the Text button, since `sms:` does nothing on most desktops

### Named Rules
**The Two Buttons Max Rule.** A contact cluster holds at most two buttons: Call (amber), then Text (outline). The hero and the close repeat the same pair. Don't add a third channel or a duplicate.

**The No Sticky Bar Rule.** There is no sticky or fixed call bar. Call is reachable from the hero, the Ed sign, the close, and the footer.

**The Nothing Hidden Behind A Tap Rule.** No accordions, tabs, carousels, "read more" or tap-to-reveal. Every question shows its answer in full. If text is worth having on the page, it is visible on arrival; if it isn't, cut it.

## Elevation & Depth

The page is flat with one exception. Aluminum and night sections use no shadows: depth comes from the change between night and aluminum, and from the seams. The guide sign is the only lifted surface, because a real sign stands off its post. Inside the road canvas, the car, trees, houses and state signs cast small offset shadows at 28–35% black. That is the canvas's own top-down lighting, not UI elevation.

### Shadow Vocabulary
- **Sign Lift** (`box-shadow: 0 14px 30px -12px rgba(0,0,0,.55), 0 2px 0 #084d2b`): guide-sign panels only. The diffuse part lifts the panel off the ground. The 2px lip is the panel's own metal edge, always sign-deep and never black.

### Named Rules
**The Only Signs Stand Up Rule.** Only guide-sign panels get elevation. Buttons, lists, question pairs and sections stay flat.

## Shapes

Corners are soft but never pill-shaped. Signs are 16px outside and 11px on the inset; the inset is a 3px sign-white border set 7px in from the panel edge, so the two radii stay concentric. Buttons are 12px. Focus rings are 6px. Service bullets are 12px squares at 3px. Section edges are never straight lines: each change of ground is a wavy edge drawn by a seam.

## Components

### Buttons
Large, direct, and only for the thumb.
- **Shape:** gently rounded (12px), 58px minimum height, 18px/800 label, a 22px inline SVG icon (phone or chat) 10px before the label, no wrapping.
- **Call (primary):** amber fill and border, ink text, label "Call 732-300-3835" with the number written out. On a phone it takes the wider column (`minmax(0,1fr) auto`).
- **Text (ghost):** transparent fill, on-dark text, 2px border at 55% haze. Opens `sms:` with a pre-filled message. Hidden on fine-pointer devices.
- **Hover / Focus:** hover applies only under `(hover:hover)`. Call lightens to lit amber and its border turns shield blue. The ghost's border turns shield blue and its text goes white. Focus is a 3px shield-blue outline at 3px offset. Transitions: background and border .2s, transform .15s; pressing nudges the button down 1px.

### Guide Sign (signature)
The house component, and the system's headline device.
- **Structure:** a green panel (7px padding, 16px radius, Sign Lift), an inset with a 3px sign-white border at 11px radius, content in sign-white.
- **Hero variant:** a route-marker row (the I-95 shield SVG at 38×40 plus the Sign Label direction word, which flips SOUTH/NORTH by season), then the Display headline, one phrase per line.
- **Content variant (Ed):** inset padding 24/20 on phones, 40/44 wide. Holds a Headline, a Lede in sign-white, and the Phone Number link: a 3px underline at 50% sign-white that turns shield blue on hover, 48px minimum height. Focus outlines inside the sign are sign-white.
- **Canvas variant:** the state-line signs drawn in the road ("Welcome to / Georgia"): same green, a 1.5px sign-white inset stroke, 4px radius, 700-weight system type at 12.5px (phone) or 13.5px.

### Seams (signature)
A still lane line along the top edge of the next section.
- **Form:** an SVG with a 1200×64 viewBox stretched full width, 44px tall (64px at 760px and up), overlapping the band above by its own height. The fill path takes the next section's ground (`--next`). The stroke is a 3px dashed lane line (26 on, 22 off, round caps) in `--lane`.
- **Wave:** `y = 34 + 9·sin(x/190 + φ) + 5·sin(x/83 + 2φ)`, sampled every 20 units, with φ = 1.7 × seam index so no two seams match. Drawn once on load; it never animates.
- **Colour:** amber lane on both seams, because each one crosses into or out of night.

### Road Canvas (signature)
A top-down night highway band: scenery to watch, never a control.
- **Scene:** a winding two-lane road across eight states (New Jersey to Florida, 900px of road each). Ground warms from cool green in Jersey to warmer green in Florida. Shoulder gravel, asphalt, sign-white edge lines at 80%, an amber centre dash 16/16, still reflector dots at 30% sign-white. Trees go pine to oak to palm on the way south. A house sits at each end of the trip. The packed cream car (#e9e2cf, amber and green cargo) carries an additive headlight beam.
- **Motion:** the car drives at a steady CRUISE of 110px/s from one house to the other, pauses 2.5s, turns round and drives back. The camera and lane position ease in; nothing else in the scene moves. Direction starts southbound September to February and northbound March to August.
- **Input:** none. No drag, no steering, no hint, no `touch-action` override: the page scrolls normally over the band.
- **Running:** one shared requestAnimationFrame loop (frame time capped at 50ms), paused whenever the band is off screen. Road width 60px when the canvas is under 700px wide, 78px otherwise; devicePixelRatio capped at 2.
- **Reduced motion:** draws one still frame.

**The One Moving Thing Rule.** Only the car moves. Seams, text, illustrations and sections never animate, reveal on scroll, or loop; the only other change on the page is state feedback (colour shifts and a 1px press) in direct response to a touch, hover or keyboard focus.

### Lists
- **Services:** Title-style lines between 2px dotted guardrail rules, each led by a 12px sign-green square (3px radius).
- **Good to know:** two plain question/answer pairs. Each is a Question h3 (20px/750) above a body paragraph (max 60ch), with a 2px solid guardrail rule above the first pair and below every answer. Always open; no toggle, no icon.

### Navigation
None. A wordmark bar sits at the top: a 34px clover, "Shamrock Transportation" in Wordmark, and the uppercase tracked Wordmark Sub ("Owner & driver: Ed Brannagan") in dim haze beneath. The bar does not stick.

### Close and Footer
- **Close:** on night. Headline (seasonal: "Heading south this winter?" / "Heading home this spring?"), a lede in dim haze that carries the rates line, the contact pair (max 520px), then the card tagline in italic body.
- **Footer:** night shoulder ground, 16px dim haze, the name and phone link in on-dark at 18px. Links have a 2px underline at 4px offset, 44px minimum height, and take a shield-blue underline on hover.

## Do's and Don'ts

### Do:
- **Do** put the headline that matters most on a guide sign: green, 3px sign-white inset border, 16/11px concentric radii, Sign Lift shadow.
- **Do** keep amber for Call and the centre line. Text on amber is always ink.
- **Do** show blue only on hover (gated behind `(hover:hover)`) and focus. Use deep shield blue on aluminum and sign-white focus inside green signs.
- **Do** stitch every change of ground with a still seam whose fill is the next section's colour.
- **Do** keep reading text at 18px or larger and buttons at 58px tall or more.
- **Do** show every answer in full, on arrival.
- **Do** keep the car the only moving thing: run it on the shared loop, pause it off screen, and draw a still frame under `prefers-reduced-motion`.
- **Do** write icons as inline SVG symbols that inherit `currentColor`.

### Don't:
- **Don't** add a second moving thing: no rolling seams, scroll reveals, marquees, looping illustrations, or extra traffic in the road.
- **Don't** make the road band interactive or capture touch on it. It is scenery; the page must scroll over it.
- **Don't** hide text behind a tap: no accordions, tabs, carousels or "read more".
- **Don't** add a webfont or a second family. The system stack is the house style.
- **Don't** add a sticky or fixed call bar.
- **Don't** put more than two contact buttons in a cluster, or add a second amber element to the interface.
- **Don't** use blue at rest as a link colour, accent, or fill.
- **Don't** use #000 or near-black as a ground. Night is blue-green.
- **Don't** put a tracked uppercase label above a section headline. Tracked uppercase appears in only two places: the route direction word beside the shield inside a guide sign, and the wordmark subline.
- **Don't** add shadows to buttons, lists, question pairs or sections. Only signs stand up.
- **Don't** use stock fleet photos, quote forms, or trust badges.

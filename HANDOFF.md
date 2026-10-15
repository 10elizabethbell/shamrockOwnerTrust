# Shamrock Transportation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockOwnerTrust/ · **Repo:** https://github.com/10elizabethbell/shamrockOwnerTrust · **Built:** 2026-10-14 from Muse brief of 2026-10-13 (Vibe 2, owner-operator trust, approved by Ellie 2026-10-14)

## What's built
- **The look: a roadside scene on I-95 at dusk.** The hero is a green guide sign (shamrock green `#0a6337`, a green rim outside its white border) standing on two steel posts, seen down the road: dusk sky (night blue fading to twilight), a warm glow on the horizon, a treeline, and the road running toward the sign with white edge lines and an amber centre line. All of it is still; nothing moves. The hero is the only sign on the page. The rest of the page is pale aluminum and blue-green night (`#0e2a33`, not black). Amber only for Call buttons and road centre lines.
- **Roadside sign hero (Ellie, 2026-10-15):** "make it look like it's actually a road sign on a road", with scenery outside the sign and the sign farther away. Scene parts: `.posts` (treeline, glow, posts at 30%/70% where the road edges meet the horizon) and `svg.ground` (grass, road). Sign size: `.hero-copy` margin/max-width.
- **More color (Ellie, 2026-10-15: "I hate the lack of color"):** the hero became the green sign. The driver sign briefly went blue, then Ellie dropped it ("the blue goes with nothing and the repeated signs feel ugly"), so Meet your driver is now plain on aluminum.
- **Quiet hero (Ellie, 2026-10-14):** headline, one line ("I drive your car between New Jersey and Florida, door to door."), one big "Call for a free quote / 732-300-3835" button, an "or send a text" link, and "Owner & driver: Ed Brannagan". No sign panel and no motion in the hero.
- **The one moving part:** a short road strip just above the closing call. A packed cream car drives steadily south past "Welcome to Delaware … Florida" signs, house to house, pauses, then drives back north. Nothing else moves and nothing needs touching. Speed and spacing (`CRUISE`, `SEG`, `TREE_GAP`) are at the top of the road script.
- **Section edges:** still dashed lane lines.
- **Sections, following the 40–70 research brief (Ellie, 2026-10-14):**
  - Header: name; on desktop also "Meet your driver / How it works / Questions" and the phone number.
  - Hero (above). **Two photo spots for Ed, both standing still (Ellie, 2026-10-15):** on desktop a wide "Photo of Ed with a car" placeholder fills the right half; on phones a small round face sits beside "Owner & driver". To add photos, swap each placeholder for the `<img>` line in the HTML comment above it: `ed-wide.jpg` (wide, 4:3) and `ed.jpg` (head and shoulders, used for both the round face and the sign).
  - Meet your driver: no sign, plain on the pale background. A dashed "Portrait of Ed" placeholder sits on an offset shamrock-green block (above the text on phones, beside it on desktop), then dark headline and text, and the phone number in shamrock green. Ed in his own words, tap-to-call number. To add the photo, drop `ed.jpg` in the folder and swap the placeholder for the `<img>` line in the HTML comment above it.
  - How it works: Call for a quote → Arrange pickup → Receive your car, beside What I do.
  - Driven, not trucked: the packing point, with the side-view drawing of the packed car.
  - Questions, always visible: cost, packing, the spring trip home, when a truck carrier is better. A comment in the HTML marks where the insurance answer goes once Ed confirms.
  - Close: the road strip, "Heading south this winter?", the phone number in large type (tap to call), and Send a text on phones. The yellow Call button there was removed (Ellie, 2026-10-15); the big number does that job.
  - Footer: name, Ed, service area, phone.
- **Season-aware:** March–August the close reads "Heading home this spring?" and the car starts northbound.
- **Contact:**
  - `tel:+17323003835` everywhere; the number is always visible as text.
  - **Sticky Call button on phones (this site only, Ellie's call):** a small "Call Ed" pill at the bottom right. It appears once the hero button scrolls away and hides when the closing buttons are on screen. This is a deliberate exception to the no-sticky-bar house rule.
  - "Send a text" opens a text that's already filled in: "Hi Ed, I'd like my car driven from ___ to ___ around ___." Hidden on computers, where `sms:` links do nothing.
- **Page details:**
  - About 33 KB, single file, no photos.
  - Favicon and iPhone home-screen icon: a white clover on sign green.
  - Link-preview image: `og.png` (1200x630), regenerated for the new hero.
## Assumptions I made
- **Packing the car ("Driven, not trucked") is a selling point.** The brief made it the #1 differentiator. It's inferred from how driveaway works, not from Ed. **Confirm he's fine with packed cars and whether there are weight or contents limits.**
- **"I'm the one behind the wheel" / "You call my cell, not a dispatcher".** The brief names Ed as the only known driver. Confirm he drives every job himself.
- **"I pick it up at your door" / "Delivered to your Florida door".** Based on the brief's "door-to-door" trust idea.
- **The airport line is the card's verbatim wording ("Airport services anywhere in Florida").** I left what that means vague on purpose (meeting the customer with their car? passenger rides?).
- **The Questions answer about when a truck carrier is better** comes from the competitor pattern the brief pointed to (drivecartoflorida.com), written in Ed's voice.
- **Colors:** I didn't have the card photo, so I used sign green `#0a6337` and leaf green `#3dbb6c` for the clover. Sample the real green from the card once it's cleared.
- **The clover mark is my own drawing**, not the card's emblem. The brief says to check with Ellie before using a card scan publicly.
- **I picked the look myself, from 6 options I listed.** The run was unattended, so there was no Impeccable decision page and no comparison against other directions.

## Placeholders and gaps
- **No photos at all.** Nothing of Ed, his vehicle, or any job. Three visible placeholders wait for Ed's photos (desktop hero, phone owner line, Meet your driver); don't hand the site over with any still empty.
- **No logo file** (the card emblem isn't cleared).
- **No email and no Facebook.** So, against the usual rules: no footer email, and no "see more of my work" Facebook link. Add both if Ed has them.
- **Rates:** $1 per mile (Ed, via Ellie, 2026-10-15), shown in How it works step 1, the "What does it cost?" answer and the closing line. The hero doesn't show it. The page doesn't say what the price includes, and gives no example trip total.
- **Insurance, driver vetting, hours, years in business, reviews:** none are on the page, on purpose.
- **Texting:** the brief says "accepts texts: unknown". The Text button is a guess. If Ed doesn't text, delete both `.js-sms` buttons; Call can stand alone.

## Questions for Ed (Thursday)
1. Rates: $1 per mile. Does that include fuel, tolls, lodging and your trip back? Is there a minimum? Can we print an example (e.g. a typical NJ to Florida total)?
2. Insurance: what covers the car and the things inside it while you drive? (Snowbirds will ask first. It's the biggest gap.)
3. Do you take texts?
4. Any packing limits (weight, valuables, nothing on the roof)?
5. What does "Airport services anywhere in Florida" mean in practice?
6. Do you drive every car yourself? Do you ever bring a second driver?
7. Can we use the shamrock from your card? We need two photos: a wide one of you with a car (or at the wheel) for the top of the page, and a head-and-shoulders portrait for Meet your driver. Plates and customers' faces will be blurred.
8. Hours or season windows, years doing this, and any customers willing to be quoted.
9. youflyilldrive.com is unregistered. Want it registered and pointed here?

## Simplified for the 40–70 audience (Ellie, 2026-10-14)
Ellie: "too much, overwhelming, and confusing", so I kept the look and made it calmer:
- Taken out of the road: drag-to-steer and push, trees bending under the finger, oncoming traffic, the plane, and the "Drag to drive" hint. The road no longer grabs touches, so scrolling over it works normally.
- Section edges stopped moving.
- Removed "How it works" (thin steps that repeated the hero), the separate Rates section (now one line in the close), the tap-to-open FAQ rows, and two FAQ answers that repeated other sections (packing, airports).
- This deliberately overrides the house rules that the signature element reacts to touch and that the hero lets the visitor do the job. Ellie asked for it on this site; I haven't changed the house rules themselves.

## Research brief applied (Ellie, 2026-10-14)
From Ellie's "Website UX Research & Design Brief, ages 40–70": kept the look, adopted the structure (Meet your driver, a 3-step How it works, Call for a free quote, phone number in the header and close, plain-text FAQ incl. cost) and the sticky Call pill. Not adopted, because the facts don't exist yet: reviews, insurance terms, credentials, what the price includes (fuel, tolls, lodging, return travel), years of experience, Ed's portrait. Each is a Thursday question. Fonts stay the system stack (the brief suggests Inter, Source Sans 3 or Atkinson Hyperlegible; swapping would be easy).

## Ideas not built (yours to pick)
- **Runner-up look: "Departure board."** A split-flap airport board for "You fly", with NJ → FL flights and the car as the "arrival". Less touchable than the road.
- **Highway Gothic lettering:** self-host Overpass (open licence, based on Highway Gothic) for the sign text only. It breaks the system-font house rule, so I didn't.
- **A moving top edge for the road band**, like the other section edges (currently a straight edge).

## Impeccable pass
- Ran every mode except live and onboard, plus the finish reviewer. Fixes applied:
  - truthful copy: no arrival-timing promise, no claims about competitors, no unlimited-packing promise;
  - focus outlines that meet 3:1 on light and green backgrounds;
  - 14–15px minimum text;
  - hover effects only on devices that hover;
  - reduced-motion and screen-reader fixes;
  - the packed car redrawn so it reads as a car.
- Detector warnings left standing on purpose:
  - Roboto: it's only a fallback in the system font stack (suppressed in `.impeccable/config.json`).
  - Tight line height: display headings only.
  - "Shape-assembled illustration": the packed-car drawing. A real photo of Ed's car would replace it.

## Not verified
- Real-device scrolling and layout on iOS/Android, including inside Facebook's in-app browser (tested only in headless Chrome).
- Whether the `sms:` text arrives already filled in on a real iPhone or Android.
- Frame rate of the road on older phones.
- Live Pages URL returns 200 with the current page (checked by fetch, not opened in a phone browser).

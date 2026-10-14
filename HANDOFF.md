# Shamrock Transportation — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockOwnerTrust/ · **Repo:** https://github.com/10elizabethbell/shamrockOwnerTrust · **Built:** 2026-10-14 from Muse brief of 2026-10-13 (Vibe 2, owner-operator trust, approved by Ellie 2026-10-14)

## What's built
- **The look: I-95 at night.** The page ground is a blue-green night color (`#0e2a33`, not black). The headline sits on a green interstate guide sign: interstate green is shamrock green, so it carries the brand. The sign has an I-95 shield and SOUTH, and the hero headline is **"You fly. I'll drive."**, taken from the domain on Ed's card (youflyilldrive.com).
- **The moving part (in the hero, under the buttons):** a top-down night highway.
  - A packed cream car drives itself south past "Welcome to Delaware … Florida" signs, from a house in NJ to a house in FL, then turns around and drives back north.
  - Oncoming headlights, roadside reflectors that light up in the beams, and a plane overhead every ~20 s.
  - Dragging steers the car into any part of the road and pushes it faster. Trees bend away from the finger or mouse.
  - The scenery changes from pines to palms as you go south.
  - Its tunable constants (`CRUISE`, `MAX_SPEED`, `SEG`, `TREE_GAP`, `PUSH_R`) are at the top of the road script.
- **Section edges:** animated dashed lane lines, all sharing one animation loop.
- **Sections:**
  - Hero: sign, promise, Call + Text.
  - Pack it full: a side-view drawing of the car with a suitcase on the roof, boxes and golf clubs inside, and Ed at the wheel.
  - "You'll know who's driving.": a second guide sign with Ed's name and a tap-to-call number.
  - What I do, and How it works (4 steps).
  - Very reasonable rates.
  - Questions: the truck-carrier answer is open by default.
  - A closing call.
  - Footer: name, Ed, phone.
- **Season-aware:** March–August the sign reads NORTH, the close reads "Heading home this spring?", and the car starts northbound.
- **Contact:**
  - `tel:+17323003835` everywhere.
  - The Text button opens a text that's already filled in: "Hi Ed, I'd like my car driven from ___ to ___ around ___." It's hidden on computers, where `sms:` links do nothing.
- **Page details:**
  - 40 KB single file with no photos.
  - Favicon and iPhone home-screen icon: a white clover on sign green.
  - Link-preview image: `og.png` (1200x630).

## Assumptions I made
- **"Pack it full" is a selling point.** The brief made it the #1 differentiator. It's inferred from how driveaway works, not from Ed. **Confirm he's fine with packed cars and whether there are weight or contents limits.**
- **"I'm the one behind the wheel" / "You call my cell, not a dispatcher".** The brief names Ed as the only known driver. Confirm he drives every job himself.
- **"I pick it up at your door" / "Delivered to your Florida door".** Based on the brief's "door-to-door" trust idea.
- **The airport line is the card's verbatim wording ("Airport services anywhere in Florida").** I left what that means vague on purpose (meeting the customer with their car? passenger rides?). The FAQ just says "Tell me your flight when you call."
- **The FAQ answer about when a truck carrier is better** comes from the competitor pattern the brief pointed to (drivecartoflorida.com), written in Ed's voice.
- **Colors:** I didn't have the card photo, so I used sign green `#0a6337` and leaf green `#3dbb6c` for the clover. Sample the real green from the card once it's cleared.
- **The clover mark is my own drawing**, not the card's emblem. The brief says to check with Ellie before using a card scan publicly.
- **I picked the look myself, from 6 options I listed.** The run was unattended, so there was no Impeccable decision page and no comparison against other directions.

## Placeholders and gaps
- **No photos at all.** Nothing of Ed, his vehicle, or any job.
- **No logo file** (the card emblem isn't cleared).
- **No email and no Facebook.** So, against the usual rules: no footer email, and no "see more of my work" Facebook link. Add both if Ed has them.
- **Rates:** the page only says "Very reasonable rates" (card wording) and "call for a price". No numbers.
- **Insurance, driver vetting, hours, years in business, reviews:** none are on the page, on purpose.
- **Texting:** the brief says "accepts texts: unknown". The Text button is a guess. If Ed doesn't text, delete both `.js-sms` buttons; Call can stand alone.

## Questions for Ed (Thursday)
1. Rates: a flat NJ↔FL price, or per trip? Is that okay to publish?
2. Insurance: what covers the car and the things inside it while you drive? (Snowbirds will ask first. It's the biggest gap.)
3. Do you take texts?
4. Any packing limits (weight, valuables, nothing on the roof)?
5. What does "Airport services anywhere in Florida" mean in practice?
6. Do you drive every car yourself? Do you ever bring a second driver?
7. Can we use the shamrock from your card? Do you have a photo of yourself, and of your car if you have one? It would go in the "You'll know who's driving" sign.
8. Hours or season windows, years doing this, and any customers willing to be quoted.
9. youflyilldrive.com is unregistered. Want it registered and pointed here?

## Ideas not built (yours to pick)
- **Runner-up look: "Departure board."** A split-flap airport board for "You fly", with NJ → FL flights and the car as the "arrival". Less touchable than the road.
- **Arrival moment:** when the car pulls into the Florida house, the porch light comes on just as the plane passes overhead ("it's there when you land", told visually instead of promised).
- **Highway Gothic lettering:** self-host Overpass (open licence, based on Highway Gothic) for the sign text only. It breaks the system-font house rule, so I didn't.
- **More road-sign touches below the hero:** the How-it-works numbers as mile markers or exit tabs, sign brackets/rivets.
- **The car in "Pack it full" could react:** tap or drag to load bags, or a little bounce on the suspension.
- **Desktop:** the Ed sign is capped at 860px and the Rates column has space under it. Ed's photo would fill the right half of the sign.
- **Keyboard steering:** arrow keys on the canvas (`tabindex=0`), for keyboard users.
- **A moving top edge for the road band**, like the other section edges (currently a straight edge).
- **Old phones:** cap the canvas resolution at 1.5x, or run the section edges at 30fps on low-core devices.

## Impeccable pass
- Ran every mode except live and onboard, plus the finish reviewer. Fixes applied:
  - truthful copy: no arrival-timing promise, no claims about competitors, no unlimited-packing promise;
  - focus outlines that meet 3:1 on light and green backgrounds;
  - 14–15px minimum text;
  - hover effects only on devices that hover;
  - reduced-motion and screen-reader fixes;
  - cheaper canvas drawing;
  - the packed car redrawn so it reads as a car.
- Detector warnings left standing on purpose:
  - Roboto: it's only a fallback in the system font stack (suppressed in `.impeccable/config.json`).
  - Tight line height: display headings only.
  - FAQ padding: false positive.
  - "Shape-assembled illustration": the packed-car drawing. A real photo of Ed's car would replace it.

## Not verified
- Real-device touch on iOS/Android, including inside Facebook's in-app browser (tested only with simulated touch in headless Chrome).
- Whether the `sms:` text arrives already filled in on a real iPhone or Android.
- Frame rate on older phones.
- Live Pages URL returns 200 with the current page (checked by fetch, not opened in a phone browser).

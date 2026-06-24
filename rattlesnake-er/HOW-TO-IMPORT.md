# 🐍 Rattlesnake ER — Colorado (Coco's emergency vet map)

A ready-to-import map of 24/7 emergency veterinary hospitals across Colorado that
can treat **dog rattlesnake bites**. Import it once into **Google My Maps** and the
pins show up in the regular Google Maps phone app under **Saved → Maps**, where you
can tap any clinic to **call** or **navigate** instantly.

## ⚠️ Read this first (the 60-second version)

A rattlesnake bite is a **time emergency**. If Coco is bitten:

1. **Stay calm and keep her calm/still** — movement spreads venom faster. Carry her if you can.
2. **Do NOT** apply a tourniquet, cut the wound, try to suck out venom, or apply ice. These make it worse.
3. **Call ahead** to the nearest clinic on this map *while you drive* — tell them
   "suspected rattlesnake bite, en route" so they prep antivenom.
4. **Confirm they have crotalid antivenom in stock.** Most ER vets carry it, but stock
   fluctuates and almost none publish it — so every pin here says "Call to confirm."
   If the nearest one is out, the next pin is already on your map.

Antivenom-stocking 24/7 ERs are concentrated on the **Front Range** (Denver, Boulder,
Longmont, Fort Collins, Colorado Springs). The **mountains have sparse coverage** — see
the notes on those pins for the nearest real option.

## How to import into Google My Maps (one time, ~1 minute)

1. On a computer, go to **https://www.google.com/mymaps** and click **Create a new map**.
2. Click **Import** under the layer name.
3. Upload **`rattlesnake-er-colorado.csv`** (from this folder).
4. When asked which columns to position the pins by, choose **`MapLocation`** ⭐
   (this column has the clinic name + clean address, which Google geocodes most
   reliably — do NOT pick `Address`, which keeps suite numbers that can trip up geocoding).
5. When asked which column to title the markers, choose **`Name`**.
6. Rename the map something like **"🐍 Rattlesnake ER — CO"** and (optional) style pins
   by the **`Priority`** column so true-24/7 clinics stand out.
7. After import, check the layer says **"32 features."** If Google reports any rows
   "could not be drawn," click that notice — it lists which addresses to fix by hand
   (usually just re-type the street into the search box for that pin).

### To get it on your phone
Open the **Google Maps app → Saved → Maps tab** → your new map appears there.
Tap any pin → **Call** or **Directions**. Works the same on Android and iPhone.

## Columns in the CSV
- **Name** — clinic name
- **Address** — full street address (used to place the pin)
- **Phone** — call this
- **Hours** — ⭐ whether it's truly 24/7 vs. limited hours (read carefully)
- **Antivenom** — almost always "Call to confirm" (see note above)
- **Priority** — `24/7` (rely on it any hour) / `Limited hours` / `Daytime/transfer only`
- **Area** — region, for filtering
- **Notes** — drive-time hints, "nearest real option," etc.
- **Website** — clinic site

## ❌ Closed — do NOT drive here (still appear in old lists / map searches)
These showed up in searches but are confirmed closed as of 2026 — they're left **off**
the map on purpose so you don't waste minutes on them:
- **VCA Highlands Ranch Animal Specialty & Emergency** (5640 County Line Pl) — closed Mar 31, 2026; records moved to VCA Alameda East.
- **VCA Veterinary Specialists of Northern Colorado** (Loveland, 201 W 67th Ct) — closed Mar 31, 2026; records moved to VCA Fort Collins.
- **Aspen Meadow Veterinary Specialists** (Longmont, 104 S Main St) — permanently closed. For Longmont use BluePearl Lafayette or CASE Boulder.

## Coverage gaps you should know about
- **Estes Park:** no 24/7 vet in town. Drive down to Loveland (Four Seasons) or Fort Collins (CSU / FCVEH).
- **Grand Lake / Granby / Winter Park:** worst-covered area — no 24/7 ER in Grand County. Any true 24/7 ER is ~2 hrs (Steamboat has 24-hr on-call clinics, or Front Range). Stabilize at Granby Vet first.
- **Pueblo / Cañon City:** Pueblo's ER is after-hours only (not round-the-clock weekdays); Cañon City has no overnight ER — drive to Colorado Springs.

## Tip: bookmark the live antivenom locators
Stock changes constantly. To check who has antivenom *right now*:
- veterinarysnakebite911.com/antivenin-locator
- crofab.com/locating-and-ordering/locate-crofab

## Keeping it current
Hours, phone numbers, and even whether a clinic still exists drift over time.
**Re-verify every few months**, especially before snake season (≈ April–October).
Last compiled: 2026-06-24.

*This is a logistics aid, not veterinary advice. In a real emergency, call a vet.*

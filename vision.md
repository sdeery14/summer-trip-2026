# Summer Trip 2026 — Vision Document

## Purpose

This repository is a decision-support system for planning a ~1 week summer trip for two people. We use Claude Code in non-interactive mode to research, plan, and generate decision-support documents organized as features using spec kit. The goal is to have well-researched information in front of us so we can make confident decisions — not to have Claude make decisions for us.

## Who

- Two partners, both athletic and avid outdoors people, traveling from Arlington, MA.
- She is a serious climber (V10 boulderer). He plays basketball, football, rugby, and is learning mountain biking and road biking.
- Together: hiking, backpacking, car camping, canoeing, white water rafting, cross-country skiing (new).
- Recently completed a 10-day car camping trip to Yosemite and Sequoia — hiked 10+ miles daily, bought food at Walmart, left day-to-day plans flexible around major movement days. It was amazing but they wish they had done slightly more research on trails and activities beforehand.

## Trip Overview

- **When:** Late summer 2026 (targeting best conditions — likely late July through early September). Exact dates flexible.
- **Duration:** ~1 week on the ground.
- **Travel:** Fly from Boston area, rent a car at destination.
- **Style:** Car camping as the base mode. Interested in backcountry backpacking if a compelling 1-2 night option presents itself. Not looking for hotels or glamping.
- **Budget mindset:** We are not on a strict budget. We make enough to cover this trip comfortably. Our goal is to spend smart — we value convenience and maximizing time doing fun things, but we don't want to overpay for anything. Pay for the thing that makes the trip better (a well-located campsite, a rental car that handles dirt roads, a guided rafting trip). Skip the thing that's overpriced for what it is. Research should surface prices so we can see what things cost, but should NOT filter out options just because they're expensive. Flag value, not limits.

## Destination Candidates

Research and produce decision-support documents for **two destination options**. We will choose between them once we can compare the information side by side.

### Option A: Greater Yellowstone Loop

A multi-park road trip, potentially: Airport → Yellowstone → Beartooth Highway → Grand Tetons → Airport. Similar structure to last year's Yosemite → Sequoia trip.

### Option B: Glacier National Park

Potentially a single-park deep dive. May have nearby areas worth including — research should clarify whether Glacier alone fills a week or if adjacent areas (Flathead National Forest, Bob Marshall Wilderness, etc.) should be part of the plan.

## What We Value

### Going deeper, not wider

We want to see the major attractions that everyone sees, but we do NOT want to stop there. We are willing to put in the miles, wake up early, and do the research to get away from crowds and into real nature. A lesser-known ridge with solitude is worth more to us than a famous overlook with 200 people. We go home proud of ourselves and with great memories.

### Physical challenge

We are fit and want to be physically challenged. 10+ mile days are standard for us. Elevation gain is welcome. We want to come home tired and satisfied, not feeling like we held back.

### Flexibility with structure

We want major logistics planned (where we sleep each night, major driving days, permit-dependent activities). But day-to-day hiking and activity choices should be presented as menus of options so we can decide in the moment based on weather, energy, and mood.

### Celebration

This trip is a celebration — he finished school and got a better job, she is doing incredible things with climbing, and their lives are moving toward marriage. This should feel special. A brewery at the end of a hard day, a sunset from a place they earned — those moments matter.

## Activities to Research

### Primary
- **Day hiking:** Ranging from 8–20 miles, varied terrain and difficulty. Include both iconic/popular trails and lesser-known gems. For each trail, note: distance, elevation gain, trailhead parking situation, crowd level, and what makes it special.
- **Backpacking:** 1–2 night backcountry options in case we want to push ourselves. Include permit requirements, bear safety considerations, water sources, and difficulty. We have gear (bear canister, backpacking equipment) and experience with backcountry cooking/food storage, but this would be our first time in grizzly territory for overnight trips.
- **Car camping:** Campsite options for each night. Include both reservable and first-come-first-served. Note reservation windows, booking links, and backup options.

### Secondary
- **Bouldering:** Outdoor bouldering areas near the parks. She climbs V10 — include areas with problems in the V4–V10 range. Research pad rental options since we are flying and cannot bring pads.
- **Mountain biking:** Rental shops and beginner-to-intermediate trail options near the parks. He is still learning so nothing extreme.
- **White water rafting / canoeing:** Guided or rental options in the area. Note pricing and how to book.
- **Scenic drives:** Beartooth Highway, Going-to-the-Sun Road, etc. Best times to drive them, what to stop for.

### Treats
- **Breweries:** Local craft breweries near the parks or in gateway towns.
- **Food:** Good burger spots, banh mi if it exists out there, pubs, and any local gems. We like tasty, filling, reasonably priced. Bonus points for that black-metal-aesthetic-with-wood-furniture vibe.
- **Grocery:** Walmart or equivalent near the parks for stocking up on trip food.

## Logistics to Research

### Flights
- Boston (BOS) to nearest airports for each destination option. For Yellowstone loop: Bozeman (BZN), Jackson Hole (JAC), or others. For Glacier: Kalispell/Glacier Park International (FCA) or others.
- Target late summer dates. Flag price ranges and whether flexibility on exact dates saves significant money.

### Rental Car
- Needs to be suitable for park roads and trailhead access. Research whether 4WD/AWD is needed or recommended for either destination.
- Pickup and dropoff — same airport or could a one-way rental make the route better?

### Permits & Reservations
- **Backcountry permits:** How to get them, lottery vs. first-come-first-served, key dates and deadlines, links to the actual permit systems.
- **Campsite reservations:** When do they open for late summer 2026? Links to recreation.gov or park-specific booking. Strategy for getting sites (book at midnight on opening day, etc.).
- **Park entrance fees:** Cost, whether an America the Beautiful pass is worth it.
- **Vehicle entry reservations:** Some parks (like Glacier) have timed entry. Research whether this applies in 2026.

### Bear Safety in Grizzly Country
- We have bear spray experience (videos, not formal training) and own a bear canister. We cook away from camp.
- Research should cover: what we already know vs. what we need to learn, any recommended formal resources or briefings at the parks, where to buy bear spray near the airport (can't fly with it), regulations for each park.

### Gear We Need to Acquire There
- Bear spray (cannot fly with it — where to buy near airport/park).
- Bouldering pad rental.
- Mountain bike rental.
- Any other gear that's flight-restricted or rental-makes-sense.

## Planning Style & Output Format

### Decision Support, Not Decisions

Every output document should present **options with trade-offs**, not a single "here's your itinerary." We want to see:
- 2–3 options where applicable, with pros and cons.
- Key facts (distance, cost, difficulty, crowd level).
- A recommendation with reasoning, but always with alternatives.

### Day-by-Day Menus

For each day of the trip, produce a menu of hiking/activity options rather than a single prescribed plan. Group by effort level (chill day, standard day, big day) so we can choose in the moment.

### Links and Actionable Info

Include links to booking sites, permit applications, maps, and resources. We use CalTopo, Gaia GPS, and AllTrails for mapping — include trail names and locations that we can look up in those tools.

### Feature Structure

Each major research area is a feature with its own spec and output. The vision doc (this file) provides the shared context that every feature spec references. Features should be runnable independently via `claude -p` in non-interactive mode.

## Timeline Awareness

It is currently March 2026. Some campsite and permit reservations may already be open or opening soon. Research should flag any time-sensitive deadlines so we don't miss booking windows.

## What Success Looks Like

When this repo is done, we should be able to:
1. **Choose a destination** by comparing two well-researched option documents side by side.
2. **Book everything** using the links and timing info in the logistics docs.
3. **Show up prepared** with bear safety knowledge, gear acquired, and major logistics locked in.
4. **Have an amazing week** using day-by-day activity menus to make spontaneous but informed decisions on the ground.
5. **Go home proud** knowing we didn't just scratch the surface — we went deeper than most and earned every view.

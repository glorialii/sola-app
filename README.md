# sola ☀️

sola is a room planning app that I accidentally came up with at around 3am while trying to plan my university dorm room for me and my sister.

We were trying to figure out where to put our beds and furniture so we'd both have some privacy, still get good natural light, and not completely destroy the walking space. I realized pretty quickly that figuring out whether everything *technically fits* is not the same as figuring out whether the room will actually be comfortable to live in.

So now I'm building this!!! :)

## the idea

sola is basically a 2D room planner that uses real measurements and pays attention to all the practical stuff I kept having to figure out manually.

Things like:

- does the furniture actually fit?
- can you still walk between everything?
- is anything blocking a door?
- is there enough room to open a drawer or pull out a chair?
- which side of the room gets the best natural light?
- what will the sunlight look like at different times of the day, month, year?

The plan is to let **you** recreate your room using its actual dimensions, add furniture with real measurements, and move everything around while sola checks the layout as you go!!

## what I want to build!!

- 2D room editor with real dimensions
- rectangular + irregular/L or U-shaped rooms
- multiple rooms and floors
- searchable furniture catalog with real measurements
- custom furniture for things you already own
- drag, rotate and snap furniture
- live clearance/walkway checks
- doors with actual swing space
- windows placed directly on walls
- sunlight analysis based on location + room orientation
- simple 3D preview
- saved projects
- printable/shareable floor plans

## clearance checking

This is probably the part I'm most interested in building!!

A lot of the time furniture can *fit* in a room without the layout actually making sense.

A desk might fit beside a bed, but now you can't pull the chair out. A dresser might fit against a wall, but the drawers don't have enough room to open. Two beds might fit in a dorm, but now one person has to squeeze sideways through a tiny gap every morning 😭

I want sola to catch things like that while you're moving furniture around instead of making you realize it after you've already rearranged the entire room!!

It'll warn you about things like blocked walkways, door swings, furniture overlap, bed access, chair pull-out space and other clearance issues, but it won't stop you from placing something there.

Sometimes you know your room better than the app does!!

## sunlight ☀️

This was the other thing that sent me down the rabbit hole!!

When we were arranging our room, I didn't just care about where the window was. I wanted to know who would actually get the better light and where the sun would hit throughout the day.

So eventually sola will use the room's location, compass orientation and window placement to estimate when direct sunlight enters the room and how that changes throughout the year!!

I'd also like to visualize roughly how far the sunlight reaches into the room instead of just saying that a window is "south-facing" or "west-facing."

## tech

Right now I'm planning on using:

- React + Vite
- Zustand
- SVG for the 2D editor
- Three.js / React Three Fiber for the 3D preview
- Supabase
- PostgreSQL

Measurements will be stored internally in inches and converted for display when needed!

## roadmap

Very much a work in progress!!!

1. room geometry
2. furniture catalog
3. furniture placement
4. clearance engine
5. doors + windows
6. solar analysis
7. 3D preview
8. accounts, saving + sharing

Right now I'm starting with the actual room planner before I let myself disappear into the 3D rabbit hole 😭

## why "sola"?

Mostly because I wanted something short and simple that connected back to the natural-light side of the project!

And it sounded cute!!!

---

built because apparently rearranging a dorm room at 3am wasn't enough of a project ☀️

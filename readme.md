# Sidebar Resize+

The default resize handle on Zen's sidebar is either invisible until you get lucky and find it, or way too fat to grab precisely. This fixes that.

It's a thin, subtle line right on the edge of the sidebar. Hover over it and it lights up a bit so you know exactly where to click. Drag it to resize like normal, just easier to actually hit.

It also stops the sidebar from getting dragged down to basically nothing, or stretched way too wide by accident, since both have min/max limits baked in.

## What it does

- Makes the resize edge thin instead of a thick clunky bar
- Highlights on hover so it's obvious where to grab
- Keeps the sidebar within sane min/max widths
- Optional small grip dots on the handle if you want a visual cue even when not hovering

## Settings

All of these are adjustable in the mod's settings panel, no need to touch the CSS:

- Minimum width
- Maximum width
- Handle thickness
- Grip dots on/off
- Handle color (a few presets)

## Heads up

This only works when the sidebar is showing normally. If you're using Zen's compact mode (the auto-hide sidebar), the resize handle is disabled by Zen itself in that mode, this mod can't bring it back since Zen mods are CSS only, no scripting allowed. That's on Zen's end, not something I can patch around.

If a future Zen update breaks this, it's probably because they renamed the internal element (`#zen-sidebar-splitter`). Pop open the Browser Toolbox, find the real name, swap it in.

Made because I wanted this to exist and it didn't. Enjoy.

*max width doesnt work i will fix it 

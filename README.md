# iRODS Member Logos Layout

This is pretty straight-forward, but I have a few notes.

## The HTML

The `<div class="members">` renders the logos, which live in the `logos` directory. They're all `.svg` files which will scale nicely with the flexible layout when the corresponding `<img>` tags get the `member-logo` class.

Some of the images have a rather wide orientation, *e.g.*, Maastricht University logo, so you can specify that they don't get as small as the others by giving them a `member-logo-wide` class.

## The CSS

Dump those style definitions (the three class definitions: `members`, `member-logo`, and `member-logo-wide`) into your global style sheet or make a separate style sheet and reference it in the home page's HTML.
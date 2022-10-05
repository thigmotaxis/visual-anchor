# visual-anchor

A simple chrome browser extension designed to help people with hemispatial neglect scan to the left side of websites

Q: What is hemispatial neglect?

Hemispatial neglect is an acquired neurological condition resulting in decreased (or absent)
awareness of sensory input on one side of the body (usually the left). As you might imagine,
this causes all sorts of problems for the survivor of neurological injury. If a person's
perception of their surroundings is impaired, they are likely to collide with obstacles
while walking or propelling their wheelchair; driving safely becomes impossible; even
dressing oneself and tracking conversations become difficult and exhausting.

Read more about hemispatial neglect here: https://en.wikipedia.org/wiki/Hemispatial_neglect

Q: How does this extension help?

Treating hemispatial neglect involves gradually retraining the patient to visually scan to
the affected side. The patient is given a target (known as a visual anchor) and trained to
keep scanning until they perceive it. This extension creates a visual anchor within the
browser window that can be used by patients or clinicians to facilitate this training.

Project Notes:

This is the first browser extension I have created, so initially it will only render an anchor
on the left side of the screen. In the near future, I will add options to allow the user to toggle
the color and width of the anchor and to display it on the right rather than the left. I am
choosing to implement left over right initially because left neglect is vastly more common than
right neglect.

Bug Report:

Currently, the extension creates the anchor by utilizing the body:before pseudo-element and
position: fixed. This works on almost all websites I have tested with the sole exception of the
youtube homepage (individual youtube videos display the bar just fine).

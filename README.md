# fredi_68's Custom BD UI Tweaks (bd-custom-ui-tweaks)

This is a collection of minor visual changes I created after finally switching to BetterDiscord after the 2021 rebrand. It is intended to be used together with the
[Revert Rebrand theme by GooseNest](https://github.com/Goose-Nest/GT-RevertRebrand).

## List of Changes

- Removed visual distractions from reactions. Reactions now have the same background color as the rest of the message unless you hover over them, even if it is your reaction. Note that the only way to tell whether or not you have reacted on a message is the color of the number, however, I did not find this to be problematic so far.

- Removed the quick-access button panel that shows up when hovering over a message. I never use it so it was unnecessarily distracting visual clutter that had to go.

- Changed the default mentioned-in-message visuals to be less intrusive. I also got rid of the dirty, puke-yellow background color. By default, a message you were mentioned in (or which contains a reply to a message you posted) will have the same background color as other messages. On hover, this will change to a subtle blue tint. I also changed the `::before` notification bar on the left to be the same color and added a 2px border around the whole message. Paddings and margins have been adjusted accordingly. Once again, despite the significantly less attention-seeking design I had no trouble finding messages I was mentioned in so far.

- Bring back the old font. Because there really was no need for a new one other than discord being able to say "look we got our very own font now".

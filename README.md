# hub-plugin-whip

> Original author: [@ManyLattice](https://github.com/ManyLattice) · upstream: [ManyLattice/hub-plugin-whip](https://github.com/ManyLattice/hub-plugin-whip). This is the copy the Hub catalog installs; the author's updates are taken into it from upstream.
>
> License: MIT (ManyLattice)

A page plugin for [Agents Hub](https://github.com/flagman/agents-hub-core) on the model of
["Hammer"](https://github.com/flagman/hub-plugin-hammer): a "Whip" button in the top strip. A handle at the cursor, a
flexible lash follows the hand; a click is a crack: the lash shoots out, a welt stays on the "screen", sparks and a
sound. Esc or "Clear marks" puts everything back.

![Whip](icon.png)

It is a layer over the page: the hub under it keeps working while the whip is in hand, clicks do not reach it. With
"Reduce motion" there is no lash physics, only the mark and the sound. Everything is drawn by code: no files, no
network, the hub's data is not read.

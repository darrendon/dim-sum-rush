# Dim Sum Rush — playtest build

A partnership shedding / climbing tile game by Darren Don (What's Good Board Games).

The whole game is one file, `index.html`: play against bots, run the tutorial, or host an online table and have friends join with a 5-letter code. Online tables relay through public MQTT brokers, so nothing else needs hosting.

Published with GitHub Pages.

Current rules: fixed-order hands; trolley tiles are never played; when you pass you may put the tile from either end of your hand on a trolley spot and slide the tile that was there into your hand wherever you like. Combinations are singles, sets of 2–3 and runs of 2–3; four of a number or a run of four is a Chef's Special.

## Free-hand test build

`free/index.html` is the same game with free hands: racks stay sorted and you may play any of your tiles together. Only four of a kind is a Chef's Special (a run of four is an ordinary play), and the number ranges are retuned per player count so Specials still land in roughly a quarter to a third of tricks. It keeps the earlier trolley rules (trolley tiles can be added to plays, empty spots can be filled). Free-hand tables use their own online rooms, so codes from the two builds don't mix.

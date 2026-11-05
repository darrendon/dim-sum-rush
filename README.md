# Dim Sum Rush — playtest build

A partnership shedding / climbing card game by Darren Don (What's Good Board Games).

The whole game is one file, `index.html`: play against bots, run the tutorial, or host an online table and have friends join with a 5-letter code. Online tables relay through public MQTT brokers, so nothing else needs hosting.

Published with GitHub Pages.

## Free-hand test build

`free/index.html` is the same game with free hands: racks stay sorted and you may play any of your tiles together. Only four of a kind is a Chef's Special (a run of four is an ordinary play), and the number ranges are retuned per player count so Specials still land in roughly a quarter to a third of tricks. Free-hand tables use their own online rooms, so codes from the two builds don't mix.

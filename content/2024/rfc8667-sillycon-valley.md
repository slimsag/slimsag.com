---
author: "Stephen Gutekanst"
title: "RFC8667: Sillycon Valley"
date: "2024-07-21"
categories:
- tech
draft: false
images: []
description: "RFC8667: Sillycon Valley THE GAME.. a dumb social tabletop game for 1x developers.."
---

Proposed variant of / inspired fanatically by [another popular tabletop game](https://www.secrethitler.com).

## GAME START

* All players are given a random role:
  * One player per game: `VC`
  * ~40% of players: `CEO`
    * 25% chance one `CEO` may be `CRYPTO CEO`
    * 15% chance one `CEO` may be `LAB CEO`
    * 5% chance one `CEO` may be `JUICE CEO`
    * 5% chance one `CEO` may be `UNICORN CEO`
  * ~60% of players: `DEV`
* All players are assumed to be good open source `DEV`s
* Nobody can see each other’s roles, except `CEO`s can see who is `VC`

## DECK FUNCTION

* 40% probability of drawing `GROWTH`
* 60% probability of drawing `FOSS`

## TURNS

* In rotating order, each player will be 'the `1xDEV`' and gets to submit a `10xDEV` to Hacky News
* All `DEV`s must upvote/downvote the Hacky News submission and decide whether they want to depend on the `10xDEV`s work.
* If the submission doesn’t reach the front page (no majority vote), there is no `10xDEV` so `goto next_turn;`
* If the submission would reach the front page, but the `10xDEV` is secretly `VC`, the `VC` shouts `IPO!` and wins
* If the submission reaches the front page, a `10xDEV` has been nominated:
  * If the `10xDEV` is secretly..
    * `VC` or `UNICORN CEO`, they can shout `IPO!` and the `VC` and `CEO` win
    * `CRYPTO CEO`, they can invoke `CRYPTO!`, flip a coin, if heads they steal all `VC` funds and win game for themselves. Tails they go to jail (out of the game entirely.)
    * `LAB CEO`, they can invoke `FAKE IT TILL YOU MAKE IT!`, flip a coin, if heads they steal all `VC` funds and win game for themselves. Tails they go to jail (out of the game entirely.)
    * `JUICE CEO`, they can invoke `SQUEEZED TO DEATH`, two coin flips, if both heads they can shout `IPO!` and `VC` and `CEO` win, otherwise CEO out of the game entirely.
  * If the `10xDEV` is actually just a normal open source `DEV`:
    * The `10xDEV` draws 3 random cards, reviews and discards 1, giving the remaining 2 to the `1xDEV`
    * The `1xDEV` is given 2 cards by the `10xDEV`, must discard 1, must play/put-down the other

## PLAYING CARDS 

* If five `GROWTH` cards are played, the `VC` shouts `IPO!` and wins
* If five `FOSS` cards are played, the `DEV`s win
* When the 3rd and 4th `GROWTH` cards are played, the current `10xDEV` chooses one player to suffer `BURNOUT` - that player can no longer do anything but talk.

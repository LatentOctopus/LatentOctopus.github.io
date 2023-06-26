---
layout: page
title: Glossary
permalink: /glossary/
---
{%- include init.html -%}

### Abbreviations

*  **G**n (e.g. G2):  the n-th growth options, starting from 1 going left to right. For Green, the "Always" growth is called G0.
* n**E** (e.g. 2E): n energy/turn.
* n**CP** (e.g. 3CP): n card plays.
* **x/y** (e.g. 2/4): x energy/turn and y card plays.
* **CE**: Cumulative Energy. See [Stats](#Stats) below for its meaning.

### Terminology

* **Reclaim cycle**: the turns between a Reclaim (included) and the following Reclaim (excluded). For example, an opening that goes `G2, G3, Reclaim, G2, Reclaim, G3, Reclaim, G3, Reclaim` has a reclaim cycle of 2 turns: turn 3+4 is the first reclaim cycle, 4+5 the second, 6+7 the third.
  * _Why is this important?_ Because you want to:
      1. Have enough Energy to be able to play to your maximum card plays in every reclaim cycle.
      2. If you're unlocking more card plays, gain enough cards to fuel the next cycle.
* **Reclaim loop**: A reclaim cycle of 1 turn (that is, reclaiming every turn).

### Opening names

Referring to presence placement:

* **Full top/bottom track**: the opening focuses on emptying one of the tracks, taking one or no presence from the other one.
* **Top/bottom track**: the opening mostly takes presence from one track, and only occasionally from the other one.
* **Hybrid**: presence is taken from both tracks more or less equally. Sometimes this can be written as **Top/bottom track hybrid** to signal the early-game focus, which is useful e.g. to know what other opening one can pivot to if the game takes an unexpected turn.
              
    
Referring to Power cards gains: **Minor** (no Major, or only gain Majors late in the game), **Major** (find good Majors ASAP), **Mixed**.
              
### Stats

I'll often report stats in an opening in a table like this:

Turn | Growth | Owned cards | Cards in hand | CE | Ele+CP
:--: | :--: | :--: | :--: | :--: | :--:
1 | 2 |   5   | 5 | 2 | {{p}}1
2 | 3 |   5   | 3 | 6 | {{p}}{{n}}2

The columns of these table are:

* **Turn**: the turn the row refers to.
* **Growth(s)**: the growth option that is typically selected.
* **Owned cards**: the total number of cards owned by the player, including the discard, _after_ all cards gained during growth. A number in **bold** denotes a Major gain.
* **Cards in hand**: the number cards available to play, _after_ gaining and reclaiming. Note that, unless otherwise specified in the opening, this assumes that all card plays are used on the previous turn.
* **CE (Cumulative energy)**: the total amount of energy gained so far in the game _via growth_, i.e. escluding gains from other sources like Powers, unless otherwise specified. Note that this _includes_ costs for Growth options (e.g. Fangs' G1), but not for other Spirit phase effects (e.g. MM's "Pay 2 to gain a Power).
    * _Why do you not report the energy available on that turn?_ Because that depends on gained cards cost and order of play, thus being too variable to reliably report.
* **Ele+CP (Elements and Card Plays)**: the elements that are unlocked *during the Spirit phase* (e.g. on Presence tracks or via Growth, but not via played Powers), followed by the Card Plays available that turn. These two things combined give a rough idea of which Innate thresholds can be unlocked on a given turn.

Other Spirit-specific columns may be added, but the above-mentioned ones will be present most of the time.

### Confidence

Not all the guides I'll write have been equally tested. I will use the following icons to indicate how confident I am in the guide:

- {{confidence.low}} The guide is very tentative. I have used the strategy only a few times at most -- it might even be pure theorycrafting! It will likely see some changes in the future, as I test more.
- {{confidence.medium}} I am somewhat confident in the guide. I have played it a few times, and have had success with it, but I need to improve it in some aspects and/or gather more data.
- {{confidence.high}} I have tested the guide multiple times, and I think it's in a good spot. This doesn't mean that it's the best strategy in existence nor that it will not change in the future, but it achieves what it aims for.

### Credits

Many other people post guides online, and there may be overlaps with mine. In this case I'll credit the other guide in one of two ways:

- **Adapted from X** means that I've read X and tried it before writing my notes. X was instrumental for my guide, which may even be largely the same as X, or a simplified version!
- **Same as X** / **Similar to X** means that my guide was developed independently from X. It just happened that someone else uses a similar or identical strategy and posted it online. Even it X was online before I uploaded the guide, I did not use X to come up with mine -- I probably hadn't even read it at the time!

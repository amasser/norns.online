# norns.online

![111](https://user-images.githubusercontent.com/6550035/99736745-c470c180-2a7b-11eb-80d4-e9b2a02167cf.png)

online [norns](https://monome.org/docs/norns/) on [norns.online](https://norns.online).

access your norns, or someone else's from the browser. 

**how does it work?** norns runs a service that sends screenshots to `norns.online/<yourname>`. the website at `norns.online/<yourname>` sends inputs back to norns. norns listens to to inputs and runs the acceptable ones (adjustable with parameters). what was [just an idea](https://llllllll.co/t/norns-online-crowdsource-your-norns/38492) is not a norns script.

**note of caution:** when using this keep in mind that anyone with the url `norns.online/<yourname>` can access your norns. even though the inputs are sanitized on the norns so that only `enc()` and `key()` and `_menu.setmode()` functions are available, even with these functions someone could reset your norns / make some havoc. if this concerns you, don't share `<yourname>` with anyone or avoid using this script.

future directions:

- fix all the 🐛🐛🐛
- radio stream somehow? (anyone know how?)

### Requirements

- norns 
- internet connection

### Documentation 

- K3 toggles internet
- K2 changes name
- K1+K2 updates
- more params in global menu

possible uses:

- twitch plays norns (params -> twitch to enable livestream)
- control multiple norns simultaneously
- make demos
- tech support other people's norns
- !?!?!?

## my other norns

- [barcode](https://github.com/schollz/barcode): replays a buffer six times, at different levels & pans & rates & positions, modulated by lfos on every parameter.
- [blndr](https://github.com/schollz/blndr): a quantized delay with time morphing
- [clcks](https://github.com/schollz/clcks): a tempo-locked repeater
- [oooooo](https://github.com/schollz/oooooo): digital tape loops
- [piwip](https://github.com/schollz/piwip): play instruments while instruments play.
- [glitchlets](https://github.com/schollz/glitchlets): 
add glitching to everything.
- [abacus](https://github.com/schollz/abacus): 
sampler sequencer.

## license

mit
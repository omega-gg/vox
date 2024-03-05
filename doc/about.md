# Welcome to vox

Your web browser probably packs a decent video player but that's not sufficient for the level of
innovation we're pushing with the [vox](https://vox.omega.gg/about/instance) patform. Things like:
- A dedicated language called [VBML](https://omega.gg/VBML)
- Extensive codecs support
- Distributed communication protocols

For all this, you need a dedicated [Semantic Player](https://omega.gg/about/SemanticPlayer) that
fits your requirements. At the moment you have the choice between MotionMonkey and MotionBox,
although implementing a new player is quite straightforward with the Sky application kit (LGPL
licensed).

## MotionMonkey

MotionMonkey is the simplest semantic player, with a focus on video playback. It supports a wide
variety of platforms including Windows, macOS, Linux, iOS and Android. Pick this one if you want a
straightforward experience that even a monkey could figure out (no offense to monkeys).

https://omega.gg/MotionMonkey

MotionMonkey is closed source and based on Sky kit under the LGPL license.

## MotionBox

MotionMonkey is a comprehensive semantic player designed for desktop, with a focus on track
browsing and editing functionalities. It supports several platforms including Windows, macOS and
Linux. Pick this one if you're a desktop power user that's not intimidated by a more comprehensive
interface.

https://omega.gg/MotionBox

MotionBox is licensed under the GPL and based on Sky kit under the LPGL license.

## I'm a geek, tell me more about it

The vox platform depends on the VBML language that requires an external video player for playback.
There's both a technical reason and an ethical reasoning behind that choice.

Technically, the web standards are limited in terms of codec support, communication protocols and
scripting languages. When providing a video service you are bound to follow these standards
closely. Secondly, when you want a decent level of compatibility you have to take the lowest
denominator into account in terms of browser implementation (so you don't leave anyone behind). You
can cope with this by generating and caching different video formats to handle different
compatiblity scenarios but that's complicated both in technical terms and hosting costs. Bottom
line is: at its best, the web browser is a capable player but a dedicated video player is
substantially better.

Learn more about the semantic player: https://omega.gg/about/SemanticPlayer

Ethically, we have a client based approach that's different from the traditional web parti pris.
When you're dealing with a web server you accept the asymmetrical relationship between you and the
server. The webmaster does the computation privately and you receive the end results for your local
client to render. When using a semantic player the relationship with the server is different: the
intelligence required to retrieve, decode and interact with the data is entirely on your side: the
client side. The server is essentially a remote entity that stores raw data and blueprints for you
to run and decode locally. This approach ensures that the intelligence is distributed and retained
at the extremities of the network.

Also, we are aligned with the Motion Freedom ethical principles: https://omega.gg/about/MotionFreedom

## Related projects

- [MotionBox](https://omega.gg/MotionBox/sources) - Video Browser
- [MotionMonkey](https://omega.gg/MotionMonkey) - Semantic Player
- [tevolution](https://omega.gg/tevolution) - Remote Video Screen

## Authors

- Benjamin Arnaud aka [bunjee](https://bunjee.me) | <bunjee@omega.gg>

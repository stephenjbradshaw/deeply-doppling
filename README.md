# Deeply Doppling

This Max patch was developed in collaboration with sound artist and composer [Shaun Davies](https://www.shaundavies.info/about) for his piece [_Deeply Doppling_](https://www.shaundavies.info/deeply-doppling). He describes it as a piece of "deep listening theatre" and it was performed at the Kalv Composition Academy in Sweden, Autumn 2019. A demonstration of the patch's features in action can be viewed [here](https://youtu.be/S9B7SCF8LSg).

The brief was for an easy-to-use synthesizer app that several non-technical performers could download and run on their laptops. These laptops send the audio to bluetooth speakers which are manipulated by other performers. Using a patching environment like Max enabled me to quickly iterate, meaning that Shaun could experiment with different kinds of sound generation during the composition process. Packaging the patch as a standalone app meant quicker technical setup for each performer, saving valuable rehearsal time.

Very fine, continuous pitch control of the oscillators was required. To achieve this, I implemented a 'rubber-band-style' slider UI element to provide intuitive control over pitch. Dragging the slider slightly to the right will raise the pitch very slowly, but dragging it further will raise it more quickly. The pitch can be lowered in the same way by dragging the slider to the left. Releasing the mouse button allows the slider to 'spring back' to center, stopping the pitch from changing any further. Watch the [demo](https://youtu.be/S9B7SCF8LSg) to see this in action.

If you would like a copy of the standalone, or have got any other questions, don't hesitate to [get in touch](mailto:hello@stephenbradshaw.dev).

## Features

- Two oscillators with 'rubber-band' controls for pitch
- FM synth capability
- Pink noise generator
- Built-in timer, to aid in following the composer's score

## Future development

For future performances of the piece, the patch could be rewritten as a web application, removing the need for performers to install software altogether.

## UI screenshot

![UI screenshot](img/ui-screenshot.png)

## Prerequisites

To run or edit: [Max 8](https://cycling74.com/downloads)

## Author

**Stephen Bradshaw** – [Portfolio](https://www.stephenbradshaw.dev) | [Linkedin](https://www.linkedin.com/in/stephenbradshawdev/) | [Github](https://github.com/stephenjbradshaw)

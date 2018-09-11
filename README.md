# GogoApps Task

As a Product Owner I want an app in which I can select a color and, by doing this, change
the background color of the whole app.
List of all colors is here: http://www.mocky.io/v2/5a37a7403200000f10eb6a2d 
Colors should be selectable from an autosuggest field.

Acceptance criteria:
- colors should be fetched from remote source,
- new background color must be 50% transparent,
- autosuggest should work from 2 chars,
- selected color should be accepted by clicking an “Accept” button placed next to the
autosuggest field.

Tech requirements:
- general stack is: React, redux, ES6 (if not familiar with React then use vanilla or your
favorite JS framework/libraries),
- autosuggest mechanism should be written from scratch, no ready-to-use solutions,
- code should be tested (write all suitable and needed tests),
- solution must be delivered either as a GitHub repository or as a compressed
package,
- the app must be a npm project (installable and runnable by npm or yarn scripts),
- UI is not important,
- browser support: newest versions (skip the IE/Edge).
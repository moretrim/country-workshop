<p align="center"> <!-- Dear GitHub -->
<figure>
<a href="https://github.com/moretrim/country-workshop">
<img src="media/title.jpg" alt="Architect at his drawing board. He is pensive, looking not at floor plans
but at a Victoria 2 map of Europe.">
</a>
<figcaption>
<center>
<h1>The Country Workshop</h1>
</figcaption>
</figure>
</p>

Build status:
[![Github Workflow][github-workflow-badge]][github-workflow-dashboard]

[github-workflow-badge]:
    https://github.com/moretrim/country-workshop/actions/workflows/ci-on-push.yaml/badge.svg
[github-workflow-dashboard]:
    https://github.com/moretrim/country-workshop/actions/workflows/ci-on-push.yaml
    "Github Workflows"

The Country Workshop
--------------------

A collection of odd alternative starts and countries designed on a whim. Sometimes collaboratively,
often haphazardly. The main appeal is usually the added challenge these new starts & countries
provide, or putting a fresh twist on an existing part of the world.

Please note that the included countries or their features are not always based on anything
historical or historically plausible. It’s fair to consider most of them fantasy countries. See the
[Features](#features) & [Feature List](#feature-list) for a detailed account.

This is a submod for [ccHFM][] and should not be played standalone.

[ccHFM]: https://github.com/moretrim/ccHFM#readme

Installation
------------

This is a submod, so you should install [the parent mod][] first. After that grab the [1.0.0
release][].

[the parent mod]: https://github.com/moretrim/ccHFM/releases/
[1.0.0 release]: https://github.com/moretrim/country-workshop/releases/tag/v1.0.0

Extract the `country-workshop` and `country_workshop.mod` file from the provided archive, and place
them in your favourite `mod` folder. Both the folder and file must end up side-by-side.

When launching the game, make sure to enable *both* the parent mod and this submod. This includes
when loading a previous save.

Features
--------

Category | Description
--------:|:-----------
Alternative start | Involves a pre-existing country of HFM. Makes that country playable from 1 January 1836, whereas it would normally have been very unusual or even impossible to do so.
Minimal country | Cultures & starting cores. **No** historical data, **no** specific content.
Fantasy country | **No** historical data, some non-historical content.

Feature List
------------

Any feature that is not yet complete will be marked as a <dfn>**Work In Progress**</dfn>
(***WIP***).

Start           | Category  | Features <small>(culture union listed with the primary culture)</small>
---------------:|:---------:|:-----------------------------------------------------------------------
[Disunited States][FSA-preview] | Alternative start | <h5>The United States broken up by the Disunited States event.</h5>13 possible starting American countries, all of which can restore the Union.<br>Fast forwards through the early historical happenings up to the Gadsden Purchase borders along with the Alaska Purchase.<br>Fast forwards some immigration of European soldiers to prop up the less populated Western and Midwestern breakaway countries.<br>Skips the Civil War.<br>Hawaii starts Westernised.<br>Releases Liberia early.<br>Sets up a couple diplomatic blocs with a very brief truce period.<br>Prevents these AI American countries from peacefully uniting with their American neighbours or the reborn Union.<br>The Treaty of Guadalupe Hidalgo is not signed, and the northern Mexican cores are suspended rather than outright removed. They can return by decision with Revolution & Counterrevolution.<br>Allows tech-gated, limited uses of American Restoration CBs with unlimited uses after Mass Politics.
Gotland | Fantasy country | <h5>The leader of a new Hanseatic League.</h5>Cultures: Swedish (Scandinavia), Estonian<br>Start: Gotland
Kosakenstadt | Alternative start | <h5>The lone core that is normally added by the *Russify the Baltic States* decision.</h5>Cultures: Eastern German (*none*)<br>Start: Saratov

[FSA-preview]: media/disunited-states.jpg?raw=true

Detailed usage
--------------

- Start a new campaign as the country you intend to play, or as any country if you intend to use one
  of the submod features.
- Do **not** unpause. While you are allowed to enable any feature during the first month of the
  game, we really only advise you do so on 1 January 1836.
- Activate the “Country Workshop: show all decisions” decision. This will display all submod
  features in the form of individual decisions.
- You can at any time take the opposite decision to hide all features before they vanish on their
  own after the first month. This is not permanent, and you can re-activate the display decision at
  any time during that first month.
- You can now activate any feature decision to enable that feature. (This cannot be reversed.
  You have to restart if you activated the wrong decision.)
- Some features may present you with a follow-up event. This gives you finer control over the
  feature. Typically for country features this offers you the following choices:
  * limit them to just cores on the map
  * release them as a vassal country (this releases from the current owner of the capital province)
  * release them as an independent country
  * play them as an independent country
- There are also umbrella decisions to enable every feature at once. One grants you fine control
  over each feature, which can result in many event notifications at once. Others apply a given
  level of control to each country (e.g. releasing each as a vassal), sparing you the follow-ups.
- You may only pick one “Play as…” follow-up option when using an umbrella decision. Subsequent
  picks will have the same effect as the “Independent country…” option.
- You can enable any number of features individually before activating one of the umbrella
  decisions, to enable all others.
- When activated, some features may recommend that you save & reload the campaign at this stage. You
  should do so after dismissing all outstanding events, but before unpausing. Failure to do so may
  lead to unpredictable game behaviour.
- Once you have enabled everything you wanted and optionally reloaded, you may unpause and play. All
  decisions will disappear by the end of the first month. Have fun!

Note that during a playthrough the submod must be loaded on every subsequent launch of the game. The
submod is not just needed for the initial decisions, but is also necessary for the new countries it
adds. Loading a save while missing a mod present during the making of that save has unpredictable
results.

Attributions
------------

[Attribution information for the title & in-game images that this submod uses is
available.](./attributions.markdown)

Other resources
---------------

|  |  |
|-:|:-|
**[Troubleshooting Guide][]** | Having issues running Victoria II? Try our guide!
**[ccHFM][]** | The parent mod to this submod
**[Shatter][]** | Shatter your Victoria II world at any time, with any mod

[Troubleshooting Guide]: https://github.com/moretrim/victoria2-troubleshooting#readme
[ccHFM]: https://github.com/moretrim/ccHFM#readme
[Shatter]: https://github.com/moretrim/shatter#readme

Release History
---------------

### 1.0

#### 1.0.0

The original release, it targets [ccHFM 1.1.0][].

[ccHFM 1.1.0]: https://github.com/moretrim/ccHFM/releases/tag/v1.1.0

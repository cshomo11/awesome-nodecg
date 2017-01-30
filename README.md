# Awesome NodeCG [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/nodecg/awesome-nodecg.svg?branch=master)](https://travis-ci.org/nodecg/awesome-nodecg)

> A curated list of [NodeCG](http://nodecg.com) v0.8 bundles and resources.

*Looking for bundles for an older version of NodeCG?
Check the [`old-versions`](https://github.com/nodecg/awesome-nodecg/blob/master/old-versions) folder.*  
*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list project.*  
*Please read the [contribution guidelines](contributing.md) before contributing.*

## Intro to [NodeCG](http://nodecg.com)
NodeCG is a broadcast graphics framework and application. It provides an API and structure for making dynamic graphical assets for broadcast use. NodeCG graphics packages are called "bundles". NodeCG is primarily aimed at [Twitch](http://www.twitch.tv) broadcasters using [Open Broadcaster Software](https://obsproject.com), but is usable in any environment that can render HTML, including [CasparCG](http://casparcg.com).

Still not clear on what NodeCG is and what it is used for? These videos go over some of the more prominent uses of NodeCG:
- [Tip of the Hats 2015 Graphics Overview](https://www.youtube.com/watch?v=Z4-qaya5-0Y)
- [Tip of the Hats 2016 Graphics Overview](https://www.youtube.com/watch?v=F0xGN-aSytA)
- [Awesome Games Done Quick 2016 Graphics Overview](https://www.youtube.com/watch?v=oAzj9Zddogs)

Want to suggest a bundle for inclusion? Open a PR!


## Table of Contents
- [Complete Systems](#complete-systems)
- [Alerts](#alerts)
- [Service Integrations](#service-integrations)
  - [Twitch](#twitch)
  - [Beam](#beam)
- [Utilities](#utilities)
- [Dashboard Polymer Elements](#dashboard-polymer-elements)

## Complete Systems
NodeCG bundles (or suites of bundles) that provide an entire production system by themselves. They're generally targeted at a specific game or type of show, though some may be more generalized.

- [sgdq16-layouts](https://github.com/GamesDoneQuick/sgdq16-layouts) - The on-stream graphics used during Summer Games Done Quick 2016.
- [toth4-overlay](https://github.com/TipoftheHats/toth4-overlay) - The main broadcast assets for Tip of the Hats 2016.
- [b2aExtraLife](https://github.com/cshomo11/b2aExtraLife) - A stream bundle created for Extra Life 2016. It will track donation totals, show a list of donors, and display games played and other messages.

## Alerts
Bundles which provide alerts on an overlay.

- [prime-alerts](https://github.com/ProbablePrime/prime-alerts) - Basic follow, sub and tip alerts that listen to nodecg-beam messages.

## Widgets
Bundles which provide some form of visual information on an overlay.

- [nodecg-recentfollower](https://github.com/Allar/nodecg-recentfollower) - Displays the most recent follower from Beam or Twitch using [node-beam-service](https://github.com/Allar/nodecg-beam-service) and [node-twitch-service](https://github.com/Allar/nodecg-twitch-service).

## Service Integrations

### Twitch
- [lfg-twichapi](https://github.com/SupportClass/lfg-twitchapi) - Lets other bundles easily query the Twitch API on behalf of a logged in user.
- [nodecg-twitch-service](https://github.com/Allar/nodecg-twitch-service) - Tracks Twitch events and emits them as events for other bundles.

### Beam
- [nodecg-beam](https://github.com/ProbablePrime/nodecg-beam) - Tracks Beam Follows, Subscriptions and Hosts and emits them as events for other bundles.
- [nodecg-beam-service](https://github.com/Allar/nodecg-beam-service) - Tracks Beam events using [constellation-client](https://github.com/StreamJar/Constellation) and provides Beam info via Replicants.

## Utilities
- [prime-manual-alerts](https://github.com/ProbablePrime/prime-manual-alerts) - Manual emits follow, subscription, host and tip events which prime-alerts can listen to.

## Dashboard Polymer Elements
These are [Polymer](https://www.polymer-project.org/1.0/) elements meant to be used as part of a dashboard panel.
Think of them as building blocks that can be used to speed up development time of a panel.
- [nodecg-toggle](https://github.com/NodeCGElements/nodecg-toggle) - Toggles the boolean state of a Replicant.
- [nodecg-toast](https://github.com/NodeCGElements/nodecg-toast) - An implementation of paper-toast designed to work well in NodeCG dashboard panels.
- [nodecg-replicant-input](https://github.com/NodeCGElements/nodecg-replicant-input) - A [`<paper-input>`](https://github.com/PolymerElements/paper-input) element that has two-way binding with a Replicant.
- [nodecg-position-select](https://github.com/NodeCGElements/nodecg-position-select) - A UI element for quickly selecting a position preset, useful when making graphics that the user may need to reposition.
- [nodecg-replicant](https://github.com/NodeCGElements/nodecg-replicant) - A declarative way of using Replicants, best used as part of other Polymer elements.
- [nodecg-message-button](https://github.com/ProbablePrime/nodecg-message-button) - A [`<paper-button>`](https://elements.polymer-project.org/elements/paper-button) which sends a message to a bundle when clicked.
- [nodecg-show-hide](https://github.com/ProbablePrime/nodecg-show-hide) - A dashboard element which provides show & hide [`<nodecg-message-button>`](https://github.com/ProbablePrime/nodecg-message-button) buttons.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the NodeCG team has waived all copyright and related or neighboring rights to this work.

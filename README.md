# JakeBot training dashboard

Live training progress of JakeBot, a Rocket League bot that learns only by playing itself.

The page (`index.html`) reads `data.json`, which the training PC regenerates and pushes every
~5 minutes while it is on. This repo is a single force-pushed snapshot; there is no history.
It shows progress only (steps, speed, Elo, test results against its own older versions,
learning health); how the bot is trained and how it plays are not published.

Dashboard design by NiteRex ([rlbot-dashboard](https://github.com/NiteRex/rlbot-dashboard)),
adapted for JakeBot.

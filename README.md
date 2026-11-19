# flowops-dev-releases

This repository holds one small file, `latest.json`, which says what the newest version of the
FlowOps.dev desktop app is, for example `{"version":"0.8.0"}`.

The installed app reads it (one anonymous request, on launch and when the learner picks
Help > Check for Updates) to find out whether a newer version exists. It contains no installers
and no source code, and the app sends no information about the learner.

The file is written automatically by the release workflow of the main (private) project.

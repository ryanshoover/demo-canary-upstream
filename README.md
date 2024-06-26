# Demo Upstream with Canary Site

This is a demo upstream for Pantheon sites. It relies on canary sites to test any changes before those changes are made available to the broader list of sites.

The master branch is the "production-ready" branch that can be used by any live sites.

The default branch for this repo is the `canary` branch. It's meant to be a branch where any upstream changes get merged into first before they're ready for live sites to use.

The `canary` branch automatically deploys to the dev environment of any sites tagged as `canary` sites.

If you create PRs into other branches, those branches will create multidevs and automatically deploy to a dedicated multidev.

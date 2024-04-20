# Update Site for SpotBugs Eclipse Plugin

This repository serves update site for SpotBugs Eclipse Plugin.
About the usage of SpotBugs Eclipse Plugin, please visit [official manual](http://spotbugs.readthedocs.io/en/latest/eclipse.html).

## URL for Eclipse Update site

Please use following URL when you install SpotBugs Eclipse Plugin:

https://spotbugs.github.io/eclipse/

## How we push changes to this repository

When change in [spotbugs](https://github.com/spotbugs/spotbugs) repository has been tagged with non-RC version,
Github CI builds Eclipse Plugin and [deploys](https://github.com/spotbugs/spotbugs/blob/master/.github/workflows/release.yml) it to the `gh-pages` branch of this repository.

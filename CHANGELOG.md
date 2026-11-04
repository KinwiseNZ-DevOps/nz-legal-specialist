# Changelog

All notable changes to this plugin are listed here, newest first. To cut a release, add your notes under "Unreleased", then run `python scripts/bump_version.py patch` (or `minor` or `major`). It updates the plugin version and moves those notes under the new version.

## [Unreleased]

## [0.3.0] - 2026-11-05

- Added a Works with other repos section to the router skill and README: it names the repos this one depends on or is relied on by, and when to hand off. Marketing comes first in the decision order (marketing, then look and feel, then the technical work). The map is in skills-repos-dependency-map.md beside the repos.

## [0.2.0] - 2026-10-29

- Added the rule to act only when told and to analyse the repo before answering: no guesswork, no redoing finished work, and show the real artifact when asking the user to review or approve. It is in AGENTS.md and as a hard-rule bullet in every skill.

## [0.1.0] - 2026-10-29

- Initial skills: `nz-legal-specialist` (router), `nz-contract-drafting`, `nz-trading-terms`, `nz-privacy-compliance`. Every flagged wording issue requires a specific New Zealand Act and section citation, verified against a live source where web access allows.

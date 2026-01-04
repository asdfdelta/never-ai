## Name

NeverAI.io

## Project Statement

A service that offers an image badge where written content creators (articles and blogs) can put on their pages that verifies if the content is AI or not.

## Impelmentation Details

Users only need to add an image tag to their site.

Image tag will hit an edge service that returns a cache, adds the url to the db, or reads current value from db.

A separate function will run on a CRON schedule to go and scrape the content, hit an AI detector api, and return results in the db.

## Current State

Planning.

## Checkpoints
- [ ] Researched and chosen AI detector API
- [ ] Designed architecture
- [x] Registered domain
- [ ] Commissioned image badges
- [ ] Scaffolded edge service
- [ ] Scaffolded database
- [ ] Test

## Braindump

- 
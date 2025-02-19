---
title: Email Scoring
github: https://github.com/PostHog/mailboxlayer-plugin
installUrl: https://app.posthog.com/project/apps?name=Posthog+Ingestion+Alert+Plugin
thumbnail: ../../cdp/thumbnails/email-scoring.png
tags:
    - email-scoring
---

The Email Scoring app adds email scores to Persons in PostHog, giving you more context on each user. Email scores are added using the [Mailboxlayer API](https://mailboxlayer.com/).

## Requirements

The Email Scoring app requires either PostHog Cloud, or a self-hosted PostHog instance running [version 1.30.0](https://posthog.com/blog/the-posthog-array-1-30-0) or later.

Not running 1.30.0? Find out [how to update your self-hosted PostHog deployment](https://posthog.com/docs/runbook/upgrading-posthog)!

You'll also need Mailboxlayer access and an API key.

## Installation

1. Visit the 'Apps' page in your instance of PostHog.
2. Search for 'Email Scoring' and select the app, press Install.
3. Get an API key from Mailboxlayer.
4. Click '+ Install new app' and use this URL to install: `https://github.com/PostHog/mailboxlayer-plugin`
5. Add the API key to the config.
6. Enable the app and watch the email scores come in!

## Configuration

<AppParameters />

## FAQ

### Is the source code for this app available?

PostHog is open-source and so are all apps on the platform. The [source code for the Email Scoring app](https://github.com/PostHog/mailboxlayer-plugin) is available on GitHub.

### Who created this app?

We'd like to thank PostHog team members [Yakko Majuri](https://github.com/yakkomajuri) and [Marius Andra](https://github.com/mariusandra) for creating the Email Scoring app.

### Who maintains this app?

This app is maintained by PostHog. If you have issues with the app not functioning as intended, please [let us know](http://app.posthog.com/home#supportModal)!

### What if I have feedback on this app?

We love feature requests and feedback! Please [tell us what you think](http://app.posthog.com/home#supportModal)! to tell us what you think.

### What if my question isn't answered above?

We love answering questions. Ask us anything via [our community forum](/questions), or [drop us a message](http://app.posthog.com/home#supportModal). 
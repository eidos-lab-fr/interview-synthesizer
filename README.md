# Interview Synthesizer

Turn user interview notes into themes, verbatim quotes and opportunities with Claude.
**[Try it live](https://eidos-lab-fr.github.io/interview-synthesizer/)**


## Features

- Themes with how many interviews mention each one
- Quotes copied word for word from your notes and attributed to their interview
- Opportunities phrased as customer needs, not features
- Contradictions and open questions called out

## Usage

Open `index.html` in a browser, paste an [Anthropic API key](https://console.anthropic.com/), and run it. There is nothing to install and nothing to build.

## Your key, your cost

This page has no server. It calls the Anthropic API straight from your browser with **your own key**:

- The key is kept in the browser tab, or on the device if you tick "Remember". It is sent only to `api.anthropic.com`.
- Nobody else's key is involved, so hosting this page publicly costs its owner nothing.
- Each run shows the tokens used and an estimated cost. Use a key with a spending limit.

The Anthropic SDK is loaded from `esm.sh` at a pinned version. You can choose between Claude Opus 5.5, Sonnet 5.5 and Haiku 5.5.

Remove names and confidential details before pasting: your notes are sent to the Anthropic API.

## Stack

A single HTML file. Anthropic TypeScript SDK loaded as an ES module.

## License

[MIT](LICENSE) © 2026 Eidos Lab

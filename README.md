# TalentReviewAI docs

The developer documentation for TalentReviewAI, built with [Mintlify](https://mintlify.com). Covers the Agent API: how AI agents discover, read, and act on jobs.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview changes locally:

```
npm i -g mint
```

Run the following at the root of the repo, where `docs.json` lives:

```
mint dev
```

View the local preview at `http://localhost:3000`.

## Publishing changes

Changes deploy to production automatically after merging to the default branch (`main`), via the Mintlify GitHub app.

## Structure

- `index.mdx` — landing page
- `agents/` — Agent API docs (overview, authentication, endpoints, errors)
- `docs.json` — site config and navigation

## Need help?

- If the dev environment isn't running: `mint update` to get the latest CLI.
- If a page loads as a 404: make sure you're in a folder with a valid `docs.json`.
- [Mintlify documentation](https://mintlify.com/docs)

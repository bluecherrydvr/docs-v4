# Bluecherry DVR v4 docs

End-user documentation for the Bluecherry DVR v4 web interface, hosted on
[Mintlify](https://mintlify.com). Pages are MDX files; navigation and site
settings live in `docs.json`.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```
npm i -g mint
```

Preview locally from this directory:

```
mint dev
```

View the preview at `http://localhost:3000`.

## Publishing changes

Pushing to the default branch deploys to production automatically (via the
Mintlify GitHub app).

## Writing

See `AGENTS.md` for voice and style rules. Every UI label, route, and setting
in these pages is grounded in the `modern-web/` sources in
[bluecherry-apps](https://github.com/bluecherrydvr/bluecherry-apps) — verify
against that code before documenting new behavior.

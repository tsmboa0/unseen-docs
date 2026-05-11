# Unseen Pay documentation — AI / agent notes

This site is Mintlify: MDX pages + **`docs/docs.json`**. Preview with `mint dev` from this directory (`docs/`).

## Product terms

- Prefer **Unseen Pay** as the integration name where it describes checkout and payments.
- Packages: **`@unseen_fi/sdk`** (server / Node), **`@unseen_fi/ui`** (React checkout UI).
- API keys look like **`usk_test_`** / **`usk_live_`**; never encourage shipping live secrets to browsers.

## How to extend these docs

- New pages **must** be listed under `navigation.groups` (or tabs) or they stay hidden from the sidebar.
- Internal links use **root paths without** `.mdx` (example: `/sdk/server/installation`).
- Reuse prose via **`snippets/`** and `<Import>` patterns from the [Mintlify reusable snippets guide](https://www.mintlify.com/docs/create/reusable-snippets).

## Maintainer skill

Mintlify publishes skills from **`https://www.mintlify.com/docs`** (use the **`www`** host):

`npx skills add https://www.mintlify.com/docs`

## Brand assets in this repo

Navbar uses **`docs/logo/wordmark-dark.png`** (from `unseen_app/public/unseen-logo-dark.png`) and **`docs/logo/dark.svg`** for dark-mode wordmark. **`docs/favicon.png`** is a resized `unseen-icon.png`. Re-copy from `unseen_app/public/` when marketing ships new files.

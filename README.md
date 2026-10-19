# 3dprinter.cobanov.dev

A one-page, printer-agnostic guide and a prompt that hands setting up and
calibrating a 3D printer to an AI agent. You do the physical steps; the agent
does the research, backups, software, slicer profiles and the calibration loop.
English and Turkish.

https://3dprinter.cobanov.dev

## Layout

- `public/index.html`: the page. Styles and script are inline; English and
  Turkish sit side by side as `lang` attributes and the TR/EN button switches them.
- `public/prompt.txt`: the prompt the page loads, fills with the optional clue
  and copies.
- `public/assets/`: the social card.

## Deploy

Cloudflare Pages project `3dprinter`, direct upload:

```sh
wrangler pages deploy public --project-name 3dprinter --branch main
```

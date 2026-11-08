# agent-memory-deploy

Sales material for a service offer: deploying and supporting the open-source
[Metronix Memory](https://github.com/mtrnix/metronix-memory) (Apache-2.0) on a customer's
own servers. This is an independent implementation-partner offer, not the Metronix project;
the name is used only to identify the software. No Metronix logo is used.

| Path | What it is |
|------|------------|
| `landing/index.html` | One-page site. Static, no frameworks, no external requests. |
| `landing/demo.mp4`, `landing/demo-poster.jpg` | 68-second terminal demo (clean-machine install, cross-client recall, local storage) and its poster frame. `landing/demo.gif` is the same demo as a GIF for sharing; the page no longer embeds it. |
| `landing/qa/` | Full-page screenshots at 1440 px and 390 px, light and dark. |

Live: https://deploy.mtrnix.com/ (GitHub Pages custom domain, HTTPS enforced; deployed from `landing/` by
`.github/workflows/pages.yml`). The old https://cycterna2222288888-ai.github.io/agent-memory-deploy/ URL redirects there.
Preview locally: `open landing/index.html`.

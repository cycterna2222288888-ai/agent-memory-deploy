# agent-memory-deploy

Sales material for a service offer: deploying and supporting the open-source
[Metronix Memory](https://github.com/mtrnix/metronix-memory) (Apache-2.0) on a customer's
own servers. This is an independent implementation-partner offer, not the Metronix project;
the name is used only to identify the software. No Metronix logo is used.

| Path | What it is |
|------|------------|
| `landing/index.html` | One-page site. Static, no frameworks, no external requests. |
| `landing/demo.gif`, `landing/demo.mp4` | 68-second terminal demo of a clean-machine install, cross-client recall and local storage. |

Live: https://cycterna2222288888-ai.github.io/agent-memory-deploy/ (GitHub Pages, deployed from `landing/` by `.github/workflows/pages.yml`).
Planned custom domain: https://deploy.mtrnix.com/ (`landing/CNAME`). It takes effect once DNS points at GitHub Pages and the
custom domain is set in the repository's Pages settings; until then the github.io URL keeps working.
Preview locally: `open landing/index.html`.

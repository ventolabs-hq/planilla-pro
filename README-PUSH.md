# Planilla Pro — GitHub Pages bundle (ready, NOT pushed)
Copied 2026-10-26 from ipc-pack/pages-bundle/public (manual email flow; comprar.html/config.js excluded; no wallet address in files — address is sent only by email reply).
Push (Lead GO required):
  cd products/planilla-pages && git init -b main && git add . && git commit -m "Planilla Pro site"
  gh repo create ventolabs-hq/planilla-pro --public --source=. --push
  gh api -X POST repos/ventolabs-hq/planilla-pro/pages -f 'source[branch]=main' -f 'source[path]=/'
URL: https://ventolabs-hq.github.io/planilla-pro/

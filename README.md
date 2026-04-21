# bolt-website

Marketing site for **Bolt by Studio B** — Continuous Goods WMS.

- **Live:** https://bolt.b.studio
- **Host:** Railway (service `bolt-site` in `studiob-platform`)
- **Register:** Cut Sheet — navy + signal-blue + warehouse-yellow, Inter + JetBrains Mono
- **Voice:** Basecamp/Hey (per `memory/feedback_studio-b-voice.md`)

## Pages
- `/` — `index.html`
- `/pricing` — `pricing.html`
- `/customers/heritage` — `customers/heritage.html`

## Family
Follows the `{product}-website` convention. Siblings: [b-studio-website](https://github.com/studio-b-ai/b-studio-website), [acuops-website](https://github.com/studio-b-ai/acuops-website), [amplify-website](https://github.com/studio-b-ai/amplify-website), [relay-website](https://github.com/studio-b-ai/relay-website).

## Deploy
Static files served by Railway. The `bolt-site` service deploys from `main` on push.

# policies

Privacy policies and support pages for apps by Martin Kiperszmid, served by GitHub Pages at
https://mkiperszmid.github.io/policies/.

One folder per app, each self-contained (its own assets), linked from `index.html`:

| App | Home | Privacy | Support |
|---|---|---|---|
| Tabiya | [/policies/tabiya/](https://mkiperszmid.github.io/policies/tabiya/) | [privacy](https://mkiperszmid.github.io/policies/tabiya/privacy/) | [support](https://mkiperszmid.github.io/policies/tabiya/support/) |

To add an app: create `<app>/` with `index.html`, `privacy/index.html`, `support/index.html`
(and `es/…` for Spanish), add a row to `index.html` and to this table, push. Links inside an app
folder stay relative, so the folder works anywhere.

Every statement in a privacy policy must match what that app's code does. Change the policy (and
its "Last updated" date) in the same release that changes the behaviour.

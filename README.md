# rhythmicode.com

The static website for Rhythmicode, served by GitHub Pages at
<https://rhythmicode.com>. Plain HTML and CSS, no build step: edit a file, push to
`main`, and Pages republishes it within a minute or two.

| Path | Page |
|---|---|
| `/` | home |
| `/3toop/` | the game page |
| `/3toop/privacy/` | 3Toop privacy policy (the URL given to Google Play) |
| `/3toop/terms/` | 3Toop terms of service |

The policy and terms texts come from the 3Toop repo's drafts,
`docs/store/play/privacy-policy.md` and `terms-of-service.md`. Change them there
and here together, and update each page's "Last updated" date. The privacy policy
must be revised before any release that adds network access, accounts, ads or
purchases (3Toop's E4).

`CNAME` holds the custom domain. DNS is at Namecheap: four `A` records on `@` to
GitHub Pages' addresses and a `CNAME` on `www` to `rhythmicode.github.io`.

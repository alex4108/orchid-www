# orchid-www

Public website for [Orchid](https://runorchid.com) — served via GitHub Pages at <https://runorchid.com>.

## What's here

- `index.html` — landing page
- `security/index.html` — security policy (served at `/security`)
- `.well-known/security.txt` — RFC 9116 security contact
- `.well-known/security-pubkey.asc` — PGP pubkey for security reports
- `CNAME` — custom domain binding (`runorchid.com`)
- `.nojekyll` — disable Jekyll so `.well-known/` is served verbatim

## Source of truth

The security policy and PGP key are mirrored from the private Orchid
source repo. When `SECURITY.md` or `.well-known/` changes there, update
this repo too. Setup history and rollout status lives in that repo at
`docs/agent-context/DOMAIN-SETUP.md`.

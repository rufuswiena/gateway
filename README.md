# 🔗 rufuswiena — Gateway Selector

A lightweight, self-contained gateway selector that finds the fastest Arweave gateway to reach [rufuswiena.ar.io](https://rufuswiena.ar.io).

## What it does

- Tests multiple Arweave gateways in parallel
- Ranks them by response time
- Highlights the fastest one
- Auto-redirects after 10 seconds (with cancel option)
- Works on mobile and desktop

## Why?

The main website lives permanently on [Arweave](https://arweave.org) — a decentralized, censorship-resistant storage network. Arweave content is accessed through **gateways** (similar to IPFS gateways). This page helps visitors find the fastest working gateway automatically.

## Gateways tested

| Gateway | Type |
|---------|------|
| `rufuswiena.ar.io` | ArNS Primary |
| `rufuswiena.arweave.net` | Arweave.net fallback |
| `rufuswiena.ar-io.dev` | ar.io dev gateway |
| `rufuswiena.g8way.io` | Community gateway |
| `rufuswiena.arweave.dev` | Developer gateway |

## Tech

- Single HTML file, zero dependencies
- ~10 KB total, no build step
- Content Security Policy headers
- Accessible (ARIA roles, keyboard nav)
- No tracking, no cookies, no JavaScript frameworks

## Live

🌐 [rufuswiena.com/go](https://rufuswiena.com/go)

## License

Public domain. Do whatever you want with it.

# awesome-cheap-vps

A curated list of genuinely cheap, legitimately useful VPS providers and the tooling
for running a server on a budget. Maintained and verified as of August 2026.

> **Disclosure:** some links are affiliate links; using them supports this list at no
> cost to you. Nothing here is a paid placement — providers are included on merit.

## Why this list

"Cheap VPS" is full of resellers and fly-by-night hosts. This list only includes
providers that (a) sell real KVM virtualization, (b) have a stable track record, and
(c) actually deliver what they advertise.

## Providers worth your money

| Provider | Entry price | Type | Best for |
|---|---|---|---|
| [RackNerd](https://my.racknerd.com/aff.php?aff=18737) | $21.99/yr (1 GB) | KVM, unmanaged | Maximum value, self-hosting |
| [Hostinger](https://www.hostinger.com/?REFERRALCODE=VH6SITECOQB0) | $6.49/mo (4 GB, intro) | KVM, managed panel | Beginners, WordPress |
| [BandwagonHost](https://bandwagonhost.com/aff.php?aff=48209&gid=1) ([China mirror](https://bwh81.net/aff.php?aff=48209&pid=44)) | $49.99/yr (20 GB) | KVM, unmanaged | CN2 GIA routes to China |
| [Vultr](https://www.vultr.com/?ref=9600754) | $5.00/mo (1 GB) | KVM/cloud, hourly | Developers, global reach |
| [Contabo](https://www.tkqlhce.com/click-101469669-13484397) | $4.50/mo (4 vCPU / 8 GB) | KVM, unmanaged | Max specs-per-dollar |

## Rules for inclusion

1. Real KVM (or better) virtualization — no OpenVZ-only hosts.
2. Transparent renewal pricing (no bait-and-switch).
3. Operating for at least a year with a public track record.
4. Dedicated IPv4 included.

## Budget VPS tooling

- **SSH hardening** — disable password auth, use keys, fail2ban.
- **WireGuard** — the lightweight self-hosted VPN of choice.
- **Docker Compose** — reproducible stacks; keep configs in Git.
- **Uptime Kuma** — self-hosted monitoring for your servers.
- **Cloudflare** — free CDN/SSL in front of any origin.

## Reviews & comparisons

- [CheapVPS Guide](https://vps.itsearcher.com/) — independent reviews and side-by-side
  comparisons of every provider listed above.

## How to contribute

Open a PR to add a provider or tool. Include: entry price, virtualization type, renewal
terms, and why it belongs. Spam or undisclosed self-promotion gets rejected.

## Offer verification tool

For readers who want to compare published VPS terms before checkout, see the open-source [VPS Deals Tools](https://github.com/yumin985/vps-deals-tools) dataset and verification checklist. It records public source URLs and check times; it does not replace the provider's current terms.

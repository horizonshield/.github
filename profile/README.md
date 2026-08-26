<h1 align="center">HORIZON SHIELD</h1>

<p align="center">
<b>Open, verifiable Japanese construction-cost and nursing-reimbursement data, plus key-less MCP servers.</b><br>
Every answer ships with a way to check it yourself. No account, no API key.
</p>

<p align="center">
<a href="https://shield.the-horizons-innovation.com">Website</a> ·
<a href="https://github.com/horizonshield/awesome-horizon-shield">Catalog</a>
</p>

<p align="center">
<a href="https://gate.horizonshield.dev/register"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fhorizonshield%2Fawesome-horizon-shield%2Fmain%2Fbadges%2Fverified.json" alt="conduct verified today"></a>
<a href="https://doi.org/10.5281/zenodo.21898745"><img src="https://img.shields.io/badge/JCCDB-DOI%20zenodo.21898745-1f7a8c" alt="JCCDB DOI"></a>
<a href="https://doi.org/10.5281/zenodo.22083722"><img src="https://img.shields.io/badge/JHNRD-DOI%20zenodo.22083722-1f7a8c" alt="JHNRD DOI"></a>
<img src="https://img.shields.io/badge/license-CC%20BY%204.0-1f7a8c" alt="CC BY 4.0">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/horizonshield/.github/main/profile/audit-example.png" alt="Example KIRA estimate audit" width="880">
</p>
<p align="center"><sub>An example KIRA audit. A 1,800,000 yen lump-sum exterior-paint quote, checked against open cost data.</sub></p>

---

### What we run

- **KIRA** audits a Japanese renovation estimate against **65,520 open cost items** ([JCCDB, DOI 10.5281/zenodo.21898745](https://doi.org/10.5281/zenodo.21898745)). It returns a fair-price range, the gap, and red flags. It never calls the contractor dishonest; it hands you the numbers and the sources.
- **JHNRD** is an open home-visit-nursing reimbursement database ([DOI 10.5281/zenodo.22083722](https://doi.org/10.5281/zenodo.22083722)). Each rule carries ranked sources, tiered statute over agency over commentary. It never says "you can bill this"; it shows the requirements and what is still unconfirmed.
- **JIDEC** is a Bitcoin-anchored public verification ledger. You recompute the hash yourself.
- **YAKUMO** is a directory of independently audited contractors, fail-closed.

### Check any of it in one command

```bash
curl -s https://gate.horizonshield.dev/register
```

Nothing here asks to be trusted. Everything can be recomputed from published bytes.

<sub>Operated by The HORIZONs K.K. · supervised by Toshikatsu Oga (ORCID 0009-0000-9180-903X) · text CC BY 4.0</sub>

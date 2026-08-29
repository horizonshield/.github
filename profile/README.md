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
<a href="https://modelcontextprotocol.io"><img src="https://img.shields.io/badge/protocol-MCP-2f6feb" alt="MCP"></a>
<a href="https://doi.org/10.5281/zenodo.21898745"><img src="https://img.shields.io/badge/JCCDB-10.5281%2Fzenodo.21898745-1682D4" alt="JCCDB DOI"></a>
<a href="https://doi.org/10.5281/zenodo.22083722"><img src="https://img.shields.io/badge/JHNRD-10.5281%2Fzenodo.22083722-1682D4" alt="JHNRD DOI"></a>
<a href="https://doi.org/10.5281/zenodo.21970931"><img src="https://img.shields.io/badge/Conduct%20Register-10.5281%2Fzenodo.21970931-1682D4" alt="Register DOI"></a>
<a href="https://orcid.org/0009-0000-9180-903X"><img src="https://img.shields.io/badge/ORCID-0009--0000--9180--903X-A6CE39" alt="ORCID"></a>
<a href="https://gate.horizonshield.dev/register"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fhorizonshield%2Fawesome-horizon-shield%2Fmain%2Fbadges%2Fverified.json" alt="Conduct verified today"></a>
<a href="https://registry.modelcontextprotocol.io"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fhorizonshield%2Fawesome-horizon-shield%2Fmain%2Fbadges%2Fservers.json" alt="Endpoints measured"></a>
<a href="https://shield.the-horizons-innovation.com/verify-directory/"><img src="https://img.shields.io/badge/verify%20directory-WEDJAT%20live-48d0dc" alt="WEDJAT verify directory, live"></a>
<a href="https://creativecommons.org/licenses/by/4.0/"><img src="https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey" alt="License"></a>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/horizonshield/.github/main/profile/audit-example.png" alt="Example KIRA estimate audit" width="880">
</p>
<p align="center"><sub>An example KIRA audit. A 1,800,000 yen lump-sum exterior-paint quote, checked against open cost data.</sub></p>

<p align="center">
<img src="https://raw.githubusercontent.com/ogasurfproject-jpg/hs-femtech-mcp/main/banner.jpg" alt="HORIZON SHIELD Femtech Registry: neutral, verifiable registry of femtech information sources. No diagnosis, no referral fees." width="880">
</p>
<p align="center"><sub>The same discipline, applied to women's health. The Femtech Registry verifies who publishes a source and under what disclosure — it never diagnoses.</sub></p>

---

### What we run

- **KIRA** audits a Japanese renovation estimate against **95,403 open cost items** ([JCCDB, DOI 10.5281/zenodo.21898745](https://doi.org/10.5281/zenodo.21898745)). It returns a fair-price range, the gap, and red flags. It never calls the contractor dishonest; it hands you the numbers and the sources.
- **JHNRD** is an open home-visit-nursing reimbursement database ([DOI 10.5281/zenodo.22083722](https://doi.org/10.5281/zenodo.22083722)). Each rule carries ranked sources, tiered statute over agency over commentary. It never says "you can bill this"; it shows the requirements and what is still unconfirmed.
- **JIDEC** is a Bitcoin-anchored public verification ledger. You recompute the hash yourself.
- **YAKUMO** is a directory of independently audited contractors, fail-closed.
- **Femtech Registry** verifies femtech (women's health) information sources by publisher, authority tier, jurisdiction, and machine-readable compensation, with a re-computable SHA-256. It never diagnoses, never claims a product works, and never takes a referral fee.

### Check any of it in one command

```bash
curl -s https://gate.horizonshield.dev/register
```

Nothing here asks to be trusted. Everything can be recomputed from published bytes.

<sub>Operated by The HORIZONs K.K. · supervised by Toshikatsu Oga (ORCID 0009-0000-9180-903X) · text CC BY 4.0</sub>

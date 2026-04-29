# Security Policy

## Supported Versions

Curious Factory supporte uniquement la dernière version stable de chaque produit. Pas de backport sur versions plus anciennes.

## Reporting a Vulnerability

Si tu découvres une vulnérabilité de sécurité, **n'ouvre pas une issue publique**. Disclose-la en privé pour qu'on puisse patcher avant de l'exposer.

Envoie un rapport détaillé à **security@curiousfactory.fr** avec :

- Description de la vulnérabilité et son impact
- Steps to reproduce (PoC, versions affectées, environnement)
- Suggested fix ou mitigation si tu en as une

Nous accusons réception sous **2 jours ouvrés** et donnons une évaluation initiale sous **5 jours ouvrés**. Patch shippé sous **30 jours** depuis confirmation, selon la sévérité.

Si la vulnérabilité est confirmée :

1. Nous coordonnons un timeline de disclosure avec toi
2. Tu es crédité dans les release notes (sauf si tu préfères rester anonyme)
3. GitHub Security Advisory (GHSA) publié avec CVE assignment si applicable

## Supply-chain Security

Les paquets npm publiés par Curious Factory sont signés avec [npm provenance attestations](https://docs.npmjs.com/generating-provenance-statements) et [SLSA build provenance](https://slsa.dev/). Vérification :

```bash
npm audit signatures
```

SBOMs (SPDX format) attachés à chaque release via GitHub artifact attestations.

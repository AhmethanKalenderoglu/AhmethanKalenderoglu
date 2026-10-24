# Ahmethan Kalenderoğlu

I build **VERIS**, a permissioned blockchain protocol for verifiable elections: every vote can be audited by anyone, while who voted for whom stays secret.

### Projects

- **[VERIS](https://github.com/verisproject)**: two-layer chain design, Pedersen-commitment tallies with zero-knowledge verification at the upper layer, hardware-attested voter identity. Live prototype at [canlisecim.com](https://canlisecim.com).
- **[veris-verify](https://github.com/AhmethanKalenderoglu/veris-verify)**: checks the Ed25519 signatures on the VERIS project sites. Bash, tested in CI.
- **[morse](https://github.com/AhmethanKalenderoglu/morse)**: two-way Morse code translator with sound output. Python, no dependencies.

### Contributions

- **[ethereum/py_ecc#162](https://github.com/ethereum/py_ecc/pull/162)**: fixed a stack overflow on Windows and wrong results for negative exponents in finite-field arithmetic.
- **[ethereum/execution-specs#3776](https://github.com/ethereum/execution-specs/pull/3776)**: unit tests for the new fork tool's codemods, which also caught a bug in constant rewriting.
- **[ethereum/execution-specs#3869](https://github.com/ethereum/execution-specs/pull/3869)**: failing tests with `--traces` now print the EVM trace as a compact table instead of one JSON object per step.
- **[hiero-ledger/hiero-sdk-python#2739](https://github.com/hiero-ledger/hiero-sdk-python/pull/2739)**: moved the token creation end-to-end tests to the shared environment fixture.

### Signed releases

Pages and releases I publish are signed with this SSH key:

`SHA256:Bsm2osevqT9KjFlaeqwNvaz7LqNCTDMqqveFLG5BmII`

How to verify: [ahmethankalenderoglu.com/dogrulama](https://ahmethankalenderoglu.com/dogrulama)

### Contact

ahmethan@ahmethankalenderoglu.com (for general)

ahmethan@veris.vote (for about veris project)
